<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [awesome-zsh-plugins](#awesome-zsh-plugins)
  - [Frameworks](#frameworks)
  - [Tutorials](#tutorials)
    - [Antigen](#antigen)
    - [Oh-My-Zsh](#oh-my-zsh)
    - [Prezto](#prezto)
  - [Plugins](#plugins)
  - [Themes](#themes)
  - [Even more completions](#even-more-completions)
  - [Installation](#installation)
    - [[Antigen](https://github.com/zsh-users/antigen)](#antigenhttpsgithubcomzsh-usersantigen)
    - [[dotzsh](https://github.com/dotphiles/dotzsh)](#dotzshhttpsgithubcomdotphilesdotzsh)
    - [[Oh-My-Zsh](http://ohmyz.sh/)](#oh-my-zshhttpohmyzsh)
    - [[Prezto](https://github.com/sorin-ionescu/prezto)](#preztohttpsgithubcomsorin-ionescuprezto)
    - [[Zgen](https://github.com/tarjoilija/zgen)](#zgenhttpsgithubcomtarjoilijazgen)
  - [Writing New Plugins](#writing-new-plugins)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# awesome-zsh-plugins

[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

## Frameworks

These frameworks make customizing your zsh setup easier.

* [alf](https://github.com/psyrendust/alf) - Alf is an out of this world super fast and configurable framework for zsh; it's modeled after Prezto and Antigen while utilizing Oh My Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.
* [ant-zsh](https://github.com/anthraxx/ant-zsh) - Tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.
* [antigen-hs](https://github.com/Tarrasch/antigen-hs) - A replacement for antigen optimized for a low overhead when starting up the shell.
* [antigen](https://github.com/zsh-users/antigen) - Antigen is a small set of functions that help you easily manage your shell (zsh) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to zsh, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins.
* [dotzsh](https://github.com/dotphiles/dotzsh) - dotzsh strives to be platform and version independent, some functionality may be lost when running under older versions of zsh, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.
* [oh-my-zsh](http://ohmyz.sh/) - A community-driven framework for managing your zsh configuration. Includes 120+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool so that makes it easy to keep up with the latest updates from the community.
* [prezto](https://github.com/sorin-ionescu/prezto) - Prezto enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes
* [zeesh](https://github.com/zeekay/zeesh) - Zeesh is a cross-platform Zsh framework. It's similar to, but incompatible with, oh-my-zsh. It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.
* [zgen](https://github.com/tarjoilija/zgen) - A lightweight plugin manager for ZSH inspired by antigen, but optimized for speed when starting a new shell. Can load oh-my-zsh compatible plugins and themes.
* [zilsh](https://github.com/zilsh/zilsh) - A zsh config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen. 
* [zoppo](https://github.com/zoppo/zoppo) - the crippled configuration framework for Zsh. As an italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.
* [ztanesh](https://github.com/miohtama/ztanesh) - Improve your UNIX command line experience and productivity with the the configuration provided by ztanesh project: the tools will make your shell more powerful and easier to use.

Not a framework, but still useful

* [zshdb](https://github.com/rocky/zshdb) ZSH debugger

## Tutorials

* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) - Seth Brown's tutorial on combining zsh, tmux and vim.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework
* [ZSH Tips by ZZapper](http://www.rayninfo.co.uk/tips/zshtips.html) - ZZapper's list of tips
* [http://strcat.de/zsh/#tipps](http://strcat.de/zsh/#tipps) - an exhaustive list of ZSH tips by Christian Schneider
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh) - Arch Linux's ZSH intro

### Antigen
* [Using Antigen to Manage your Zsh installation](http://danryan.co/using-antigen-for-zsh.html) - Dan Ryan's blog post on switching to Antigen
* [http://mgdm.net/weblog/zsh-antigen](http://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.

### Oh-My-Zsh
* [ZSH Gem 24](http://www.refining-linux.org/archives/59/ZSH-Gem-24-ZSH-frameworks/) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.
* [Mark Nichols' Oh-My-Zsh tutorial](http://zanshin.net/2011/08/12/oh-my-zsh/)

### Prezto
* [A Beautifully Productive Terminal Experience](http://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Mike Buss' blog post about using Prezto, Tmux & Tmuxinator.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) - Linh M. Tran's post about transitioning to Prezto from Oh-My-Zsh
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto

## Plugins

* [accurev-zsh](https://github.com/dalefukami/accurev-zsh) ZSH plugin for accurev
* [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>
* [autoupdate-antigen.zshplugin](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [blackbox](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a git repository.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - browse-commit is a zsh plugin that lets you open any commit in your browser from the command line.
* [caniuse.plugin.zsh](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](http://caniuse.com) support to ZSH
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - zsh plugin to cd to git repository root directory
* [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - zsh plugin to copy your shell configuration to another machine over ssh
* [czhttpd](https://github.com/jsks/czhttpd) - Simple http server written in 99.9% pure zsh.
* [deer](https://github.com/Vifon/deer) - file navigator for zsh heavily inspired by [ranger](http://ranger.nongnu.org/).
* [depot-tools](https://github.com/jgrowl/depot_tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - zsh plugin that lets you use zeus with normal rails commands
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used git commands
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra git helper scripts I've collected over time.
* [git-it-on.zsh](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on github. Only works on OS X.
* [gitignore.plugin.zsh](https://github.com/voronkovich/gitignore.plugin.zsh) - zsh plugin for creating `.gitignore` files
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell
* [hooks](https://github.com/willghatch/zsh-hooks) - add missing hooks - for plugins and personal use
* [jvm](https://github.com/mgryszko/jvm) - Allows selection of JDK on OS X
* [k](https://github.com/supercrabtree/k) - Directory listings for zsh with git features.
* [kitsunebook.plugin.zsh](https://github.com/d12frosted/kitsunebook.plugin.zsh/blob/master/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for Oh-My-Zsh
* [mysql.plugin.zsh](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql
* [mysql-colorize](https://github.com/horosgrisa/mysql-colorize) - Colors for mysql tables
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - maps exit status code to human readable string
* [oh-my-dogesh](https://github.com/keithhamilton/oh-my-dogesh) dogification plugin
* [oh-my-zsh-dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - plugin for displaying dirstack info on a single line
* [oh-my-zsh-flow3-plugin](https://github.com/sandstorm/oh-my-zsh-flow3-plugin) - This plugin makes the flow command available inside every subdirectory of the TYPO3 Flow distribution
* [oh-my-zsh-jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRAs from the command line
* [oh-my-zsh-virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - fork of the virtualenv plugin from upstream. It adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [opp.zsh](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for zsh.
* [osx-dev-zsh-plugin](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on my OSX install
* [otter](https://github.com/allanhortle/otter) - combination theme and plugin by Allan Hortle
* [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct virtualenvs so they don't conflict with any other python requirements on your system.
* [pretty-time-zsh](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [robo-zsh-plugin](https://github.com/shengyou/robo-zsh-plugin) - a zsh plugin for [Robo](http://codegyre.github.io/Robo/)
* [rvm-zsh](https://github.com/johnhamelink/rvm-zsh) - plugin which initiates RVM and adds rubygem binaries (like compass) accessible in the user's $PATH
* [send.zsh](https://github.com/robertzk/send.zsh) - Shortcut script for zsh
* [sf2.plugin.zsh](https://github.com/voronkovich/sf2.plugin.zsh) - ZSH plugin for Symfony2
* [smart-cd](https://github.com/secrettriangle/smart-cd) - runs `ls` and `git status` after chpwd
* [snippets](https://github.com/willghatch/zsh-snippets) - command line snippet expansion
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins
* [wd](https://github.com/mfaerevaag/wd) - (warp directory) lets you jump to custom directories in zsh, without using cd. Why? Because cd seems ineffecient when the folder is frequently visited or has a long path.
* [yeoman-zsh-plugin](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for Oh My ZSH, compatible with yeoman version ≥1.0 (includes options and command auto-completion)
* [zaw-extras](https://github.com/willghatch/zsh-zaw-extras) - Extras for zaw. Make sure you load zaw first.
* [zaw](https://github.com/zsh-users/zaw) - zsh anything.el-like widget
* [zce](https://github.com/hchbaw/zce.zsh) - vim’s EasyMotion / Emacs’s ace-jump-mode for zsh.
* [zsh-256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen TERM environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [zsh-add-upstream](https://github.com/caarlos0/zsh-add-upstream) - plugin to easily add the upstream remote to your git fork
* [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a .env file, it will automatically be executed when you cd into it.
* [autoenv](https://github.com/horosgrisa/autoenv) - Extended version of this ↑ plugin
* [zsh-autosuggestions](https://github.com/tarruda/zsh-autosuggestions) - [Fish](http://fishshell.com/)-like fast/unobtrusive autosuggestions for zsh.
* [zsh-basex](https://github.com/dirkk/zsh-basex) - adds several [BaseX](http://www.basex.org) aliases for simplified usage
* [zsh-bash](https://github.com/chrissicool/zsh-bash) - plugin to make ZSH more Bash compatible. It redefines the source command to act more like Bash does. It also enables Bash completions.
* [zsh-bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`
* [zsh-colors](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works
* [zsh-dircolors-solarized](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin
* [zsh-directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for zsh.
* [zsh-dwim](https://github.com/oknowton/zsh-dwim) - zsh-dwim attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [zsh-functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [zsh-geeknote](https://github.com/s7anley/zsh-geeknote) - Geeknote plugin for zsh
* [zsh-git-sync](https://github.com/caarlos0/zsh-git-sync) - A zsh plugin to sync git repositories and clean them up.
* [zsh-grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for grunt
* [zsh-gvm](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for gvm(Groovy enVironment Manager)
* [zsh-gvm](https://github.com/horosgrisa/zsh-gvm) - gvm (Go version manager) plugin for zsh
* [zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after zsh-syntax-highlighting, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md
* [zsh-konsole-theme-changer](https://github.com/horosgrisa/zsh-konsole-theme-changer) - Toggle konsole theme from zsh
* [zsh-manydots-magic](https://github.com/knu/zsh-manydots-magic) - manydots-magic - zle tweak for emulating `...'==`../..' etc.
* [zsh-nodejs-plugin](https://github.com/poying/zsh-nodejs-plugin) - nodejs plugin for zsh
* [zsh-notify](https://github.com/marzocchi/zsh-notify) - A plugin for the Z shell (on OS X and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [zsh-open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [zsh-pg](https://github.com/caarlos0/zsh-pg) utility functions to work with PosgreSQL
* [zsh-plugin-ibtool](https://github.com/RudthMael/zsh-plugin-ibtool) - ibtool shortcuts to generate localized XIB files
* [zsh-plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your zsh. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [zsh-t32](https://github.com/chrissicool/zsh-t32) - plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [zsh-url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the zsh syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [zsh-vim-mode](sharat87/zsh-vim-mode) - Shrikant Sharat's bindings for zsh's vi mode so it behaves more vim-like
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh

## Themes

If you're using [Antigen](https://github.com/zsh-lovers/antigen), you can test these themes in a running zsh with `antigen theme githubuser/repo`. If you're using [zgen](https://github.com/tarjoilija/zgen), add them to your `init.zsh` with `zgen load githubuser/reponame`.

* [MaxUlysse/myzsh](https://github.com/MaxUlysse/myzsh) Maxime Garcia's myzsh theme.
* [af-magic-mod](antigen theme desyncr/zshrc themes/af-magic-mod) - af-magic-mod theme. Install with `antigen theme desyncr/zshrc themes/af-magic-mod`
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme) - Add with `antigen theme caiogondim/bullet-train-oh-my-zsh-theme bullet-train`
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) Red version of the frisk theme from oh-my-zsh
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & ZSH
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character.  Requires [hooks](https://github.com/willghatch/zsh-hooks) plugin.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and zsh
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for Oh My ZSH used by Frédéric de Villamil.
* [pure](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt.
* [rummik/zsh-theme](https://github.com/rummik/zsh-theme) Rummik's theme
* [zero](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin
* [zsh-prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight zsh prompt, based on the powerline font from the popular eponymous vim plugin, which works well for a dark background.

## Even more completions

These plugins add tab completion without adding extra functions or aliases.

* [berkshelf-zsh-plugin](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - oh-my-zsh-compatible plugin for BOSH autocompletion
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal
* [codeception-zsh-plugin](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer
* [docker-enter-completion](https://github.com/runcom/docker-enter-completion) - command completion for docker-enter (https://github.com/jpetazzo/nsenter)
* [docker-zsh-completion](https://github.com/felixr/docker-zsh-completion) - Add completions for docker
* [docker-zsh](https://github.com/adrien-f/docker-zsh) - Adds tab completion for docker
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for zsh
* [etcdctl-zsh](https://github.com/sheax0r/etcdctl-zsh) - etcdctl autocomplete plugin for oh-my-zsh
* [git-flow-completion](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for git-flow
* [grid5000-zsh-plugin](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions
* [gulp-autocompletion-zsh](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp autocomplete for oh-my-zsh/antigen
* [jumpstorm-zsh-plugin](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm)
* [oh-my-zsh-nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for the nova so you don't need to remember all those pesky arguments
* [oh-my-zsh_razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor](https://github.com/puppetlabs/Razor)
* [rake-completion.zshplugin](https://github.com/unixorn/rake-completion.zshplugin) - Add tab completion for rakefile targets
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Oh-My-Zsh plugin for autocompletion of [tugboat](https://github.com/pearkes/tugboat/) command
* [zsh-cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - add tab completion for cabal
* [zsh-completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Load it last so it doesn't override completions provided by your other plugins.
* [zsh-completions](https://github.com/zsh-users/zsh-completions) is a collection of extra completions for zsh. To use it, add `antigen bundle zsh-users/zsh-completions src` to your .zshrc
* [zsh-pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion pulgin for oh-my-zsh/antigen
* [zsh-pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - pip autocomplete plugin for oh-my-zsh/antigen

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start zsh. You can also add the plugin to a running zsh with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3. Open a new zsh terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Most of these plugins can be installed by adding `zgen load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgen load` calls in.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).
