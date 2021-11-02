# Writing Plugins

Here are some suggestions to make installing and using your plugin as simple as possible, no matter what ZSH framework (if any) someone is using.

1. Make using your plugin easier for everyone and put the plugin file at the root level of your plugin repository instead of hiding it in a subdirectory. This allows [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) users to install it with a simple `git clone git@github.com:you/yourplugin.git` in their `custom/plugins` directory and also lets [Antigen](https://github.com/zsh-users/antigen) and [zgenom](https://github.com/jandamm/zgenom) users let the framework automatically clone the repository without having to specify a subdirectory path.

2. Only oh-my-zsh sets the `${ZSH_CUSTOM}` variable. Relying on your plugin being in `${ZSH_CUSTOM}/yourPluginName` will make your plugin not work with anything but oh-my-zsh. `$(dirname $0)` will tell you what directory your plugin is actually installed in, is cross-framework and won't break when a user inevitably renames your plugin directory.

3. Don't assume your plugin will be checked out into a directory with the same name you gave the plugin. This is another case where `$(dirname ${0})` will work and `${ZSH_CUSTOM}/hardcoded-directory-name` will fail miserably.

4. Use `yourplugin.plugin.zsh` for the main plugin file. This is what [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) looks for. [Antigen](https://github.com/zsh-users/antigen), [zgenom](https://github.com/jandamm/zgenom) and most other ZSH frameworks will also automatically find and load that filename.

5. If you’re making a theme, include a screenshot so prospective users can see what it looks like without having to install it.

6. If your plugin adds any of its subdirectories to the user's `fpath`, make sure those subdirectories only contain function definition files. This allows for frameworks to correctly [zcompile all functions](http://zsh.sourceforge.net/Doc/Release/Functions.html#Autoloading-Functions). Please don't make your plugin add its root directory to the `fpath`.

7. Don't forget to add a license. [choosealicense.com](https://choosealicense.com) is a good tool to help you pick one if you don't have something specific already in mind.

8. Submit a PR here so your plugin is easy for users to find :-)
