# Writing Plugins and Themes

Here are some suggestions to make installing and using your plugin/theme as simple as possible for end users, no matter what ZSH framework (if any) they are using.

1. Make using your plugin easier for end users and put the plugin file at the root level of your plugin repository instead of hiding it in a subdirectory. This allows [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) users to install it with a simple `git clone git@github.com:you/yourplugin.git` in their `custom/plugins` directory and also lets [Antigen](https://github.com/zsh-users/antigen) and [zgenom](https://github.com/jandamm/zgenom) users let the framework automatically clone the repository without having to specify a subdirectory path.

2. Only put one plugin or theme in a repository. This makes using it a simple `git clone` for [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) users, and simpler for other framework users as well - they won't have to specify a subdirectory, just username/reponame.

3. Only oh-my-zsh sets the `${ZSH_CUSTOM}` variable. Relying on your plugin being in `${ZSH_CUSTOM}/yourPluginName` will make your plugin not work with anything but oh-my-zsh. `$(dirname $0)` will tell you what directory your plugin is actually installed in, is cross-framework and won't break when a user inevitably renames your plugin directory.

4. Don't assume your plugin will be checked out into a directory with the same name you gave the plugin. This is another case where `$(dirname ${0})` will work and `${ZSH_CUSTOM}/hardcoded-directory-name` will fail miserably.

5. Use `yourplugin.plugin.zsh` for the main plugin file. This is what [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) looks for. [Antigen](https://github.com/zsh-users/antigen), [zgenom](https://github.com/jandamm/zgenom) and most other ZSH frameworks will also automatically find and load that filename.

6. If you’re making a theme, include a screenshot so prospective users can see what it looks like without having to install it. If it relies on Powerline-compatible fonts or Nerdfonts, put that in the readme.

7. If your plugin adds any of its subdirectories to the user's `fpath`, make sure those subdirectories only contain function definition files. This allows for frameworks to correctly [zcompile all functions](http://zsh.sourceforge.net/Doc/Release/Functions.html#Autoloading-Functions). Please don't make your plugin add its root directory to the `fpath` - this will cause problems with `zcompile`.

8. Leave ZSH settings alone.
  - If you're using `setopt` to override the user's existing settings, you _will_ break someone's workflow. If you feel you absolutely must tweak `setopt` settings, make sure there's an easy way to disable your overrides - consider looking for a file named `~/.YOURPLUGIN_disable_SETTINGSNAME`.
  -  If you're touching the magic ZSH settings variables like `HISTSIZE`, _only do it if the variable is unset_. Wrap it in a `if [[ -z "$VARNAME" ]]; then` block so you don't step on a user's existing settings.

9. Don't forget to add a license. A lot of people won't use anything that doesn't have a license. [choosealicense.com](https://choosealicense.com) is a good tool to help you pick one if you don't already have something specific in mind.

10. Submit a PR or add an issue here at [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) so your plugin is easy for users to find :-)
