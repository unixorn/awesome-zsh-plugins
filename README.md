# awesome-zsh-plugins

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![CircleCI](https://circleci.com/gh/unixorn/awesome-zsh-plugins.svg?style=shield)](https://circleci.com/gh/unixorn/awesome-zsh-plugins)
[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/gpa.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![Issue Count](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/master.svg)](https://github.com/unixorn/awesome-zsh-plugins)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Frameworks](#frameworks)
  - [alf](#alf)
  - [ansible-role-zsh](#ansible-role-zsh)
  - [ant-zsh](#ant-zsh)
  - [antibody](#antibody)
  - [antigen-hs](#antigen-hs)
  - [antigen](#antigen)
  - [ax-zsh](#ax-zsh)
  - [dotzsh](#dotzsh)
  - [fresh](#fresh)
  - [oh-my-zsh](#oh-my-zsh)
  - [prezto](#prezto)
  - [pumice](#pumice)
  - [Sheldon](#sheldon)
  - [Toasty](#toasty)
  - [zapack](#zapack)
  - [zeesh](#zeesh)
  - [zgem](#zgem)
  - [zgen](#zgen)
  - [zilsh](#zilsh)
  - [zim](#zim)
  - [zit](#zit)
  - [zoppo](#zoppo)
  - [zpacker](#zpacker)
  - [zplug](#zplug)
  - [zplugin](#zplugin)
  - [ZPM](#zpm)
  - [ZR](#zr)
  - [zshing](#zshing)
  - [ztanesh](#ztanesh)
  - [zulu](#zulu)
- [Tutorials](#tutorials)
  - [Generic ZSH](#generic-zsh)
  - [Antigen](#antigen)
  - [Oh-My-Zsh](#oh-my-zsh)
  - [Prezto](#prezto)
  - [Zgen](#zgen)
- [Plugins](#plugins)
- [Completions](#completions)
- [Themes](#themes)
  - [Fonts](#fonts)
- [Installation](#installation)
  - [Antibody](#antibody)
  - [Antigen](#antigen-1)
  - [dotzsh](#dotzsh-1)
  - [Oh-My-Zsh](#oh-my-zsh-1)
  - [Prezto](#prezto-1)
  - [Zgen](#zgen-1)
  - [zplug](#zplug-1)
- [Writing New Plugins](#writing-new-plugins)
- [Other Resources](#other-resources)
  - [ZSH Tools](#zsh-tools)
  - [Other Useful Lists](#other-useful-lists)
  - [Other References](#other-references)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](Contributing.md) before contributing.*

## Frameworks

These frameworks make customizing your ZSH setup easier.

### [alf](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after Prezto and Antigen while utilizing Oh-My-Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses antigen to manage bundles and oh-my-zsh. Can load bundles conditionally. By default it includes powerlevel9k theme, autosuggestions, syntax-highlighting and fzf-widgets. Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** A faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for antigen optimized for a low overhead when starting up the shell. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

### [dotzsh](https://github.com/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [oh-my-zsh](https://ohmyz.sh/)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, git, macOS, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [prezto](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [Sheldon](https://github.com/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

* Can manage
  * Remote Git repositories.
  * GitHub repositories.
  * Local plugins.
  * Gist files (planned).
  * Arbitrary binary downloads (planned).
* Configuration file using [TOML] syntax.
* Uses a lock file for much faster loading of plugins.
* Highly configurable install methods using handlebars templating.
* Branch/tag/commit support (planned).
* Downloads plugins in parallel (planned).

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack is a basic fast minimal ZSH plugin loader.

### [zeesh](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen)

**Zgen** is a lightweight plugin manager for ZSH inspired by Antigen. The goal is to have a minimal overhead when starting up the shell because nobody likes waiting. The script generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`. This saves startup time by not having to execute time consuming logic (plugin checking, updates, etc). The downside is that you have to refresh the init script manually with `zgen reset` whenever you update your `.zshrc`. Can load [oh-my-zsh](http://ohmyz.sh/)-compatible plugins and themes, and will automagically clone them for you when you add them to your plugin list.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [zit](https://github.com/m45t3r/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from Git repositories (and Git repositories only, them why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, PATH manipulation and others.

### [zoppo](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- Can manage everything
  - Zsh plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - Gist files ([gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- Super-fast parallel installation/update
- Support for lazy-loading
- Branch/tag/commit support
- Post-update, post-load hooks
- Dependencies between packages
- Unlike [antigen](https://github.com/zsh-users/antigen), no ZSH plugin file (`*.plugin.zsh`) required
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw), and so on)
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zplugin](https://github.com/zdharma/zplugin)

**Zplugin** is an innovative plugin manager with [semigraphical UI](https://github.com/zdharma/zplugin-crasis), [Turbo Mode](https://github.com/zdharma/zplugin#turbo-mode), a clean fpath, reports, completion management and [services](https://github.com/zservices) support.

### [ZPM](https://github.com/zpm-zsh/zpm)

**ZPM** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) similar to vim-plug. ZPM plugins are compatible with [oh-my-zsh](http://ohmyz.sh/). ZPM runs on Linux, macOS, FreeBSD and Android.

### [ZR](https://github.com/jedahan/zr)

**ZR** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* keep track of and configure your plugins right in the `.zshrc`
* Install Zsh plugins
* Update Zsh plugins
* Search by name all available Zsh Plugins
* Clean unused plugins up
* run the above actions in a *single command*
* manages the __Source Plugins__ of your installed Plugins

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5+, which aims to make it easy to manage your shell without writing any code.

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Tutorial using a combination of [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
* [https://commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh) - Arch Linux's ZSH introduction. Not Arch or Linux-specific.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) - Seth Brown's tutorial on combining ZSH, [tmux](https://tmux.github.io) and vim.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.

### Antigen

* [https://mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

* [ZSH Gem 24](https://www.refining-linux.org/archives/59/ZSH-Gem-24-ZSH-frameworks/) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) - Linh M. Tran's post about transitioning to Prezto from Oh-My-Zsh.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell, using [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto), and [Zgen](https://github.com/tarjoilija/zgen).
* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with [zgen](https://github.com/tarjoilija/zgen). This includes a curated collection of plugins, and will automatically configure ZSH to use [zgen](https://github.com/tarjoilija/zgen) to load them, configures [zgen](https://github.com/tarjoilija/zgen) to periodically automatically update itself, the plugins, and the quickstart kit itself.

## Plugins

* [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to Vim's abbreviation expansion.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for accurev.
* [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) scripts from your command line. Includes tab completions.
* [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with antigen.
* [almostontop](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by alwaysontop plugin for `bash`.
* [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for Ansible.
* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with Git rebasing.
* [antigen-git-store](https://github.com/smallhadroncollider-deprecated/antigen-git-store) - Antigen/ZSH script to store `git`'s current working directory. For working with `git` between two computers without forcing arbitrary commits.
* [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
* [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - A plugin for Oh My Zsh that lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com). It's based on the Sublime plugin. Only supports macOS.
* [atom](https://github.com/kingsj/atom_plugin.zsh) - A plugin for the Atom editor on macOS.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) plugin.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you `cd` into it.
* [autojump](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs when traversing directories.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh doesn't autoupdate non-core plugins, this adds plugin autoupdating to omz.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - plugin for AWS CLI MFA based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa).
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - Plugin for AWS MFA.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
* [aws-vault](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault](https://github.com/99designs/aws-vault).
* [base16](https://github.com/chriskempson/base16-shell) - Adds script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
* [basex](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - Get random quote from Bash.im.
* [bash](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
* [bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH vi-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - Add more command aliases for `brew`
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
* [blackbox](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a `git` repository.
* [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](https://caniuse.com) support to ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - A wrapper for `rm` that adds trash/recycling and useful warnings
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to `cd` to the google-repo repository root directory.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
* [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [cdc](https://github.com/evanthegrayt/cdc) - Shell function for changing directory to frequently-used places.
* [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for ZSH.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard.
* [cmd-architect](https://github.com/psprint/zsh-cmd-architect) - Build commands from what's in history and at prompt, move, delete, add command segments and search history with multi-word queries.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [robbyrussell/oh-my-zsh/plugins/colored-man-pages](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - Colorize `man` pages.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Colorize output of various programs.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of omz.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
* [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price.
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [diff-so-fancy](https://github.com/zdharma/zsh-diff-so-fancy) - Simplify installing the `diff-so-fancy` project into your user account.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [dircolors-solarized](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin.
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH.
* [dirrc](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - Keep your dotfines in sync across multiple machines using `git`.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - If you have a `.pyvenv` virtualenv, will automagically switches to it.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin.
* [dwim](https://github.com/oknowton/zsh-dwim) - zsh-dwim attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/psprint/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history _word_ completion).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ascii art emojis to your environment in convenient variables.
* [enhancd](https://github.com/b4b4r07/enhancd) - A simple tool that provides enhanced `cd` command.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`".
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [explain-shell](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding exit code for each command in the history.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of OMZ.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips) - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips](https://github.com/djui/alias-tips)
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - Optimized an improved `zsh-users/zsh-syntax-highlighting` – better response times, `zed/vared` can edit `10 kB` functions.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
* [firebase](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` taking advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [fz](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among your historical directories.
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat). Searches in the local tree of subdirectories for files.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [fzf-mpd](https://github.com/anders-dc/fzf-mpd/) - A ZSH plugin that allows you to control [mpd](https://www.musicpd.org/) using [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line.
* [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations.
* [gcloud-project](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Project.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - Geeknote plugin for ZSH.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - Geometry plugin to display the current folder's npm package version.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from [code.jquery.com](code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use zeus with normal rails commands.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your `git` fork.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of OMZ.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
* [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. `fzf`, completion, preview integrated.
* [git-it-on.zsh](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
* [git-secret](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a `git` repository.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds git commands to make some common `git` usages more efficient.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
* [gitcd](https://github.com/viko16/gitcd.plugin.zsh) - cd to a git working directory after cloning it.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo](https://github.com/ltj/gitgo) - Open a Github/Gitlab repository in your browser from the command line (macOS only).
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
* [gitsync](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
* [goenv](https://github.com/bbenne10/goenv) - Antigen plugin to manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt/decrypt files or directories in place.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for `grunt`.
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - gvm (Go version manager) plugin for ZSH.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for `gvm` (Groovy enVironment Manager).
* [hab](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - Adds some convenience aliases for hadoop functions.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) projects.
* [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
* [history-search-multi-word](https://github.com/zdharma/history-search-multi-word) - syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after zsh-syntax-highlighting, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [history-sync](https://github.com/wulfgarpro/history-sync) - An Oh My Zsh plugin for GPG encrypted, Internet synchronized ZSH history using `git`.
* [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
* [hooks](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
* [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
* [ing](https://github.com/rummik/zsh-ing) - `ping`, but shorter output.
* [intellij](https://github.com/mgryszko/intellij) - Extract intellij bookmarks into markdown format.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
* [iosctl](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator.
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
* [jabba](https://github.com/2m/zsh-jabba) - Adds shell integration code and completions for the [jabba](https://github.com/shyiko/jabba) Java version manager.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
* [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - macOS-only plugin for switching between jdk versions.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of jEnv.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRAs from the command line.
* [jvm](https://github.com/mgryszko/jvm) - Allows selection of JDK on macOS.
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with git features.
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for kubectl that adds current context and namespace.
* [kubectl-zsh-plugin](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing kubectl.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - Add kubernetes helper functions and aliases.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)'s workspace.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of OMZ.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - Replacement `git` plugin for Oh-My-Zsh-compatible frameworks.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for Oh-My-Zsh.
* [linuxbrew](https://github.com/zpm-zsh/linuxbrew) - ZSH plugin for [linuxbrew](http://linuxbrew.sh/).
* [listbox](https://github.com/gko/listbox) - Listbox element for shell.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for Sublime Text projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets data from [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts.
* [lux](https://github.com/pndurette/zsh-lux) - ZSH plugin to toggle the light & dark modes of macOS and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with Munki.
* [macos](https://github.com/joow/macos) - A ZSH plugin for macOS.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - Adds `m2` function to run magento binary, adds tab completions.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - Mark Files and Edit them With Autocompletion for existing Marks.
* [markgate](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - Extracted from oh-my-zsh so you can use it without oh-my-zsh.
* [mfunc](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and vi mode.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
* [morpho](https://github.com/psprint/zsh-morpho) - Terminal screen savers written in pure ZSH, and also screen saver framework.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit handler plugin for starting handler easily.
* [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Colors for mysql tables.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
* [navigation-tools](https://github.com/psprint/zsh-navigation-tools) - Adds `htop`-like `kill`, directory bookmarks browser, multi-word incremental history searcher and more.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - Maps exit status code to human readable string.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default `nix-shell` shell.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
* [nodenv](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
* [nohup](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - Inspired by [terminal_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH.
* [notify](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [nvm-auto](https://github.com/dijitalmunky/nvm-auto) - Aims to alleviate needing to type `nvm use` as much as possible, especially if you often switch between versions of node.js and use `.nvmrc` files in your project to manage what version of node your project needs.
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
* [operator](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with Menlo for Powerline.
* [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on my macOS install.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - Keeps passwords from entering your command line history.
* [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing ctrl+R.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with PosgreSQL.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - Auto-load [phpenv](https://github.com/sptndc/phpenv) and its completions.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct virtualenvs so they don't conflict with any other python requirements on your system.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
* [plugin](https://github.com/darrenbutcher/plugin) - Creates custom oh-my-zsh plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
* [pretty-time](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [profile-secrets](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
* [project (gko)](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository).
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Aliases to manage proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - Configure your proxy settings.
* [pure-agnoster](https://github.com/yourfin/pure-agnoster) - Mashup of pure and aganoster. Has `git` decorations and works well with both dark and light terminal backgrounds.
* [purs](https://github.com/xcambar/purs) - A [Pure](https://github.com/sindresorhus/pure)-inspired prompt in [Rust](https://www.rust-lang.org/).
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load pyenv. The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
* [q (cal2195)](https://github.com/cal2195/q) - Vim-like macro registers for your ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
* [randeme](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - change the colour of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires OpenRazer linux drivers.
* [rbenv (ELLIOTTCABLE)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the rbenv plugin from oh-my-zsh.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original oh-my-zsh rbenv plugin.
* [redis](https://github.com/zservices/redis) - Will run `redis-server` pointing it to the `redis.conf` configuration file. This can be used with the [zdharma/zredis](https://github.com/zdharma/zredis) plugin to share variables between shells.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
* [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
* [ripz](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo-zsh-plugin](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://robo.li/).
* [rockz](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
* [ruby-switch](https://github.com/LockonS/ruby-switch) - Switch ruby versions and manage the PATH variable at the same time.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
* [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [select](https://github.com/psprint/zsh-select) - Multi-term searched selection list with approximate matching and uniq mode.
* [send.zsh](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
* [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python SimpleHTTPServer and SimpleHTTPSServer.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in terminal.
* [ssh-connect](https://github.com/gko/ssh-connect) - A simple `ssh` manager.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
* [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sublime](https://github.com/valentinocossar/sublime) - Same as the official Sublime plugin for Oh My Zsh, but this opens files in the current Sublime window, if there is one already open.
* [sudo](https://github.com/hcgraf/zsh-sudo) - The `sudo` plugin from oh-my-zsh, extracted to a standalone. Toggles `sudo` before the current/previous command by pressing *ESC-ESC* in emacs-mode or vi-command mode.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - Directly open files in the shell using ZSH's suffix aliases.
* [symfony](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for Symfony 2 and 3.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgits without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for vi emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new El Capitan Terminal.app features.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
* [terraform](https://github.com/pbar1/zsh-terraform) - Terraform convenience functions and aliases for ZSH.
* [timewarrior](https://github.com/svenXY/timewarrior) - Plugin for [timewarrior](https://timewarrior.net/) a timetracking application.
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
* [tmux-fork](https://github.com/sharktamer/zsh-tmux) Standalone fork of the oh-my-zsh tmux plugin
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) with ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent `tmux` pane.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [tmux](https://github.com/zpm-zsh/tmux) - Plugin for [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L tmux session.
* [travis](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists.
* [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
* [up.zsh](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original oh-my-zsh venv module
* [vanilli.sh](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
* [velocity](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) (though you don't *have* to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
* [vi-mode (Nyquase)](https://github.com/Nyquase/vi-mode) Add extra `vi`-like functionality.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - Add more `vi`-like functionality to ZSH.
* [viexchange](https://github.com/okapia/zsh-viexchange) - Vi mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly Vi-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - View vim plugin manuals (help) like man in ZSH.
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH vim mode (bindkey -v) plugin.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv ZSH plugin for oh-my-zsh.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. It adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - Custom plugin for faster navigation.
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode](https://github.com/qianxinfeng/zsh-vscode) - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
* [wack](https://github.com/leoxlin/wack) - Wraps `ack` command.
* [wakatime-zsh-plugin](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
* [wakatime](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc](https://github.com/garabik/grc).
* [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for the [watson](https://github.com/TailorDev/Watson) time management system.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's pip environment if `pipenv` detects the presence of one.
* [yeoman-zsh-plugin](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
* [youtube-dl](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/)
* [z.lua](https://github.com/skywind3000/z.lua) - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh](https://github.com/rupa/z) with windows and posix shells support and various improvements.
* [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
* [zce](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for ZSH.
* [zconvey](https://github.com/zdharma/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active Z shell sessions, for example.
* [zed](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z](https://github.com/rupa/z) to install it via a ZSH plugin.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zgdbm](https://github.com/zdharma/zgdbm) - Adds GDBM as a plugin.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make compinit run only once after all loading is done by [zgen](https://github.com/tarjoilija/zgen).
* [zhooks](https://github.com/agkozak/zhooks) - Displays the contents of any ZSH hook arrays and the code of any hook functions that have been defined. Useful for debugging.
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for zimfw, packaged into a zimfw plugin.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes.
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [zredis](https://github.com/zdharma/zredis) - Adds Redis database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
* [zsh-z](https://github.com/agkozak/zsh-z) - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
* [zsnapshot](https://github.com/psprint/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [Ztrace](https://github.com/psprint/ztrace) - Catches output of commands, allows to reuse that output, glue it with history content.
* [ZUI](https://github.com/zdharma/zui/) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for viasite-ansible/ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - This plugin provides completion for [Antibody](https://github.com/getantibody/antibody) plugin manager.
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg.
* [aws_manager_plugin](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the aws_manager CLI.
* [berkshelf-zsh-plugin](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services.
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carthage](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete-plugin](https://github.com/Dannyzen/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
* [codeception-zsh-plugin](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via `ssh`, return code of last command.
* [completions](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop](https://github.com/bcicen/ctop).
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter).
* [docker-zsh-completion](https://github.com/felixr/docker-zsh-completion) - Add completions for docker.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell).
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](https://exercism.io/).
* [extract](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
* [fly-zsh-autocomplete-plugin](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) commands.
* [gcloud-zsh-completion](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - providing ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [git-annex-completion](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands.
* [git-flow-completion](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for git-flow.
* [gradle-completion (eriwen)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
* [grid5000-zsh-plugin](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
* [gulp-autocompletion](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
* [gulp](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [ipfs](https://github.com/aramboi/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe-completion](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) gitignore editor.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm)
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line).
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [MooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
* [nix-zsh-completions](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - Autocompletion support for `npm run`.
* [packer](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [parallels-zsh-plugin](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) command completion for ZSH.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - Completions for `pipenv`.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - Adds completions for Pivotal's [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
* [razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor](https://github.com/puppetlabs/Razor).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Tab completions for Rustup.
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - autocomplete plugin for sfdx.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
* [ssh](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - Add completions for surf.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://kitchen.ci/).
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) command.
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) command.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - Yarn autocompletions.

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. If you're using [zgen](https://github.com/tarjoilija/zgen), add them to your `init.zsh` with `zgen load githubuser/reponame`.

* [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abbr](https://github.com/PhilsLab/abbr-zsh-theme) - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
* [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with git status, node version and the exit code from the last command.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-mod](https://raw.githubusercontent.com/desyncr/zshrc/master/themes/af-magic-mod.zsh-theme) - af-magic-mod theme.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run on your shell.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - Based on [agnoster theme](https://gist.github.com/3712874) included in [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt). Shows detailed information about `git` status.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) - Uses three asynchronous methods to keep the ZSH prompt swift while displaying the Git status and indicators of SSH connection, exit codes, and vi mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with git information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) terminal.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes git status.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
* [Agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires Powerline-compatible font.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster Theme](https://gist.github.com/agnoster/3712874) and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, git status, current directory and user & host information.
* [akzsh](https://github.com/awkimball/akzsh) - Works best with a dark terminal theme, includes `git` decorations.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with git status displayed.
* [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized dark](https://github.com/altercation/solarized) terminals. It's a modified version of the [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows git information in the right hand prompt.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, git branch if exists. Looks great both with dark and white terminals.
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired Zsh theme. Based on [norm](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/norm.zsh-theme)
* [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - Based on [theunraveler](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#theunraveler).
* [astral](https://github.com/alphabetum/astral) - Theme for dark backgrounds with zen mode.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - Based on [`ys`](http://blog.ysmood.org/my-ys-terminal-theme/) theme and `robbyrussell` (default theme) theme.
* [aterminal](https://github.com/guiferpa/aterminal) - Displays Nodejs, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
* [avit-mod](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) theme.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal Theme](https://github.com/ahmetsulek/flat-terminal) and Pasquale D'Silva's [Saturn Terminal Theme](https://github.com/psql/saturn-colors).
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [`gitster`](https://github.com/zimfw/zimfw/blob/master/modules/prompt/themes/gitster.zsh-theme) theme for [ZIM](https://github.com/zimfw/zimfw#installation).
* [bearable](https://github.com/JanmanX/bearable-zsh) - Works well with dark terminal backgrounds.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme), but with beer icons.
* [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [birame](https://github.com/maniat1k/birame) - Based on [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme).
* [bklyn](https://github.com/gporrata/bklyn-zsh) - Variant of [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - Another git-aware theme.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - Based on the existing theme [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme).
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
* [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information.
* [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
* [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - Displays the current song in the prompt with `audtool`.
* [brunty](https://github.com/Brunty/omz-brunty) - Brunty theme.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme) - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) dark terminal theme.
* [cherry](https://github.com/feddamisch/zsh-theme-cherry) - Cool theme with `git` status decorations in the right prompt.
* [chi](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS.
* [ciacho](https://github.com/Ciacho/ciacho-ohmyzsh-theme) - Based on Agnoster.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
* [clarity](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
* [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme.
* [clean (BrandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
* [clover](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta-zsh-theme](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for [cmder](http://cmder.net/) configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - Inspired by [bashi](https://github.com/eli-oat/bashi), includes a monkey and `git` information in your prompt.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - Brightly colored theme optimized for dark backgrounds.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - A macOS oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and the [agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) in a container.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - Informative, minimal, and, above all, X-Men themed.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Darksoku theme is based on the [ys](http://blog.ysmood.org/my-ys-terminal-theme/) and [astro](https://github.com/iplaces/astro-zsh-theme) themes.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt.
* [delta](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom LSCOLORS and LS_COLORS settings files, works with both dark and light terminal themes.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - Variant of [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) without hostname or time.
* [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dracula](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
* [dragon](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
* [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
* [elessar](https://github.com/fjpalacios/elessar-theme) - A `git`-aware theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme). Requires a Powerline-compatible font.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](robbyrussell/oh-my-zsh) theme.
* [endless-dog](https://github.com/qwelyt/endless-dog) - OMZ theme that mimics grml-zsh-config.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal.
* [eriner](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired agnoster prompt theme. Includes `git` status decorations.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
* [fishy](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy).
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - Fork of [terminal-party](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/terminalparty.zsh-theme) theme.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
* [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - A colorful two-line theme with support for `git` and `svn`.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - Breaks out oh-my-zsh gentoo theme to a separate repo for non-omz users.
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme based on Avit and Pure that displays a lot of `git` information and is composable and customizable.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) theme.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
* [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH, includes `git` decorations, user@host, path and date.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - Simple yet informative theme that includes `git` decorations.
* [gruvbox](https://github.com/sbugzu/gruvbox-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guri](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure)'s design.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [haribo](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt.
* [hcompact](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
* [heart](https://github.com/gko/heart-theme) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old bash theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hfulldate](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
* [himself](https://github.com/mwamodojnr/himself) - Optimized for people using `git`, [solarized](https://github.com/altercation/solarized) terminals and unicode-compatible fonts.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
* [horizontal](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
* [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - Shows current directory, customizable delimiter, current branch, `git` status.
* [imp](https://github.com/igormp/Imp) - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [jbrain4](https://github.com/jbrain4/jbrain4-zsh-theme) - Variant of oh-my-zsh's stock bira theme.
* [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme.
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status.
* [jovial](https://github.com/zthxxx/jovial) - Shows host, user, path, development environment, `git` branch, which python venv is active.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter) - Theme with `git`, `svn`, and network awareness.
* [karu](https://github.com/zaari/karu) - Minimalist single line ZSH prompt.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes.
* [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user@machine in `ssh` sessions and docker containers.
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klendathu](https://github.com/kegonomics/klendathu) - Uses Powerline iconsolas.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme) - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [lagune](https://github.com/noplay/lagune) - a minimal ZSH theme.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - A simple ZSH theme, optimized for `git` usage.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on Pure, with added NodeJS version.
* [lambda](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
* [lambdav](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information.
* [lewis](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
* [lime](https://github.com/yous/lime) - Simple standalone ZSH theme.
* [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
* [linuxer](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's classyTouch, Yad Smood's ys, and Bureau theme.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & ZSH.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas.
* [logico](https://github.com/logico-dev/logico-zsh-theme) - Has `git` decorations. Shows remote status and indicator for vi-mode.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme) - Variant of lambda-mod theme. Has `git` decorations, requires a powerline-compatible terminal font.
* [luke](https://github.com/xueguangl23/luke_zsh_theme) - Includes `git` decorations. Based on the [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
* [mattizer](https://github.com/matt-sungwook/ohmyzsh-mattizer-theme) - Includes working directory and `git` status decorations.
* [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist.
* [maxulysse/myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) plugin.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [minima](https://github.com/eduardnikolenko/minima) - A minimal ZSH theme with `git`, `go`, `node`, `npm`, `python` and other indicators.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - Theme for dark terminals, includes `git` decorations in the right-side prompt.
* [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimal](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh.
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
* [moux](https://github.com/gagbo/moux) - Works well with a dark background, includes `git` decorations in `RPROMPT`.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
* [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
* [neon](https://github.com/sahariko/neon) - A pretty and minimal ZSH theme with `git` decorations.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH with Nerd Fonts.
* [nescalante](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - OMZ's node theme, broken out to make it easier to use with other plugin managers.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on ys theme, with added NodeJS version (from NVM plugin).
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - Clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or ~ when outside `git` repo), time since last commit, current SHA, branch and branch state.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - Simple theme for prezto and oh-my-zsh.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and ZSH.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme) 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [pastel](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free). Includes `git` decorations.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from [Lambda (Mod) ZSH Theme](https://github.com/halfo/lambda-mod-zsh-theme).
* [pi](https://github.com/tobyjamesthomas/pi) - A minimalist theme with `git` status decorations.
* [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen), and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ZSH theme.
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - Add-on for [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - A git aware powerline theme.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - A [Powerline](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - Created in Ruby, uses powerline characters to simulate pills with useful information.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Shows important details about git/svn/hg/fossil branch and is easy to customize/extend.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - A powerline variant.
* [powerline](https://github.com/carlcarl/powerline-zsh) - A [Powerline](https://github.com/Lokaltog/vim-powerline)-like prompt, based on [powerline-bash](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
* [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - Theme optimized for dark terminal themes.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous vim plugin, which works well for a dark background.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt.
* [purien](https://github.com/sinetoami/purien) - Pretty prompt based on [pure](https://github.com/sindresorhus/pure) prompt, inpired by [alien-minimal](https://github.com/eendroroy/alien-minimal) and [filthy](https://github.com/molovo/filthy).
* [purify](https://github.com/banminkyoz/purify) - Simple, fast & cool prompt.
* [purity](https://github.com/petermbenjamin/purity) - Inspired by robbyrussell theme + pure prompt.
* [pustelto](https://github.com/Pustelto/shell_theme) - Colorful theme inspired by the [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon) - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 theme) (prezto).
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - Simple and colorful theme with `git` status decorations.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - Powerline-styled ZSH theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - Based on agnoster, optimized for [solarized](https://github.com/altercation/solarized) terminal themes.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
* [russtone](https://github.com/russtone/prompt-russtone) - Inspired by [pure](https://github.com/sindresorhus/pure) and [sorin](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - Colorful theme, includes `git` decorations and the current directory.
* [rzh](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis.
* [saltgen](https://github.com/saltgen/ohmyzsh-saltgen-theme) - Variant of the robbyrussell oh-my-zsh theme.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes git status, works well on a dark terminal background.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status, user@host information, exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if Vim is running in the background when using `:sh` command.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by dieter theme, uses color-coding to provide information.
* [senpai](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes git information, kubernetes context, AWS profile, GCP project and Azure active cloud.
* [seppuku](https://github.com/Helianthella/seppuku) - Clean and minimal theme inspired by [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme).
* [sepshell](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
* [Seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - A simple omz-compatible theme with a corresponding iTerm 2 color scheme.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - Simple.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a powerline font.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information.
* [siegerts](https://github.com/siegerts/zsh-theme) - Includes `git` status decorations in right prompt.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). The faster rust port of [bronze](https://github.com/reujab/bronze). Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH.
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with git info display.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - Optimized for a dark terminal, displays `git` status decorations.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
* [slimline](https://github.com/mgee/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - Solarized powerline variant.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) terminals.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - A ZSH theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful indicators.
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by agnoster, [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
* [starboy](https://github.com/prdpx7/Starboy) - A simple ZSH theme
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef) - ZSH steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) theme.
* [sugar-free](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [superkolo](https://github.com/Minipada/superkolo) - Add date and return status to the [kolo](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/kolo.zsh-theme) theme.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - Includes `git` status decorations and an accompanying iTerm2 color scheme.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
* [tahuri](https://github.com/Tahuri/environment-configuration) - ZSH theme for Arch Linux.
* [termuxer](https://github.com/patrick330602/termuxer) - Theme inspired by agnoster and linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - A theme based on gallifrey.
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - Inspired by theunraveler, uses symbols to display `git` status.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
* [tvline](https://github.com/thvitt/tvline) - Derived from [agnoster's theme](https://gist.github.com/agnoster/3712874), adds powerline font enhancements.
* [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme with `git` indicator, vim mode indicator and shortened path.
* [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with a [Solarized](https://github.com/altercation/solarized) color scheme.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
* [webicons](https://github.com/Jmclerck/webicons.zsh-theme) - Includes `git` status, node and yarn versions in prompt.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
* [work-line](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme) - A theme that aims to show you the information you need when you need it. `wynwyn` takes inspiration from the default theme `avit` and the excellent [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xm](https://github.com/Shiaoming/xm) - Theme for dark terminals. Has `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current git commit's shortened hash and message.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on [Robby Russell's theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme).
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](http://ysmood.org/my-ys-terminal-theme/) variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
* [yz50](https://github.com/lacanlale/yz50-zsh) - Colorful, based off of [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/crunch.zsh-theme) themes. Includes `git` status decorations.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) theme.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
* [zero](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - Works best on dark backgrounds, includes `git` status decorations.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name and the current working directory.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous powerline prompt that's easily extensible and extremely configurable.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/maran.zsh-theme) theme.
* [zsh2000](https://github.com/inspectahstack/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to agnoster-zsh-theme, designed to disclose information contextually, with a powerline aesthetic.

### Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - Another Powerline-compatible font.
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](http://input.fontbureau.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Iosevka](https://github.com/be5invis/Iosevka) - Coders’ typeface, built from code. Highly customizable.
* [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

### [Antibody](https://github.com/getantibody/antibody)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antibody will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [Antigen](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3. Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Most of these plugins can be installed by adding `zgen load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgen load` calls in. Zgen will automatically clone the repositories for you when you do a `zgen save`.

### [zplug](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [zshdb](https://github.com/rocky/zshdb) - A ZSH debugger
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.
