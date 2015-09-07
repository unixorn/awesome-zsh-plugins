
# awesome-zsh-plugins
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Frameworks](#frameworks)
- [Tutorials](#tutorials)
  - [Antigen](#antigen)
  - [Oh-My-Zsh](#oh-my-zsh)
  - [Prezto](#prezto)
- [Plugins](#plugins)
- [Themes](#themes)
  - [Fonts](#fonts)
- [Even more completions](#even-more-completions)
- [Installation](#installation)
  - [[Antigen](https://github.com/zsh-users/antigen)](#antigenhttpsgithubcomzsh-usersantigen)
  - [[dotzsh](https://github.com/dotphiles/dotzsh)](#dotzshhttpsgithubcomdotphilesdotzsh)
  - [[Oh-My-Zsh](http://ohmyz.sh/)](#oh-my-zshhttpohmyzsh)
  - [[Prezto](https://github.com/sorin-ionescu/prezto)](#preztohttpsgithubcomsorin-ionescuprezto)
  - [[Zgen](https://github.com/tarjoilija/zgen)](#zgenhttpsgithubcomtarjoilijazgen)
- [Writing New Plugins](#writing-new-plugins)
- [Other Resources](#other-resources)
  - [Other lists](#other-lists)
  - [Other References](#other-references)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](Contributing.md) before contributing.*

## Frameworks

These frameworks make customizing your zsh setup easier.

* [alf ![GitHub stars](https://img.shields.io/github/stars/psyrendust/alf.svg)](https://github.com/psyrendust/alf) - Alf is an out of this world super fast and configurable framework for zsh; it's modeled after Prezto and Antigen while utilizing Oh My Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.
* [ant-zsh ![GitHub stars](https://img.shields.io/github/stars/anthraxx/ant-zsh.svg)](https://github.com/anthraxx/ant-zsh) - Tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.
* [antibody ![GitHub stars](https://img.shields.io/github/stars/caarlos0/antibody.svg)](https://github.com/caarlos0/antibody) - A simpler and faster replacement for antigen written in Go that can do stuff in parallel.
* [antigen-hs ![GitHub stars](https://img.shields.io/github/stars/Tarrasch/antigen-hs.svg)](https://github.com/Tarrasch/antigen-hs) - A replacement for antigen optimized for a low overhead when starting up the shell.
* [antigen ![GitHub stars](https://img.shields.io/github/stars/zsh-users/antigen.svg)](https://github.com/zsh-users/antigen) - Antigen is a small set of functions that help you easily manage your shell (zsh) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to zsh, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins.
* [dotzsh ![GitHub stars](https://img.shields.io/github/stars/dotphiles/dotzsh.svg)](https://github.com/dotphiles/dotzsh) - Dotzsh strives to be platform and version independent, some functionality may be lost when running under older versions of zsh, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.
* [fresh ![GitHub stars](https://img.shields.io/github/stars/freshshell/fresh.svg)](https://github.com/freshshell/fresh) - Framework to keep your dotfiles fresh
* [oh-my-zsh ![GitHub stars](https://img.shields.io/github/stars/robbyrussell/oh-my-zsh.svg)](http://ohmyz.sh/) - A community-driven framework for managing your zsh configuration. Includes 120+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool so that makes it easy to keep up with the latest updates from the community.
* [prezto ![GitHub stars](https://img.shields.io/github/stars/sorin-ionescu/prezto.svg)](https://github.com/sorin-ionescu/prezto) - Prezto enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes
* [zeesh ![GitHub stars](https://img.shields.io/github/stars/zeekay/zeesh.svg)](https://github.com/zeekay/zeesh) - Zeesh is a cross-platform Zsh framework. It's similar to, but incompatible with, oh-my-zsh. It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.
* [zgen ![GitHub stars](https://img.shields.io/github/stars/tarjoilija/zgen.svg)](https://github.com/tarjoilija/zgen) - A lightweight plugin manager for ZSH inspired by antigen, but optimized for speed when starting a new shell. Can load oh-my-zsh compatible plugins and themes.
* [zilsh ![GitHub stars](https://img.shields.io/github/stars/zilsh/zilsh.svg)](https://github.com/zilsh/zilsh) - A zsh config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.
* [zoppo ![GitHub stars](https://img.shields.io/github/stars/zoppo/zoppo.svg)](https://github.com/zoppo/zoppo) - The crippled configuration framework for Zsh. As an italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.
* [ZPM ![GitHub stars](https://img.shields.io/github/stars/horosgrisa/ZPM.svg)](https://github.com/horosgrisa/ZPM) - Plugin manager for zsh similar to vim-plug.
* [ztanesh ![GitHub stars](https://img.shields.io/github/stars/miohtama/ztanesh.svg)](https://github.com/miohtama/ztanesh) - Improve your UNIX command line experience and productivity with the the configuration provided by ztanesh project: the tools will make your shell more powerful and easier to use.

Not a framework, but still useful

* [zshdb ![GitHub stars](https://img.shields.io/github/stars/rocky/zshdb.svg)](https://github.com/rocky/zshdb) - A ZSH debugger

## Tutorials

* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) - Seth Brown's tutorial on combining zsh, tmux and vim.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - an exhaustive list of ZSH tips by Christian Schneider.
* [ZSH Tips by ZZapper](http://www.rayninfo.co.uk/tips/zshtips.html) - ZZapper's list of tips.
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh) - Arch Linux's ZSH introduction.
* [http://commandlinepoweruser.com/](http://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.

### Antigen
* [Using Antigen to Manage your Zsh installation](http://danryan.co/using-antigen-for-zsh.html) - Dan Ryan's blog post on switching to Antigen.
* [http://mgdm.net/weblog/zsh-antigen](http://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.

### Oh-My-Zsh
* [ZSH Gem 24](http://www.refining-linux.org/archives/59/ZSH-Gem-24-ZSH-frameworks/) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.
* [Mark Nichols' Oh-My-Zsh tutorial](http://zanshin.net/2011/08/12/oh-my-zsh/)

### Prezto
* [A Beautifully Productive Terminal Experience](http://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Mike Buss' blog post about using Prezto, Tmux & Tmuxinator.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) - Linh M. Tran's post about transitioning to Prezto from Oh-My-Zsh.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

## Plugins

* [accurev-zsh ![GitHub stars](https://img.shields.io/github/stars/dalefukami/accurev-zsh.svg)](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for accurev.
* [alias-tips ![GitHub stars](https://img.shields.io/github/stars/djui/alias-tips.svg)](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [ansiweather ![GitHub stars](https://img.shields.io/github/stars/fcambus/ansiweather.svg)](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols
* [anyframe ![GitHub stars](https://img.shields.io/github/stars/mollifier/anyframe.svg)](https://github.com/mollifier/anyframe) - peco/percol/fzf wrapper plugin for zsh.
* [autoenv ![GitHub stars](https://img.shields.io/github/stars/horosgrisa/autoenv.svg)](https://github.com/horosgrisa/autoenv) - Extended version of the zsh-autoenv plugin.
* [auto-fu.zsh ![GitHub stars](https://img.shields.io/github/stars/hchbaw/auto-fu.zsh.svg)](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [autoupdate-antigen.zshplugin ![GitHub stars](https://img.shields.io/github/stars/unixorn/autoupdate-antigen.zshplugin.svg)](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [blackbox ![GitHub stars](https://img.shields.io/github/stars/StackExchange/blackbox.svg)](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a git repository.
* [browse-commit ![GitHub stars](https://img.shields.io/github/stars/adolfoabegg/browse-commit.svg)](https://github.com/adolfoabegg/browse-commit) - browse-commit lets you open any commit in your browser from the command line.
* [calc ![GitHub stars](https://img.shields.io/github/stars/arzzen/calc.plugin.zsh.svg)](https://github.com/arzzen/calc.plugin.zsh) - calculator for zsh
* [caniuse.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/walesmd/caniuse.plugin.zsh.svg)](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](http://caniuse.com) support to ZSH.
* [cd-gitroot ![GitHub stars](https://img.shields.io/github/stars/mollifier/cd-gitroot.svg)](https://github.com/mollifier/cd-gitroot) - A zsh plugin to cd to git repository root directory.
* [cdbk ![GitHub stars](https://img.shields.io/github/stars/MikeDacre/cdbk.svg)](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [copyzshell ![GitHub stars](https://img.shields.io/github/stars/rutchkiwi/copyzshell.svg)](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over ssh.
* [czhttpd ![GitHub stars](https://img.shields.io/github/stars/jsks/czhttpd.svg)](https://github.com/jsks/czhttpd) - Simple http server written in 99.9% pure zsh.
* [deer ![GitHub stars](https://img.shields.io/github/stars/Vifon/deer.svg)](https://github.com/Vifon/deer) - A file navigator for zsh heavily inspired by [ranger](http://ranger.nongnu.org/).
* [depot-tools ![GitHub stars](https://img.shields.io/github/stars/jgrowl/depot_tools.svg)](https://github.com/jgrowl/depot_tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [elixir-oh-my-zsh ![GitHub stars](https://img.shields.io/github/stars/gusaiani/elixir-oh-my-zsh.svg)](https://github.com/gusaiani/elixir-oh-my-zsh) - Oh My Zsh plugin for Elixir, IEX, Mix and Phoenix
* [enhancd ![GitHub stars](https://img.shields.io/github/stars/b4b4r07/enhancd.svg)](https://github.com/b4b4r07/enhancd) - A simple tool that provides enhanced `cd` command
* [fzf-marks ![GitHub stars](https://img.shields.io/github/stars/uvaes/fzf-marks.svg)](https://github.com/uvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in Bash and Zsh, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [get-jquery ![GitHub stars](https://img.shields.io/github/stars/voronkovich/get-jquery.plugin.zsh.svg)](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from code.jquery.com
* [ghost-zeus ![GitHub stars](https://img.shields.io/github/stars/fontno/ghost_zeus.svg)](https://github.com/fontno/ghost_zeus) - Lets you use zeus with normal rails commands.
* [git-aliases.zsh ![GitHub stars](https://img.shields.io/github/stars/peterhurford/git-aliases.zsh.svg)](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used git commands.
* [git-extra-commands ![GitHub stars](https://img.shields.io/github/stars/unixorn/git-extra-commands.svg)](https://github.com/unixorn/git-extra-commands) - Extra git helper scripts packaged as a plugin.
* [gitfast ![GitHub stars](https://img.shields.io/github/stars/tevren/gitfast-zsh-plugin.svg)](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [git-it-on.zsh ![GitHub stars](https://img.shields.io/github/stars/peterhurford/git-it-on.zsh.svg)](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [gitignore.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/voronkovich/gitignore.plugin.zsh.svg)](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
* [goenv ![GitHub stars](https://img.shields.io/github/stars/bbenne10/goenv.svg)](https://github.com/bbenne10/goenv) - Antigen plugin to manage $GOPATH similarly to Python's virtualenvwrapper.
* [grep2awk ![GitHub stars](https://img.shields.io/github/stars/joepvd/grep2awk.svg)](https://github.com/joepvd/grep2awk) - ZLE widget to transform grep command into awk command.
* [hipchat ![GitHub stars](https://img.shields.io/github/stars/robertzk/hipchat.zsh.svg)](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [hooks ![GitHub stars](https://img.shields.io/github/stars/willghatch/zsh-hooks.svg)](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
* [jvm ![GitHub stars](https://img.shields.io/github/stars/mgryszko/jvm.svg)](https://github.com/mgryszko/jvm) - Allows selection of JDK on OS X.
* [k ![GitHub stars](https://img.shields.io/github/stars/supercrabtree/k.svg)](https://github.com/supercrabtree/k) - Directory listings for zsh with git features.
* [kitsunebook.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/d12frosted/kitsunebook.plugin.zsh.svg)](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [lesaint-mvn ![GitHub stars](https://img.shields.io/github/stars/lesaint/lesaint-mvn.svg)](https://github.com/lesaint/lesaint-mvn) - Maven plugins for Oh-My-Zsh.
* [mac-packaging ![GitHub stars](https://img.shields.io/github/stars/Temikus/mac-packaging.svg)](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with Munki
* [mysql.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/voronkovich/mysql.plugin.zsh.svg)](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [mysql-colorize ![GitHub stars](https://img.shields.io/github/stars/horosgrisa/mysql-colorize.svg)](https://github.com/horosgrisa/mysql-colorize) - Colors for mysql tables.
* [nice-exit-code ![GitHub stars](https://img.shields.io/github/stars/bric3/nice-exit-code.svg)](https://github.com/bric3/nice-exit-code) - Maps exit status code to human readable string.
* [node.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/srijanshetty/node.plugin.zsh.svg)](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for zsh with caching of nvm completions and autoloading of nvm if present.
* [oh-my-dogesh ![GitHub stars](https://img.shields.io/github/stars/keithhamilton/oh-my-dogesh.svg)](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [oh-my-zsh-dirstack ![GitHub stars](https://img.shields.io/github/stars/gepoch/oh-my-zsh-dirstack.svg)](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line.
* [oh-my-zsh-flow3-plugin ![GitHub stars](https://img.shields.io/github/stars/sandstorm/oh-my-zsh-flow3-plugin.svg)](https://github.com/sandstorm/oh-my-zsh-flow3-plugin) - This plugin makes the flow command available inside every subdirectory of the TYPO3 Flow distribution.
* [oh-my-zsh-jira-plus ![GitHub stars](https://img.shields.io/github/stars/gerges/oh-my-zsh-jira-plus.svg)](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRAs from the command line.
* [oh-my-zsh-virtualenv-prompt ![GitHub stars](https://img.shields.io/github/stars/tonyseek/oh-my-zsh-virtualenv-prompt.svg)](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. It adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [opp.zsh ![GitHub stars](https://img.shields.io/github/stars/hchbaw/opp.zsh.svg)](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for zsh.
* [osx-dev-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/marshallmick007/osx-dev-zsh-plugin.svg)](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on my OSX install.
* [otter ![GitHub stars](https://img.shields.io/github/stars/allanhortle/otter.svg)](https://github.com/allanhortle/otter) - Combination theme and plugin by Allan Hortle.
* [pantheon-terminal-notify-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/deyvisonrocha/pantheon-terminal-notify-zsh-plugin.svg)](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - background notifications for long running commands. Supports Elementary OS Freya
* [parallels-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/benclark/parallels-zsh-plugin.svg)](https://github.com/benclark/parallels-zsh-plugin) - Parallels desktop plugin
* [pip-app ![GitHub stars](https://img.shields.io/github/stars/sharat87/pip-app.svg)](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct virtualenvs so they don't conflict with any other python requirements on your system.
* [pretty-time-zsh ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/pretty-time-zsh.svg)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [robo-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/shengyou/robo-zsh-plugin.svg)](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](http://codegyre.github.io/Robo/)
* [rvm-zsh ![GitHub stars](https://img.shields.io/github/stars/johnhamelink/rvm-zsh.svg)](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's $PATH
* [safe-paste](https://github.com/oz/safe-paste) - safe-paste plugin. See [http://cirw.in/blog/bracketed-paste](http://cirw.in/blog/bracketed-paste)
* [send.zsh ![GitHub stars](https://img.shields.io/github/stars/robertzk/send.zsh.svg)](https://github.com/robertzk/send.zsh) - Shortcut script for zsh.
* [sf2.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/voronkovich/sf2.plugin.zsh.svg)](https://github.com/voronkovich/sf2.plugin.zsh) - ZSH plugin for Symfony2.
* [smart-cd ![GitHub stars](https://img.shields.io/github/stars/secrettriangle/smart-cd.svg)](https://github.com/secrettriangle/smart-cd) - Runs `ls` and `git status` after chpwd.
* [snippets ![GitHub stars](https://img.shields.io/github/stars/willghatch/zsh-snippets.svg)](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [sysadmin-util ![GitHub stars](https://img.shields.io/github/stars/skx/sysadmin-util.svg)](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [vimman ![GitHub stars](https://img.shields.io/github/stars/yonchu/vimman.svg)](https://github.com/yonchu/vimman) - View vim plugin manuals (help) like man in zsh
* [wakatime ![GitHub stars](https://img.shields.io/github/stars/wbinglee/zsh-wakatime.svg)](https://github.com/mfaerevaag/wd) - Automatic time tracking for commands in ZSH using [wakatime](http://wakatime.com/)
* [wd ![GitHub stars](https://img.shields.io/github/stars/mfaerevaag/wd.svg)](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in zsh, without using cd. Why? Because cd seems ineffecient when the folder is frequently visited or has a long path.
* [yeoman-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/edouard-lopez/yeoman-zsh-plugin.svg)](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for Oh My ZSH, compatible with yeoman version ≥1.0 (includes options and command auto-completion)
* [zaw ![GitHub stars](https://img.shields.io/github/stars/zsh-users/zaw.svg)](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
* [zce ![GitHub stars](https://img.shields.io/github/stars/hchbaw/zce.zsh.svg)](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for zsh.
* [zero ![GitHub stars](https://img.shields.io/github/stars/arlimus/zero.zsh.svg)](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zsh-256color ![GitHub stars](https://img.shields.io/github/stars/chrissicool/zsh-256color.svg)](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen TERM environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [zsh-add-upstream ![GitHub stars](https://img.shields.io/github/stars/caarlos0/zsh-add-upstream.svg)](https://github.com/caarlos0/zsh-add-upstream) - Easily add the upstream remote to your git fork.
* [zsh-async ![GitHub stars](https://img.shields.io/github/stars/mafredri/zsh-async.svg)](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in zsh without requiring any external tools.
* [zsh-autoenv ![GitHub stars](https://img.shields.io/github/stars/Tarrasch/zsh-autoenv.svg)](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a .env file, it will automatically be executed when you cd into it.
* [zsh-autosuggestions ![GitHub stars](https://img.shields.io/github/stars/tarruda/zsh-autosuggestions.svg)](https://github.com/tarruda/zsh-autosuggestions) - [Fish](http://fishshell.com/)-like fast/unobtrusive autosuggestions for zsh.
* [zsh-basex ![GitHub stars](https://img.shields.io/github/stars/dirkk/zsh-basex.svg)](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://www.basex.org) aliases for simplified usage.
* [zsh-bash ![GitHub stars](https://img.shields.io/github/stars/chrissicool/zsh-bash.svg)](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like Bash does. It also enables Bash completions.
* [zsh-bd ![GitHub stars](https://img.shields.io/github/stars/Tarrasch/zsh-bd.svg)](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`
* [zsh-colors ![GitHub stars](https://img.shields.io/github/stars/Tarrasch/zsh-colors.svg)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [zsh-dircolors-solarized ![GitHub stars](https://img.shields.io/github/stars/joel-porquet/zsh-dircolors-solarized.svg)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin.
* [zsh-directory-history ![GitHub stars](https://img.shields.io/github/stars/tymm/zsh-directory-history.svg)](https://github.com/tymm/zsh-directory-history) - A per directory history for zsh.
* [zsh-dwim ![GitHub stars](https://img.shields.io/github/stars/oknowton/zsh-dwim.svg)](https://github.com/oknowton/zsh-dwim) - zsh-dwim attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [zsh-functional ![GitHub stars](https://img.shields.io/github/stars/Tarrasch/zsh-functional.svg)](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [zsh-geeknote ![GitHub stars](https://img.shields.io/github/stars/s7anley/zsh-geeknote.svg)](https://github.com/s7anley/zsh-geeknote) - Geeknote plugin for zsh.
* [zsh-git-sync ![GitHub stars](https://img.shields.io/github/stars/caarlos0/zsh-git-sync.svg)](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync git repositories and clean them up.
* [zsh-grunt-plugin ![GitHub stars](https://img.shields.io/github/stars/clauswitt/zsh-grunt-plugin.svg)](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for grunt.
* [zsh-gvm (horosgrisa) ![GitHub stars](https://img.shields.io/github/stars/horosgrisa/zsh-gvm.svg)](https://github.com/horosgrisa/zsh-gvm) - Go version manager plugin for zsh.
* [zsh-gvm (yerinle) ![GitHub stars](https://img.shields.io/github/stars/yerinle/zsh-gvm.svg)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for gvm (Groovy enVironment Manager)
* [zsh-hints ![GitHub stars](https://img.shields.io/github/stars/joepvd/zsh-hints.svg)](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [zsh-history-substring-search ![GitHub stars](https://img.shields.io/github/stars/zsh-users/zsh-history-substring-search.svg)](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after zsh-syntax-highlighting, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md
* [zsh-konsole-theme-changer ![GitHub stars](https://img.shields.io/github/stars/horosgrisa/zsh-konsole-theme-changer.svg)](https://github.com/horosgrisa/zsh-konsole-theme-changer) - Toggle konsole theme from zsh.
* [zsh-manydots-magic ![GitHub stars](https://img.shields.io/github/stars/knu/zsh-manydots-magic.svg)](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [zsh-nodejs-plugin ![GitHub stars](https://img.shields.io/github/stars/poying/zsh-nodejs-plugin.svg)](https://github.com/poying/zsh-nodejs-plugin) - Po-Ying Chen's Nodejs plugin for zsh.
* [zsh-notify ![GitHub stars](https://img.shields.io/github/stars/marzocchi/zsh-notify.svg)](https://github.com/marzocchi/zsh-notify) - A plugin for the Z shell (on OS X and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [zsh-open-pr ![GitHub stars](https://img.shields.io/github/stars/caarlos0/zsh-open-pr.svg)](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [zsh-osx ![GitHub stars](https://img.shields.io/github/stars/mkwmms/zsh-osx.svg)](https://github.com/mkwmms/zsh-osx) - Add some common OS X related aliases and functions
* [zsh-pg ![GitHub stars](https://img.shields.io/github/stars/caarlos0/zsh-pg.svg)](https://github.com/caarlos0/zsh-pg) utility functions to work with PosgreSQL
* [zsh-plugin-ibtool ![GitHub stars](https://img.shields.io/github/stars/RudthMael/zsh-plugin-ibtool.svg)](https://github.com/RudthMael/zsh-plugin-ibtool) - ibtool shortcuts to generate localized XIB files
* [zsh-plugin-rails ![GitHub stars](https://img.shields.io/github/stars/paraqles/zsh-plugin-rails.svg)](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails
* [zsh-reentry-hook ![GitHub stars](https://img.shields.io/github/stars/RobSis/zsh-reentry-hook.svg)](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
* [zsh-suffix-alias ![GitHub stars](https://img.shields.io/github/stars/srijanshetty/zsh-suffix-alias.svg)](https://github.com/srijanshetty/zsh-suffix-alias): Directly open files in the shell using ZSH's suffix aliases.
* [zsh-syntax-highlighting ![GitHub stars](https://img.shields.io/github/stars/zsh-users/zsh-syntax-highlighting.svg)](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your zsh. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [zsh-t32 ![GitHub stars](https://img.shields.io/github/stars/chrissicool/zsh-t32.svg)](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [zsh-url-highlighter ![GitHub stars](https://img.shields.io/github/stars/ascii-soup/zsh-url-highlighter.svg)](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the zsh syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [zsh-vim-mode ![GitHub stars](https://img.shields.io/github/stars/sharat87/zsh-vim-mode.svg)](https://github.com/sharat87/zsh-vim-mode) - Shrikant Sharat's bindings for zsh's vi mode so it behaves more vim-like
* [zshmarks ![GitHub stars](https://img.shields.io/github/stars/jocelynmallon/zshmarks.svg)](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running zsh with `antigen theme githubuser/repo`. If you're using [zgen](https://github.com/tarjoilija/zgen), add them to your `init.zsh` with `zgen load githubuser/reponame`.

* [af-magic-mod](https://raw.githubusercontent.com/desyncr/zshrc/master/themes/af-magic-mod.zsh-theme) - af-magic-mod theme. Install with `antigen theme desyncr/zshrc themes/af-magic-mod`
* [alpharized ![GitHub stars](https://img.shields.io/github/stars/NicoSantangelo/Alpharized.svg)](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark. It's a modified version of the [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme).
* [angry fly ![GitHub stars](https://img.shields.io/github/stars/russjohnson/angry-fly-zsh.svg)](https://github.com/russjohnson/angry-fly-zsh) - Shows git information in right hand prompt
* [bashi ![GitHub stars](https://img.shields.io/github/stars/eli-oat/bashi.svg)](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal Theme](https://github.com/ahmetsulek/flat-terminal) and Pasquale D'Silva's [Saturn Terminal Theme](https://github.com/psql/saturn-colors).
* [bluelines ![GitHub stars](https://img.shields.io/github/stars/apbarrero/bluelines.svg)](https://github.com/apbarrero/bluelines) - Clear and blue theme
* [bullet-train ![GitHub stars](https://img.shields.io/github/stars/caiogondim/bullet-train-oh-my-zsh-theme.svg)](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme) -  Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [cobalt2 ![GitHub stars](https://img.shields.io/github/stars/wesbos/Cobalt2-iterm.svg)](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2
* [codemachine ![GitHub stars](https://img.shields.io/github/stars/CodeMonkeyMike/ZshTheme-CodeMachine.svg)](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme
* [cute-theme ![GitHub stars](https://img.shields.io/github/stars/dogrocker/oh-my-zsh-powerline-cute-theme.svg)](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - An OSX oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin.
* [docker-compose ![GitHub stars](https://img.shields.io/github/stars/sroze/docker-compose-zsh-plugin.svg)](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt
* [dracula ![GitHub stars](https://img.shields.io/github/stars/zenorocha/dracula-theme.svg)](https://github.com/zenorocha/dracula-theme) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm, Sublime Text, Textmate, Terminal.app, Vim, Xcode, Zsh
* [dropbox](https://github.com/horosgrisa/zsh-dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [excess ![GitHub stars](https://img.shields.io/github/stars/davydovanton/excess.zsh-theme.svg)](https://github.com/davydovanton/excess.zsh-theme) - Simple zsh color theme
* [exercism ![GitHub stars](https://img.shields.io/github/stars/fabiokiatkowski/exercism.plugin.zsh.svg)](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/)
* [frisk-red ![GitHub stars](https://img.shields.io/github/stars/aishsingh/zsh.svg)](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the frisk theme from oh-my-zsh
* [furio ![GitHub stars](https://img.shields.io/github/stars/hectorpalmatellez/furio-theme.svg)](https://github.com/hectorpalmatellez/furio-theme) - Fork of the Cloud oh-my-zsh theme. with different colors and emojis
* [gawaine ![GitHub stars](https://img.shields.io/github/stars/nicolaracco/gawaine.zsh-theme.svg)](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires rvm & git plugins.
* [gitsome ![GitHub stars](https://img.shields.io/github/stars/mtully/gitsome.svg)](https://github.com/mtully/gitsome) - Super simple prompt with git info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a git repo, it shows the location from the git's root folder. When not in a git repo, it shows the path relative to home, `~`.
* [glimmer ![GitHub stars](https://img.shields.io/github/stars/martnu/glimmer.svg)](https://github.com/martnu/glimmer) - Includes git branch, time and user@host
* [hackersaurus ![GitHub stars](https://img.shields.io/github/stars/bhilburn/hackersaurus.svg)](https://github.com/bhilburn/hackersaurus) - theme with git status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k)
* [intheloop-powerline ![GitHub stars](https://img.shields.io/github/stars/zyphrus/intheloop-powerline.svg)](https://github.com/zyphrus/intheloop-powerline) - An extension of the intheloop theme to use powerline fonts
* [itg ![GitHub stars](https://img.shields.io/github/stars/itsthatguy/itg.zsh-theme.svg)](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme
* [jcl-zsh-theme ![GitHub stars](https://img.shields.io/github/stars/jasonlewis/jcl-zsh-theme.svg)](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme
* [judgedim ![GitHub stars](https://img.shields.io/github/stars/judgedim/oh-my-zsh-judgedim-theme.svg)](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [kketcham ![GitHub stars](https://img.shields.io/github/stars/prototype27/kketcham.svg)](https://github.com/prototype27/kketcham) - Theme with nifty colors on the git info
* [liquidprompt ![GitHub stars](https://img.shields.io/github/stars/nojhan/liquidprompt.svg)](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & ZSH
* [maxulysse/myzsh ![GitHub stars](https://img.shields.io/github/stars/MaxUlysse/myzsh.svg)](https://github.com/MaxUlysse/myzsh) Maxime Garcia's myzsh theme.
* [megaprompt ![GitHub stars](https://img.shields.io/github/stars/willghatch/zsh-megaprompt.svg)](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character.  Requires the [hooks](https://github.com/willghatch/zsh-hooks) plugin.
* [mindful-space ![GitHub stars](https://img.shields.io/github/stars/syndbg/mindful-space-zsh-theme.svg)](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind
* [minimal ![GitHub stars](https://img.shields.io/github/stars/S1cK94/minimal.svg)](https://github.com/S1cK94/minimal) - S1ck94's minimal theme
* [misa ![GitHub stars](https://img.shields.io/github/stars/S1cK94/minimal.svg)](https://github.com/misalabs/misa.zsh-theme) - misalabs' zsh theme
* [nanofish ![GitHub stars](https://img.shields.io/github/stars/tweekmonster/nanofish.svg)](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme
* [ningxia ![GitHub stars](https://img.shields.io/github/stars/wangyandong-ningxia/ningxia.zsh-theme.svg)](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic
* [oh-my-git ![GitHub stars](https://img.shields.io/github/stars/arialdomartini/oh-my-git.svg)](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and zsh
* [oh-my-zsh-robbl ![GitHub stars](https://img.shields.io/github/stars/robbl/oh-my-zsh-config.svg)](https://github.com/robbl/oh-my-zsh-config) - shows git/svn status including time since last commit, rvm status in prompt.
* [pad ![GitHub stars](https://img.shields.io/github/stars/eproxus/pad.zsh-theme.svg)](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme
* [platypus ![GitHub stars](https://img.shields.io/github/stars/fdv/platypus.svg)](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for Oh My ZSH used by Frédéric de Villamil.
* [powerlevel9k ![GitHub stars](https://img.shields.io/github/stars/bhilburn/powerlevel9k.svg)](https://github.com/bhilburn/powerlevel9k) - A very flexible theme based on the well-known agnoster-theme with support for various VCS, AWS, rbenv, virtualenv, etc.
* [powerline-cute ![GitHub stars](https://img.shields.io/github/stars/dogrocker/oh-my-zsh-powerline-cute-theme.svg)](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme)
* [prezto-cloud-prompt ![GitHub stars](https://img.shields.io/github/stars/klaude/prezto-cloud-prompt.svg)](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt
* [prezto_powerline ![GitHub stars](https://img.shields.io/github/stars/davidjrice/prezto_powerline.svg)](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [pure ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/pure.svg)](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt.
* [racotecnic ![GitHub stars](https://img.shields.io/github/stars/elboletaire/zsh-theme-racotecnic.svg)](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git
* [rummik/zsh-theme ![GitHub stars](https://img.shields.io/github/stars/rummik/zsh-theme.svg)](https://github.com/rummik/zsh-theme) Rummik's theme
* [seeker ![GitHub stars](https://img.shields.io/github/stars/tonyseek/oh-my-zsh-seeker-theme.svg)](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts
* [skeletor-syntax ![GitHub stars](https://img.shields.io/github/stars/ramonmcros/skeletor-syntax.svg)](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and Zsh inspired by Skeletor from He-Man and the Masters of the Universe
* [smiley ![GitHub stars](https://img.shields.io/github/stars/gsamokovarov/smiley.zsh-theme.svg)](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces
* [solarizsh ![GitHub stars](https://img.shields.io/github/stars/paddykontschak/Solarizsh.svg)](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [Solarized](http://ethanschoonover.com/solarized)
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by agnoster, tmux powerline, vim powerline and the vim status plugin.
* [sugarfree ![GitHub stars](https://img.shields.io/github/stars/cbrock/sugar-free.svg)](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/master/themes/candy.zsh-theme) themes
* [the-time-lord ![GitHub stars](https://img.shields.io/github/stars/jhwhite/the-time-lord.svg)](https://github.com/jhwhite/the-time-lord) - Based on gallifrey
* [tvline ![GitHub stars](https://img.shields.io/github/stars/thvitt/tvline.svg)](https://github.com/thvitt/tvline) - Derived from [agnoster's theme](https://gist.github.com/3712874), adds powerline font enhancements.
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows Current commit shorten hash and message.
* [vinhnx ![GitHub stars](https://img.shields.io/github/stars/vinhnx/vinhnx.zsh-theme.svg)](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with Solarized color scheme.
* [wild-cherry ![GitHub stars](https://img.shields.io/github/stars/mashaal/wild-cherry.svg)](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for Zsh, iTerm, Sublime, Atom, & Mou
* [zemm-blinks ![GitHub stars](https://img.shields.io/github/stars/aranasaurus/zemm-blinks.zsh-theme.svg)](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh blinks with mercurial support and other changes
* [zero ![GitHub stars](https://img.shields.io/github/stars/arlimus/zero.zsh.svg)](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin
* [zsh-prompt-iggy ![GitHub stars](https://img.shields.io/github/stars/eugenk/zsh-prompt-iggy.svg)](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, Git-aware **prezto only** theme
* [zsh-prompt-powerline ![GitHub stars](https://img.shields.io/github/stars/Valodim/zsh-prompt-powerline.svg)](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight zsh prompt, based on the powerline font from the popular eponymous vim plugin, which works well for a dark background.
* [zsh2000 ![GitHub stars](https://img.shields.io/github/stars/maverick2000/zsh2000.svg)](https://github.com/maverick2000/zsh2000) - Powerline looking ZSH theme with rvm prompt, git status and branch, current time, user, hostname, pwd, exit status, root and background job status.

### Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts ![GitHub stars](https://img.shields.io/github/stars/gabrielelana/awesome-terminal-fonts.svg)](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
* [Fantasque Awesome Font ![GitHub stars](https://img.shields.io/github/stars/ztomer/fantasque_awesome_powerline.svg)](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans ![GitHub stars](https://img.shields.io/github/stars/belluzj/fantasque-sans.svg)](https://github.com/belluzj/fantasque-sans) - Another powerline font
* [Hack](http://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](http://input.fontbureau.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Monoid](http://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Powerline patched font collection ![GitHub stars](https://img.shields.io/github/stars/powerline/fonts.svg)](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.

## Even more completions

These plugins add tab completion without adding extra functions or aliases.

* [autopkg-zsh-completion ![GitHub stars](https://img.shields.io/github/stars/fuzzylogiq/autopkg-zsh-completion.svg)](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg
* [berkshelf-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/berkshelf/berkshelf-zsh-plugin.svg)](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf
* [bosh-zsh-autocompletion ![GitHub stars](https://img.shields.io/github/stars/krujos/bosh-zsh-autocompletion.svg)](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion
* [brew-services ![GitHub stars](https://img.shields.io/github/stars/vasyharan/zsh-brew-services.svg)](https://github.com/vasyharan/zsh-brew-services) - completion plugin for homebrew services
* [cabal ![GitHub stars](https://img.shields.io/github/stars/d12frosted/cabal.plugin.zsh.svg)](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal
* [codeception-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/shengyou/codeception-zsh-plugin.svg)](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework
* [codemachine ![GitHub stars](https://img.shields.io/github/stars/CodeMonkeyMike/ZshTheme-CodeMachine.svg)](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via ssh, return code of last command
* [dbic ![GitHub stars](https://img.shields.io/github/stars/.svg)](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer
* [docker-enter-completion ![GitHub stars](https://img.shields.io/github/stars/lejeunerenard/dbic-migration-env.svg)](https://github.com/runcom/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter)
* [docker-helpers ![GitHub stars](https://img.shields.io/github/stars/unixorn/docker-helpers.zshplugin.svg)](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts
* [docker-zsh-completion ![GitHub stars](https://img.shields.io/github/stars/felixr/docker-zsh-completion.svg)](https://github.com/felixr/docker-zsh-completion) - Add completions for docker
* [docker-zsh ![GitHub stars](https://img.shields.io/github/stars/adrien-f/docker-zsh.svg)](https://github.com/adrien-f/docker-zsh) - Adds tab completion for docker
* [drush_zsh_completion ![GitHub stars](https://img.shields.io/github/stars/webflo/drush_zsh_completion.svg)](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for zsh
* [etcdctl-zsh ![GitHub stars](https://img.shields.io/github/stars/sheax0r/etcdctl-zsh.svg)](https://github.com/sheax0r/etcdctl-zsh) - etcdctl autocomplete plugin for oh-my-zsh
* [git-flow-completion ![GitHub stars](https://img.shields.io/github/stars/bobthecow/git-flow-completion.svg)](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for git-flow
* [grid5000-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/pmorillon/grid5000-zsh-plugin.svg)](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions
* [gulp-autocompletion-zsh ![GitHub stars](https://img.shields.io/github/stars/srijanshetty/gulp-autocompletion-zsh.svg)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - gulp autocompletion
* [gulp ![GitHub stars](https://img.shields.io/github/stars/akoenig/gulp.plugin.zsh.svg)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (zsh).
* [jumpstorm-zsh-plugin ![GitHub stars](https://img.shields.io/github/stars/netresearch/jumpstorm-zsh-plugin.svg)](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm)
* [npm-run.plugin.zsh ![GitHub stars](https://img.shields.io/github/stars/akoenig/npm-run.plugin.zsh.svg)](https://github.com/akoenig/npm-run.plugin.zsh) - `npm run` autocompletion
* [nvm-completion ![GitHub stars](https://img.shields.io/github/stars/tomsquest/nvm-completion.zsh.svg)](https://github.com/tomsquest/nvm-completion.zsh) - Updated nvm completions
* [oh-my-zsh-nova ![GitHub stars](https://img.shields.io/github/stars/rbirnie/oh-my-zsh-nova.svg)](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for the nova so you don't need to remember all those pesky arguments
* [oh-my-zsh-plugin-nvm ![GitHub stars](https://img.shields.io/github/stars/olesu/oh-my-zsh-plugin-nvm.svg)](https://github.com/olesu/oh-my-zsh-plugin-nvm) - Ole Sunde's nvm plugin for zsh
* [oh-my-zsh_razor_plugin ![GitHub stars](https://img.shields.io/github/stars/dalang/oh-my-zsh_razor_plugin.svg)](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor](https://github.com/puppetlabs/Razor)
* [rake-completion.zshplugin ![GitHub stars](https://img.shields.io/github/stars/unixorn/rake-completion.zshplugin.svg)](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets
* [tugboat ![GitHub stars](https://img.shields.io/github/stars/DimitriSteyaert/Zsh-tugboat.svg)](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/pearkes/tugboat/) command
* [umake ![GitHub stars](https://img.shields.io/github/stars/zlsun/umake.svg)](https://github.com/zlsun/umake) - tab completion for umake
* [zsh-cabal-completion ![GitHub stars](https://img.shields.io/github/stars/ehamberg/zsh-cabal-completion.svg)](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal
* [zsh-completion-generator ![GitHub stars](https://img.shields.io/github/stars/RobSis/zsh-completion-generator.svg)](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically.
* [zsh-completions ![GitHub stars](https://img.shields.io/github/stars/zsh-users/zsh-completions.svg)](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
* [zsh-pandoc-completion ![GitHub stars](https://img.shields.io/github/stars/srijanshetty/zsh-pandoc-completion.svg)](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin
* [zsh-pip-completion ![GitHub stars](https://img.shields.io/github/stars/srijanshetty/zsh-pip-completion.svg)](https://github.com/srijanshetty/zsh-pip-completion) - pip autocomplete plugin

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
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Most of these plugins can be installed by adding `zgen load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgen load` calls in.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### Other lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) - A curated list of awesome open source sysadmin resources

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [Zsh Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](http://grml.org/zsh/zsh-lovers.html) are indispensable.
