# awesome-zsh-plugins

Collection of zsh plugins inspired by the various awesome list collections out there.

## Frameworks

These frameworks make customizing your zsh setup easier. 

* [alf](https://github.com/psyrendust/alf) - Alf is an out of this world super fast and configurable framework for zsh; it's modeled after Prezto and Antigen while utilizing Oh My Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.
* [antigen-hs](https://github.com/Tarrasch/antigen-hs) - A replacement for antigen optimized for a low overhead when starting up the shell.
* [antigen](https://github.com/zsh-users/antigen) - Antigen is a small set of functions that help you easily manage your shell (zsh) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to zsh, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins.
* [dotzsh](https://github.com/dotphiles/dotzsh) - dotzsh strives to be platform and version independent, some functionality may be lost when running under older versions of zsh, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OS's without problems.
* [oh-my-zsh](http://ohmyz.sh/) - A community-driven framework for managing your zsh configuration. Includes 120+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool so that makes it easy to keep up with the latest updates from the community.
* [prezto](https://github.com/sorin-ionescu/prezto) - Prezto enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes
* [zshuery](https://github.com/myfreeweb/zshuery) - A simpler zsh configuration framework. jQuery did this for JS, we're doing it for zsh. 

## Plugins

* [chrissicool/zsh-256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen TERM environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [djui/alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [tarrasch/zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a .env file, it will automatically be executed when you cd into it.
* [tarruda/zsh-autosuggestions](https://github.com/tarruda/zsh-autosuggestions) - [Fish](http://fishshell.com/)-like fast/unobtrusive autosuggestions for zsh.
* [unixorn/autoupdate-antigen.zshplugin](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [tarrasch/zsh-bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`
* [berkshelf/berkshelf-zsh-plugin](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf
* [stackExchange/blackbox](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a git repository.
* [adolfoabegg/browse-commit](https://github.com/adolfoabegg/browse-commit) - browse-commit is a zsh plugin that lets you open any commit in your browser from the command line.
* [tarrasch/zsh-colors](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works
* [adrien-f/docker-zsh](https://github.com/adrien-f/docker-zsh) - Adds tab completion for docker
* [oknowton/zsh-dwim](https://github.com/oknowton/zsh-dwim) - zsh-dwim attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [s7anley/zsh-geeknote](https://github.com/s7anley/zsh-geeknote) - Geeknote plugin for zsh
* [unixorn/git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra git helper scripts I've collected over time.
* [voronkovich/gitignore.plugin.zsh](https://github.com/voronkovich/gitignore.plugin.zsh) - zsh plugin for creating `.gitignore` files
* [clauswitt/zsh-grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for grunt
* [yerinle/zsh-gvm](https://github.com/yerinle/zsh-gvm) Provides autocompletion for gvm(Groovy enVironment Manager)
* [zsh-users/zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after zsh-syntax-highlighting, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md
* [supercrabtree/k](https://github.com/supercrabtree/k) - Directory listings for zsh with git features.
* [voronkovich/mysql.plugin.zsh](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql
* [dalang/oh-my-zsh_razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor](https://github.com/puppetlabs/Razor)
* [unixorn/rake-completion.zshplugin](https://github.com/unixorn/rake-completion.zshplugin) - Add tab completion for rakefile targets
* [ascii-soup/zsh-url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the zsh syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [zsh-users/zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your zsh. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.

## Themes

* [arialdomartini/oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and zsh
* [caiogondim/bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme) - Add with `antigen theme caiogondim/bullet-train-oh-my-zsh-theme bullet-train`
* [sindresorhus/pure](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt.
* [Valodim/zsh-prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight zsh prompt, based on the powerline font from the popular eponymous vim plugin, which works well for a dark background.

## Even more completions

* [felixr/docker-zsh-completion](https://github.com/felixr/docker-zsh-completion) - Add completions for docker
* [zsh-users/zsh-completions](https://github.com/zsh-users/zsh-completions) is a collection of extra completions for zsh. To use it, add `antigen bundle zsh-users/zsh-completions src` to your .zshrc
* [RobSis/zsh-completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Load it last so it doesn't override completions provided by your other plugins.

## Installation

### Antigen

Most of these plugins can be installed by just adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically.

### dotzsh

1. Clone new plugins into `.zsh.local/modules
2. Load the plugin module in `.zshrc`
3. Open a new zsh terminal window or tab

### Oh-My-Zsh

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. add the repo to your plugin list

### Prezto

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab
