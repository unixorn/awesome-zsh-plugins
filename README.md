# awesome-zsh-plugins

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/license/BSD-3-Clause)
![Awesomebot](https://github.com/unixorn/awesome-zsh-plugins/actions/workflows/awesomebot.yml/badge.svg)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
![Contributors](https://img.shields.io/github/contributors/unixorn/awesome-zsh-plugins.svg)
[![GitHub last commit](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/main.svg)](https://github.com/unixorn/awesome-zsh-plugins)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Disclaimer](#disclaimer)
- [Frameworks](#frameworks)
  - [alf](#alf)
  - [ansible-role-zsh](#ansible-role-zsh)
  - [ant-zsh](#ant-zsh)
  - [antibody](#antibody)
  - [antidote](#antidote)
  - [antigen-hs](#antigen-hs)
  - [antigen](#antigen)
  - [ax-zsh](#ax-zsh)
  - [deer](#deer)
  - [dotzsh](#dotzsh)
  - [fresh](#fresh)
  - [gh-source](#gh-source)
  - [miniplug](#miniplug)
  - [oh-my-zsh](#oh-my-zsh)
  - [PMS](#pms)
  - [prezto](#prezto)
  - [pumice](#pumice)
  - [sheldon](#sheldon)
  - [shplug](#shplug)
  - [TheFly](#thefly)
  - [Toasty](#toasty)
  - [uz](#uz)
  - [x-cmd](#x-cmd)
  - [yazt](#yazt)
  - [yzsh](#yzsh)
  - [zap](#zap)
  - [zapack](#zapack)
  - [zcomet](#zcomet)
  - [zeesh](#zeesh)
  - [zgem](#zgem)
  - [zgen](#zgen)
  - [zgenom](#zgenom)
  - [zilsh](#zilsh)
  - [zim](#zim)
  - [Zinit](#zinit)
  - [zinit-4](#zinit-4)
  - [zit](#zit)
  - [zlugin](#zlugin)
  - [znap](#znap)
  - [zoppo](#zoppo)
  - [zpacker](#zpacker)
  - [zpico](#zpico)
  - [zplug](#zplug)
  - [zpm](#zpm)
  - [zr](#zr)
  - [zsh.ai](#zshai)
  - [zshing](#zshing)
  - [zsh-dot-plugin](#zsh-dot-plugin)
  - [zsh-mgr](#zsh-mgr)
  - [zshPlug](#zshplug)
  - [ztanesh](#ztanesh)
  - [ztheme](#ztheme)
  - [ztupide](#ztupide)
  - [zulu](#zulu)
- [Setups](#setups)
  - [zgenom](#zgenom-1)
  - [zinit](#zinit)
- [Prerequisites](#prerequisites)
- [Tutorials](#tutorials)
  - [Generic ZSH](#generic-zsh)
  - [Antigen](#antigen)
  - [Oh-My-Zsh](#oh-my-zsh)
  - [Prezto](#prezto)
  - [Zgen](#zgen)
  - [Zinit (né zplugin)](#zinit-n%C3%A9-zplugin)
  - [ZSH on Windows](#zsh-on-windows)
    - [superconsole - Windows-only](#superconsole---windows-only)
- [Plugins](#plugins)
- [Completions](#completions)
- [Themes](#themes)
- [Fonts](#fonts)
- [Installation](#installation)
  - [Antigen](#antigen-1)
  - [dotzsh](#dotzsh-1)
  - [Oh-My-Zsh](#oh-my-zsh-1)
  - [Prezto](#prezto-1)
  - [Zgen](#zgen-1)
  - [Zgenom](#zgenom)
  - [zplug](#zplug-1)
  - [zpm](#zpm-1)
- [Writing New Plugins and Themes](#writing-new-plugins-and-themes)
- [Other Resources](#other-resources)
  - [ZSH Tools](#zsh-tools)
  - [Other Useful Lists](#other-useful-lists)
  - [Other References](#other-references)
- [Thanks](#thanks)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](Contributing.md) before contributing.*
## Disclaimer

While I have done my best to not add entries with embedded malicious code, I don't have the time to sift through the source of every entry in the list.

THIS LIST IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Frameworks

These frameworks make customizing your ZSH setup easier.

You can find some interesting performance timing comparisons of various frameworks in the following locations.

- [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark) - Contains performance benchmarks for the most popular ZSH frameworks, including both install time and load time.
- [pm-perf-test](https://github.com/z-shell/pm-perf-test) - Tooling for running performance tests on multiple ZSH frameworks.

### [alf](https://github.com/psyrendust/alf)
![GitHub last commit](https://img.shields.io/github/last-commit/psyrendust/alf) ![GitHub Repo stars](https://img.shields.io/github/stars/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after [Prezto](https://github.com/sorin-ionescu/prezto) and [Antigen](https://github.com/zsh-users/antigen) while utilizing [Oh-My-Zsh](https://ohmyz.sh) under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)
![GitHub last commit](https://img.shields.io/github/last-commit/viasite-ansible/ansible-role-zsh) ![GitHub Repo stars](https://img.shields.io/github/stars/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses [antigen](https://github.com/zsh-users/antigen) to manage bundles and [oh-my-zsh](ohmyz.sh). Can load bundles conditionally. By default it includes the powerlevel9k theme, autosuggestions, syntax-highlighting and [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) and [fzf-marks](https://github.com/urbainvaes/fzf-marks). Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)
![GitHub last commit](https://img.shields.io/github/last-commit/anthraxx/ant-zsh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)
![GitHub last commit](https://img.shields.io/github/last-commit/getantibody/antibody)
 ![GitHub Repo stars](https://img.shields.io/github/stars/getantibody/antibody)

**Antibody** is a faster and simpler [antigen](https://github.com/zsh-users/antigen) written in Golang. More details are available at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antidote](https://getantidote.github.io/)
![GitHub last commit](https://img.shields.io/github/last-commit/mattmc3/antidote)
 ![GitHub Repo stars](https://img.shields.io/github/stars/mattmc3/antidote)

**Antidote** is a ZSH plugin manager made from the ground up thinking about performance.

It is fast because it can do things concurrently, and generates an ultra-fast static plugin file that you can include in your ZSH config.

It is written natively in ZSH, is well tested, and picks up where [Antibody](https://github.com/getantibody/antibody) left off.

[use-omz](https://github.com/getantidote/use-omz) enables easy use of [Oh-My-ZSH](https://github.com/ohmyzsh/ohmyzsh) with antidote.

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)
![GitHub last commit](https://img.shields.io/github/last-commit/Tarrasch/antigen-hs)
 ![GitHub Repo stars](https://img.shields.io/github/stars/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for [antigen](https://github.com/zsh-users/antigen) optimized for a low overhead when starting up a `zsh` session. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen)
![GitHub last commit](https://img.shields.io/github/last-commit/zsh-users/antigen)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)
![GitHub last commit](https://img.shields.io/github/last-commit/alexbarton/ax-zsh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

**Ax-ZSH** integrates well with [Powerlevel10k](https://github.com/romkatv/powerlevel10k) and other extensions, including plugins compatible with [oh-my-zsh](https://ohmyz.sh/).

### [deer](https://github.com/ArtixLabs/deer)
![GitHub last commit](https://img.shields.io/github/last-commit/ArtixLabs/deer)
 ![GitHub Repo stars](https://img.shields.io/github/stars/ArtixLabs/deer)

A minimalist ZSH plugin manager.

### [dotzsh](https://github.com/dotphiles/dotzsh)
![GitHub last commit](https://img.shields.io/github/last-commit/dotphiles/dotzsh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh)
![GitHub last commit](https://img.shields.io/github/last-commit/freshshell/fresh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as [Bundler](https://bundler.io) for your dot files.

### [gh-source](https://github.com/Yarden-zamir/gh-source)
![GitHub last commit](https://img.shields.io/github/last-commit/Yarden-zamir/gh-source) ![GitHub Repo stars](https://img.shields.io/github/stars/Yarden-zamir/gh-source)


**gh-source** is a plugin manager for people who don't like plugin managers. It's a simple shell function that downloads and installs plugins from GitHub as part of the sourcing step. It's designed to be used with `zsh`, but it should work with any shell.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)
![GitHub last commit](https://img.shields.io/github/last-commit/yerinalexey/miniplug) ![GitHub Repo stars](https://img.shields.io/github/stars/yerinalexey/miniplug)

**miniplug** is a minimalistic plugin manager for ZSH.

- No crashes or double plugin loading when re-sourcing `.zshrc`
- Unlike other frameworks, Miniplug does not pollute your `$PATH`
- Only does the bare minimum for managing plugins

### [oh-my-zsh](https://ohmyz.sh/)
![GitHub last commit](https://img.shields.io/github/last-commit/ohmyzsh/ohmyzsh) ![GitHub Repo stars](https://img.shields.io/github/stars/ohmyzsh/oh-my-zsh)


**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, `git`, macOS, `hub`, `capistrano`, `brew`, `ant`, MacPorts, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [PMS](https://github.com/JoshuaEstes/pms)
![GitHub last commit](https://img.shields.io/github/last-commit/JoshuaEstes/pms)
 ![GitHub Repo stars](https://img.shields.io/github/stars/JoshuaEstes/pms)

PMS allows you to manage your shell in a way to that helps decrease setup time and increases your productivity. It has support for themes (change the way your shell looks), plugins (adds functionality to your shell), and dotfile management.

The PMS framework also allows you to use the same framework in different shells. Use ZSH on your personal laptop, and use `bash` on remote servers. Wanna try `fish`? Go ahead, try out different shells.

### [prezto](https://github.com/sorin-ionescu/prezto)
![GitHub last commit](https://img.shields.io/github/last-commit/sorin-ionescu/prezto)
 ![GitHub Repo stars](https://img.shields.io/github/stars/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some [prezto](https://github.com/sorin-ionescu/prezto)-specific plugins at [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)
![GitHub last commit](https://img.shields.io/github/last-commit/ryutamaki/pumice)
 ![GitHub Repo stars](https://img.shields.io/github/stars/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [sheldon](https://github.com/rossmacarthur/sheldon)
![GitHub last commit](https://img.shields.io/github/last-commit/rossmacarthur/sheldon)
  ![GitHub Repo stars](https://img.shields.io/github/stars/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

- Can manage
  - Any `git` repository.
    - Branch/tag/commit support.
    - Extra support for GitHub repositories.
    - Extra support for Gists.
  - Arbitrary remote files, simply specify the URL.
  - Local plugins, simply specify the directory path.
- Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
- Super-fast parallel installation.
- Configuration file using [TOML](https://github.com/toml-lang/toml) syntax.
- Uses a lock file for much faster loading of plugins.

### [shplug](https://github.com/dtrugman/shplug)
![GitHub last commit](https://img.shields.io/github/last-commit/dtrugman/shplug)
 ![GitHub Repo stars](https://img.shields.io/github/stars/dtrugman/shplug)

An easy solution for managing your shell environments. Works with both `bash` and `zsh`. Makes it easy to sync your environment across multiple machines with a `git` repository.

### [TheFly](https://github.com/joknarf/thefly)

`bash`/`zsh`/`ksh` plugin manager and env teleporter

Makes your shell env and plugins available everywhere (hosts/users)!

### [Toasty](https://github.com/CosmicToast/toasty-zsh)
![GitHub last commit](https://img.shields.io/github/last-commit/CosmicToast/toasty-zsh) ![GitHub Repo stars](https://img.shields.io/github/stars/CosmicToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [uz](https://github.com/maxrodrigo/uz)
![GitHub last commit](https://img.shields.io/github/last-commit/maxrodrigo/uz)
 ![GitHub Repo stars](https://img.shields.io/github/stars/maxrodrigo/uz)

A ZSH micro plugin manager.

### [x-cmd](https://github.com/x-cmd/x-cmd)
![GitHub last commit](https://img.shields.io/github/last-commit/x-cmd/x-cmd)
 ![GitHub Repo stars](https://img.shields.io/github/stars/x-cmd/x-cmd)
**x-cmd** is a toolset implemented using posix shell and awk.It is very small in size and offers many interesting features. Here is a milestone demo: https://x-cmd.com/

Tools Provided by x-cmd:
  - [Wrappers for Common Commands (e.g., cd, ip, ps, tar, apt, brew)](https://x-cmd.com/mod/zuz): These wrapped commands are more intelligent and easier to use compared to the native commands.
  - [Lightweight Package Management Tool](https://x-cmd.com/pkg/): We have implemented a lightweight package management tool using shell and awk. Through it, you can quickly obtain most common software tools, such as jq, 7za, bat, nvim, python, node, go, etc.
  - [CLI for Useful Websites (e.g., github.com, cht.sh)](https://x-cmd.com/mod/cht): We have wrapped their APIs using shell and awk for daily use and to obtain corresponding services in scripts.
  - [AI Tools](https://x-cmd.com/mod/openai): We provide CLIs for ChatGPT, Gemini, Jina.ai, etc., and have wrapped corresponding shortcut commands for different application scenarios, such as `@gemini` for chatting with Gemini AI and `@zh` for using AI to translate specified content or command results.

### [yazt](https://github.com/bashelled/yazt)
![GitHub last commit](https://img.shields.io/github/last-commit/bashelled/yazt)
 ![GitHub Repo stars](https://img.shields.io/github/stars/bashelled/yazt)

**Yazt** is a simple ZSH theme manager in maintenance that is compatible with nearly everything. You can use prompts in plugins, mix 'n' match two themes and with a few modifications, you can even use it in `bash`.

### [yzsh](https://github.com/yunielrc/yzsh)
![GitHub last commit](https://img.shields.io/github/last-commit/yunielrc/yzsh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/yunielrc/yzsh)

**yzsh** is a simple ZSH framework for managing plugins, themes, functions, aliases and environment variables.

### [zap](https://github.com/zap-zsh/zap)
![GitHub last commit](https://img.shields.io/github/last-commit/zap-zsh/zap)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zap-zsh/zap)

**zap** is a minimal ZSH plugin manager.

### [zapack](https://github.com/aiya000/zsh-zapack)
![GitHub last commit](https://img.shields.io/github/last-commit/aiya000/zsh-zapack)
 ![GitHub Repo stars](https://img.shields.io/github/stars/aiya000/zsh-zapack)

**zapack** is a basic fast minimal ZSH plugin loader.

### [zcomet](https://github.com/agkozak/zcomet)
![GitHub last commit](https://img.shields.io/github/last-commit/agkozak/zcomet)
 ![GitHub Repo stars](https://img.shields.io/github/stars/agkozak/zcomet)

**zcomet** is a minimalistic ZSH plugin manager that gets you to the prompt surprisingly quickly without caching (see the benchmarks). In addition to loading and updating plugins stored in `git` repositories, it supports lazy-loading plugins (further reducing startup time) as well as downloading and sourcing code snippets.

### [zeesh](https://github.com/zeekay/zeesh)
![GitHub last commit](https://img.shields.io/github/last-commit/zeekay/zeesh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)
![GitHub last commit](https://img.shields.io/github/last-commit/qoomon/zgem)
 ![GitHub Repo stars](https://img.shields.io/github/stars/qoomon/zgem)

**zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen)
![GitHub last commit](https://img.shields.io/github/last-commit/tarjoilija/zgen)
 ![GitHub Repo stars](https://img.shields.io/github/stars/tarjoilija/zgen)

**Zgen is currently not being actively maintained** and I recommend you use the [zgenom](https://github.com/jandamm/zgenom) fork instead, which is actively maintained and continues to get new features.

**Zgen** is a lightweight plugin manager for ZSH inspired by [Antigen](https://github.com/zsh-users/antigen). The goal is to have minimal overhead when starting up the shell because nobody likes waiting.

### [zgenom](https://github.com/jandamm/zgenom)
![GitHub last commit](https://img.shields.io/github/last-commit/jandamm/zgenom)
 ![GitHub Repo stars](https://img.shields.io/github/stars/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen](https://github.com/tarjoilija/zgen) and provides more features and bugfixes while being fully backwards compatible.

To keep loading fast during new terminal sessions, `zgenom` generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during every shell session's startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto](https://github.com/sorin-ionescu/prezto)-compatible plugins and themes, and will automagically `git clone` plugins for you when you add them to your plugin list.

### [zilsh](https://github.com/zilsh/zilsh)
![GitHub last commit](https://img.shields.io/github/last-commit/zilsh/zilsh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)
![GitHub last commit](https://img.shields.io/github/last-commit/zimfw/zimfw)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma-continuum/zinit)
![GitHub last commit](https://img.shields.io/github/last-commit/zdharma-continuum/zinit) ![GitHub Repo stars](https://img.shields.io/github/stars/zdharma-continuum/zinit)


**Zinit** is an innovative and probably (because of the Turbo) the fastest plugin manager with support for:

- Turbo mode – 80% faster ZSH startup! for example: instead of 200 ms, it'll be 40 ms
- Completion management (selectively disable and enable completions)
- Snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead)
- Annexes (↔ Zinit extensions)
- Reports (from the plugin loads – plugins are no longer black boxes)
- Plugin unloading (allows e.g.: dynamic theme switching)
- `bindkey` capturing and remapping
- packages
- Clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated)
- Services ↔ a single-instance, background plugins
- Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

The project is very active – currently > 3100 commits.

### [zinit-4](https://github.com/psprint/Zinit-4)
![GitHub last commit](https://img.shields.io/github/last-commit/psprint/Zinit-4)
 ![GitHub Repo stars](https://img.shields.io/github/stars/psprint/Zinit-4)

This is Zinit 4 from the [original author](https://github.com/psprint), who once removed the [Zinit](https://github.com/zdharma-continuum/zinit) repository from GitHub. This spawned a community-driven [zdharma-continuum](https://github.com/zdharma-continuum) organization that revived all of psprint's ZSH projects. Its main innovations from the @zdharma-continuum fork are:

- AppImage distribution (release link),
- Action complete – press Alt-Shift-A and Alt-Shift-C to complete plugin names and ice modifiers,
- Themes – set $ZITHEME to one of default, blue and gold to set a color set to use for Zinit 4 messages,
- New ice `build` which is equivalent of three other ices: `null`, `configure` and `make install` and simply builds the project from sources, with support for autotools/CMake/Meson/Scons.

These are the most visible changes, but there are more (like e.g.: support for compiling with libraries from previously built projects/`$ZPFX`).

### [zit](https://github.com/thiagokokada/zit)
![GitHub last commit](https://img.shields.io/github/last-commit/thiagokokada/zit)
 ![GitHub Repo stars](https://img.shields.io/github/stars/thiagokokada/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from `git` repositories (and `git` repositories only, that's why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, `$PATH` manipulation and others.

### [zlugin](https://github.com/DrgnFireYellow/zlugin)
![GitHub last commit](https://img.shields.io/github/last-commit/DrgnFireYellow/zlugin)
 ![GitHub Repo stars](https://img.shields.io/github/stars/DrgnFireYellow/zlugin)

**zlugin** is a very lightweight ZSH plugin manager.

### [znap](https://github.com/marlonrichert/zsh-snap)
![GitHub last commit](https://img.shields.io/github/last-commit/marlonrichert/zsh-snap) ![GitHub Repo stars](https://img.shields.io/github/stars/marlonrichert/zsh-snap)


**:zap:Znap** is a light-weight plugin manager & `git` repository manager for ZSH that's easy to grok. While tailored for ZSH plugins specifically, **Znap** also functions as a general-purpose utility for managing `git` repositories.

Znap can:

- Make any prompt appear instantly. Reduce your startup time from ~200ms to ~40ms with just one command.
- Asynchronously compile your plugins and functions.
- Cache those expensive `eval $(commands)`.
- Clone or pull multiple repos in parallel.
- Re-clone all your repos without you having to re-enter them.
- Multi-repo management
- Automatic `compinit` and `bashinit` - you no longer need them in your `.zshrc`, znap will do them automatically as needed.

### [zoppo](https://github.com/zoppo/zoppo)
![GitHub last commit](https://img.shields.io/github/last-commit/zoppo/zoppo)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)
![GitHub last commit](https://img.shields.io/github/last-commit/happyslowly/zpacker)
 ![GitHub Repo stars](https://img.shields.io/github/stars/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico](https://github.com/thornjad/zpico)
![GitHub last commit](https://img.shields.io/github/last-commit/thornjad/zpico)
 ![GitHub Repo stars](https://img.shields.io/github/stars/thornjad/zpico)

The minuscule ZSH package manager. No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.

ZSH package managers are abundant, but most are bloated, slow or have excessive requirements. On top of that, more than a few have been abandoned for years. Zpico does not seek to be the best of the best, rather to balance functionality against a tiny, fast footprint.

### [zplug](https://github.com/zplug/zplug)
![GitHub last commit](https://img.shields.io/github/last-commit/zplug/zplug)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- Can manage everything
  - ZSH plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - Gist files ([gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- Super-fast parallel installation/update
- Support for lazy-loading
- Branch/tag/commit support
- Post-update, post-load hooks
- Dependencies between packages
- Unlike [antigen](https://github.com/zsh-users/antigen), no ZSH plugin files (`*.plugin.zsh`) are required
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw), and so on)
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)
![GitHub last commit](https://img.shields.io/github/last-commit/zpm-zsh/zpm)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) which combines the imperative and declarative approach. At first run, zpm will do complex logic and generate a cache, after that will only use the cache, so it makes this framework very fast.

- Fastest plugin manager (Really, after the first run, zpm will not be used at all)
- Support for async loading
- Dependencies between packages
- **zpm** runs on Linux, macOS, FreeBSD and Android.
- **zpm** plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)
![GitHub last commit](https://img.shields.io/github/last-commit/jedahan/zr)
 ![GitHub Repo stars](https://img.shields.io/github/stars/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zsh.ai](https://github.com/zsh-ai/zsh.ai)
![GitHub last commit](https://img.shields.io/github/last-commit/zsh-ai/zsh.ai)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zsh-ai/zsh.ai)

Focuses on security and hardening of local system. Requires [fzf](https://github.com/junegunn/fzf)

### [zshing](https://github.com/zakariaGatter/zshing)
![GitHub last commit](https://img.shields.io/github/last-commit/zakariaGatter/zshing)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

- Keep track of and configure your plugins right in the `.zshrc`
- Install ZSH plugins
- Update ZSH plugins
- Search by name all available ZSH Plugins
- Clean unused plugins up
- Run the above actions in a *single command*
- Manages the **Source Plugins** of your installed Plugins

### [zsh-dot-plugin](https://github.com/DuckzCantFly/zsh-dot-plugin)
![GitHub last commit](https://img.shields.io/github/last-commit/DuckzCantFly/zsh-dot-plugin) ![GitHub Repo stars](https://img.shields.io/github/stars/DuckzCantFly/zsh-dot-plugin)


Customize your `.zshrc` with only ~21 lines of code. Based on [zsh-unplugged](https://github.com/mattmc3/zsh_unplugged).
![GitHub last commit](https://img.shields.io/github/last-commit/mattmc3/zsh_unplugged)
 ![GitHub Repo stars](https://img.shields.io/github/stars/mattmc3/zsh_unplugged)

### [zsh-mgr](https://github.com/amt911/zsh-mgr)
![GitHub last commit](https://img.shields.io/github/last-commit/amt911/zsh-mgr)
 ![GitHub Repo stars](https://img.shields.io/github/stars/amt911/zsh-mgr)

A simple plugin manager for zsh. Features:

- Auto-updates all plugins.
- Auto-updates itself.
- Configurable time interval for both auto-updaters.

### [zshPlug](https://github.com/Atlas34/zshPlug)
![GitHub last commit](https://img.shields.io/github/last-commit/Atlas34/zshPlug)
 ![GitHub Repo stars](https://img.shields.io/github/stars/Atlas34/zshPlug)

**zshPlug** is a minimalist plugin manager heavily based on [zap](https://github.com/zap-zsh/zap).

### [ztanesh](https://github.com/miohtama/ztanesh)
![GitHub last commit](https://img.shields.io/github/last-commit/miohtama/ztanesh)
 ![GitHub Repo stars](https://img.shields.io/github/stars/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme](https://github.com/SkyyySi/ztheme)
![GitHub last commit](https://img.shields.io/github/last-commit/SkyyySi/ztheme)
 ![GitHub Repo stars](https://img.shields.io/github/stars/SkyyySi/ztheme)

**ztheme** is a small and fast theme engine for ZSH.

### [ztupide](https://github.com/mpostaire/ztupide)
![GitHub last commit](https://img.shields.io/github/last-commit/mpostaire/ztupide)
 ![GitHub Repo stars](https://img.shields.io/github/stars/mpostaire/ztupide)

A simple and fast ZSH plugin manager. It uses `zcompile` and async loading to speed up your shell startup time.

### [zulu](https://github.com/zulu-zsh/zulu)
![GitHub last commit](https://img.shields.io/github/last-commit/zulu-zsh/zulu)
 ![GitHub Repo stars](https://img.shields.io/github/stars/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5 or later, which aims to make it easy to manage your shell without writing any code.

- Easily manage your shell environment without editing files.
- Create aliases, functions and environment variables, and have them available to you at the next shell startup.
- Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
- Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

- [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with [zgenom](https://github.com/jandamm/zgenom). This automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) to load a curated (but easily customizable) collection of plugins and periodically automatically update itself, the plugins, and the quickstart kit itself.

### zinit

- [ZPWR](https://github.com/MenkeTechnologies/zpwr) - An extremely powerful custom terminal environment built on top of [Zinit](https://github.com/zdharma-continuum/zinit) for maximum speed.  A full terminal configuration framework including `zsh`, `tmux`, `fzf`, `vim` and spacemacs configurations.  It includes:

- 12.9k+ tab completions
- 1.9k+ aliases
- 330+ git aliases
- 400+ zpwr subcommands
- 2.8k functions
- 175+ zpwr environment variables
- 175+ perl, python, bash, ZSH scripts
- 2.8k line README.md
- 50k+ LOC
- 1 line install

## Prerequisites

If you're on a Mac, the `zsh` that comes with it is usually pretty stale. You can use `brew install zsh` to update it.

Many of the themes here use special glyphs for things like displaying a branch icon. You'll need to use a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) or a Powerline-compatible font in your terminal program or you'll see ugly broken boxes where the symbols should be.

Here are a few good sources for Nerd Fonts and Powerline-compatible fonts:

- [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that include some nice monospaced Icons.
- [Cascadia Code](https://github.com/microsoft/cascadia-code) - Microsoft's Cascadia Code
- [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons, and Powerline-Glyphs.
- [Fira Mono](https://github.com/mozilla/Fira) - Mozilla's Fira type family.
- [Hack](http://sourcefoundry.org/hack/) - Another Powerline-compatible font designed for source code and terminal usage.
- [Input Mono](https://input.djr.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes Powerline glyphs.
- [Iosevka](https://be5invis.github.io/Iosevka/) - Iosevka is an open source slender monospace sans-serif and slab-serif typeface inspired by [Pragmata Pro](http://www.fsd.it/fonts/pragmatapro.htm), M+ and [PF DIN Mono](https://www.myfonts.com/fonts/parachute/pf-din-mono/), designed to be the ideal font for programming.
- [Monoid](http://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
- [Mononoki](https://madmalik.github.io/mononoki/) - Mononoki is a typeface by Matthias Tellen, created to enhance code formatting.
- [More Nerd Fonts](https://www.nerdfonts.com/font-downloads) - Another site to download nerd fonts.
- [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) - A collection of over 20 patched fonts (over 1,700 variations) & the fontforge font patcher python script for Powerline, devicons, and vim-devicons: includes Droid Sans, Meslo, AnonymousPro, ProFont, Inconsolta, and many more. These can be installed with `brew` - do `brew tap homebrew/cask-fonts && brew install --cask fontname`
- [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include Powerline glyphs.
- [Spacemono](https://github.com/googlefonts/spacemono) - Google's new original monospace display typeface family.
- [Victor Mono](https://rubjo.github.io/victor-mono/) - Victor Mono is a free programming font with semi-connected cursive italics, symbol ligatures (!=, ->>, =>, ===, <=, >=, ++) and Latin, Cyrillic and Greek characters.

## Tutorials

### Generic ZSH

- [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Tutorial using a combination of [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
- [A Guide to ZSH Completion With Examples](https://thevaluable.dev/zsh-completion-guide-examples/) - Explains ZSH autocompletion configuration with examples.
- [adamnorwood-zsh](https://github.com/adamnorwood/adamnorwood-zsh/) - A minimalist but readable ZSH setup based on [oh-my-posh](https://ohmyposh.dev/).
- [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) -  Not actually Arch or Linux-specific.
- [GH](https://github.com/gustavohellwig/gh-zsh) - Setup ZSH on debian/Ubuntu-based linuxes. Installs [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/), and more.
- [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
- [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
- [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) - covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
- [Profiling ZSH](https://ellie.wtf/notes/profiling-zsh) - Good article about profiling your ZSH setup to optimize startup time.
- [rs-example](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
- [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
- [zephyr](https://github.com/mattmc3/zephyr) - Zephyr uses built-in Zsh features to set up better default options, completions, keybindings, history, and much more.
- [ZSH for Humans](https://github.com/romkatv/zsh4humans) - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
- [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
- [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
- [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) - Good resource if you want to eliminate using a framework but still easily use plugins.

### Antigen

- [belak/zsh-utils](https://github.com/belak/zsh-utils) - A minimal set of ZSH plugins designed to be low-friction and low-complexity.
- [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
- [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

- [Configuration to use Hyper.js as a ZSH terminal with a Windows Subsystem Linux on windows 10, with Oh My Zsh and the Powerlevel10k theme](https://github.com/jkergal/hyperjs-wsl-zsh-powerlevel10k-config-on-windows/) - How-to for getting Oh-My-ZSH running on WSL.
- [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
- [How to Install and Configure Z Shell in Ubuntu](https://github.com/profpan396/how-to-install-and-configure-zshell) - Amar Pan's article will walk you through the process of installing and configuring ZSH, including how to change themes and enable the time-saving autosuggestions plug-in.
- [iTerm2 + Oh-My-ZSH: Supercharge Your Mac Terminal](https://catalins.tech/improve-mac-terminal) - Catalin Pit's tutorial on getting started with Oh-My-ZSH on macOS.
- [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - A beginners guide to using Oh My Zsh on macOS by Karl Hadwen
- [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
- [One Key Linux Setup](https://github.com/miracleyoo/one-key-linux-setup) - Simple setup (ubuntu-only) of `zsh`, `oh-my-zsh`, `tmux`, `python` support and other packages.

### Prezto

- [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
- [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

- [rad-shell](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto), and [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (né zplugin)

- [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) - :crystal_ball: Awesome, customizable Zsh Starter Kit :stars::stars:. Includes powerline, [fzf](https://github.com/junegunn/fzf) integration, Weather and image viewing in some terminals.
- [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) - Real-world configuration files (basically a collection of `.zshrc` files) holding [zinit](https://github.com/zdharma-continuum/zinit) invocations.

### ZSH on Windows

#### [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only

- `ConEmu`/`zsh` out-of-the-box configured to restore previously opened tabs and shell working directories after `ConEmu` restart
- Choose between clean and inherited environment when starting new SuperConsole sessions
- Custom colorful scheme, colorful output for various commands
- `MSYS2` included, `zsh` and necessary software preinstalled, uses zsh-grml-config
- Uses [Antigen](https://github.com/zsh-users/antigen) for ZSH theme and config management
- Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
- Git-for-Windows repo with proper `git` and `git lfs` support for `MSYS2` environment is configured, `git` client already installed.
- `ssh-agent` for `git` works out-of-box, add your keys to `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` dir
- Non-blocking ZSH prompt status updates thanks to [agkozak-zsh-prompt](https://github.com/agkozak/agkozak-zsh-prompt)
- Command-not-found handler customized for `MSYS2` suggests what package to install
- Sets up `nano` as main editor, enables `nano` syntax highlighting
- Custom helper scripts added to `ConEmu/msys64/3rdparty`

## Plugins

- [1password](https://github.com/agpenton/1password-zsh-plugin) - Adds [1Password](https://1password.com/) functionality including a `opswd` command that wraps the `op` command. It takes a service name as an argument and copies the password for that service to the clipboard.
- [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
- [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
- [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
- [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
- [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) scripts from your command line. Includes tab completions.
- [activate-py-environment](https://github.com/se-jaeger/zsh-activate-py-environment) - Automagically detects and activates your python environments (`poetry`, `virtualenv` and `conda`) while traversing directories.
- [adonisjs](https://github.com/baliestri/adonisjs.plugin.zsh) - Plugin for skipping the `node` part of the `ace` command.
- [ai-commands](https://github.com/muePatrick/zsh-ai-commands) - Asks GPT (gpt-4-turbo-preview) for CLI commands that achieve the described target action.
- [airpods-battery](https://github.com/louis-thevenet/zsh-airpods-battery/) - Looks for AirPods via Bluetooth and puts their battery charge state into `$RPROMPT`.
- [alacritty](https://github.com/casonadams/alacritty-shell) - Control [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) color schemes.
- [alehouse](https://github.com/sticklerm3/alehouse) - Contains short aliases for [brew](https://brew.sh) commands, inspired by `betterbrew`.
- [alias-finder](https://github.com/akash329d/zsh-alias-finder) - Displays an alias when you use a command you have aliased previously. Helpful for remembering aliases you have defined in the past. Written as a pure ZSH script for speed.
- [alias-maker](https://github.com/MefitHp/alias-maker) - Allows you to easily create and manage aliases from the command line.
- [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
- [allclear](https://github.com/givensuman/zsh-allclear) - Clears the terminal when you cd into `$HOME`.
- [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with Antigen.
- [almostontop](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by the [alwaysontop](https://github.com/swirepe/alwaysontop) plugin for `bash`.
- [alt-and-select](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
- [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for [Ansible](https://www.ansible.com/).
- [ansimotd](https://github.com/yuhonas/zsh-ansimotd) - Adds old-school cool ANSI art when a login shell starts.
- [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
- [antidote-use-omz](https://github.com/getantidote/use-omz) - Make using [oh-my-zsh](https://ohmyz.sh/) with [antidote](https://getantidote.github.io/) seamless.
- [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
- [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH.
- [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
- [apparix](https://github.com/micans/apparix) - Command line directory bookmarks with jumping to bookmarks, subdirectory tab completion, distant listing etc.
- [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
- [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
- [apt](https://github.com/GeoLMg/apt-zsh-plugin) - For distros with `apt` package manager. Offers to install missing programs for you.
- [arc](https://github.com/anton-rudeshko/zsh-arc) - Adds aliases for Yandex version control system.
- [archlinux (fourdim)](https://github.com/fourdim/zsh-archlinux) - Defines helper functions for `pacman` on Arch Linux.
- [archlinux (junker)](https://github.com/Junker/zsh-archlinux) - Based on the oh-my-zsh [archlinux](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/archlinux) plugin. Defines helper functions and aliases.
- [arduino](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
- [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
- [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
- [asdf (kiurchv)](https://github.com/kiurchv/asdf.plugin.zsh) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
- [asdf (zimfw)](https://github.com/zimfw/asdf) - Initializes [asdf](https://github.com/asdf-vm/asdf), installing it using `git` if not installed yet. Also, bypasses the shims if you're using the [direnv](https://github.com/asdf-community/asdf-direnv) plugin, as suggested by the plugin [pro-tips](https://github.com/asdf-community/asdf-direnv/#pro-tips).
- [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf) and [direnv](https://github.com/asdf-community/asdf-direnv).
- [asdf-prompt](https://github.com/CurryEleison/zsh-asdf-prompt) - Provides a function usable in prompts that displays version information for your current tool versions.
- [ask](https://github.com/Licheam/zsh-ask) - Serves as a ChatGPT API frontend, enabling you to interact with ChatGPT directly from the ZSH shell using only `cURL` and `jq`.
- [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
- [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
- [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - Based on the [Sublime](https://github.com/valentinocossar/sublime) plugin, lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
- [atuin](https://github.com/ellie/atuin) - Replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
- [aur-install](https://github.com/redxtech/zsh-aur-install) - Small plugin to install packages from the AUR.
- [auto-cenv](https://github.com/mobiuscog/zsh-auto-cenv) - Automatically activate a conda environment when entering the project folder.
- [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
- [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
- [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - Automatically runs `ls` or `color-ls` if available on `cd`.
- [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
- [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
- [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
- [auto-pnpm-use](https://github.com/brunomacedo/zsh-auto-pnpm-use) - Automatically loads the node version specified in `.nvmrc` or `.npmrc`.
- [auto-venv](https://github.com/Skylor-Tang/auto-venv) - Automatically activates the Python virtual environment in the current directory or its parent directories.
- [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
- [autodark (cravend)](https://github.com/cravend/autodark) - Switches between user-specified light and dark themes. Only works on macOS.
- [autodark (vbwx)](https://github.com/vbwx/zsh-autodark) - Switches to another Terminal profile if dark mode is enabled (macOS-only).
- [autodotenv](https://github.com/nocttuam/autodotenv) - Will prompt you to load variables when you `cd` into a directory containing a `.env` file.
- [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) plugin.
- [autoenv](https://github.com/hyperupcall/autoenv) - Directory-based environments.
- [autojump](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
- [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
- [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
- [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
- [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects [pipenv](https://pypi.org/project/pipenv/) and [poetry](https://python-poetry.org/) projects.
- [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) - A fork of [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) for the [Antibody](https://getantibody.github.io) plugin manager, with the added ability to cooperate with static loading.
- [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) - [Antigen](https://github.com/zsh-users/antigen) doesn't do automatic updates like [oh-my-zsh](https://ohmyz.sh/). This plugin adds auto updating for `antigen`, both of `antigen` and the bundles loaded in your configuration.
- [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - [oh-my-zsh](https://ohmyz.sh/) doesn't automatically update non-core plugins, this plugin autoupdates `git` repositories in the `$ZSH_CUSTOM` directory.
- [autovenv](https://github.com/linnnus/autovenv) - Automatically activates Python virtual environments when entering their parent directory.
- [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying `mfa_device` in profile.
- [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - Plugin for AWS MFA.
- [aws-plugin](https://github.com/pookey/zsh-aws-plugin) - Adds helper functions for `aws` command. Includes mfa and `assume-role` helpers.
- [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
- [aws-vault-profiles](https://github.com/jonscheiding/zsh-plugin-aws-vault-profiles) - Plugin that integrates usage of [aws-vault](https://github.com/99designs/aws-vault) with the `$AWS_PROFILE` environment variable.
- [aws-vault](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault](https://github.com/99designs/aws-vault). Includes tab completions.
- [aws](https://github.com/apachler/zsh-aws) - Forked from the original [oh-my-zsh](https://ohmyz.sh/) [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws). Includes completions for `awscli` and a few utilities for managing AWS profiles and displaying them in your prompt.
- [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
- [awsssh](https://github.com/raisedadead/zsh-awsssh) - List, select and `ssh` into EC2 instances.
- [awsume](https://github.com/Sordie/AWSume) - Plugin that enables showing the current [awsume](https://github.com/trek10inc/awsume) profile.
- [azcli](https://github.com/dmakeienko/azcli) - Helper for using the Azure cli tools.
- [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) - Makes using Azure keyvaults less verbose from the cli.
- [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) - Displays information about the Azure current Subscription and tenant.
- [banner](https://github.com/drkhsh/zsh-banner) - Displays ANSI/ASCII art on session startup.
- [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
- [bash-quote](https://github.com/jtprog/bash-quote) - Get random quote from Bash.im.
- [bash](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
- [bat](https://github.com/fdellwing/zsh-bat) - Adds some helper aliases for [bat](https://github.com/sharkdp/bat) users.
- [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
- [bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
- [bepoptimist](https://github.com/sheoak/zsh-bepoptimist/) Remaps vi-mode for the French [bépo](http://bepo.fr/wiki/Accueil) keyboard.
- [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
- [bitwarden (casonadams)](https://github.com/casonadams/bitwarden-cli) - A [Bitwarden](https://bitwarden.com/download/) CLI fuzzy finder using [fzf](https://github.com/junegunn/fzf). Requires [jq](https://stedolan.github.io/jq/).
- [bitwarden (game4move78)](https://github.com/Game4Move78/zsh-bitwarden) - Adds functions to manage [bitwarden](https://bitwarden.com/) sessions.
- [bitwarden (kalsowerus)](https://github.com/kalsowerus/zsh-bitwarden) - Opens a [fzf](https://github.com/junegunn/fzf) widget containing your [Bitwarden](https://bitwarden.com/) vault items. Upon selecting an item either the username or password will be either written into the shell or copied into the clipboard. Requires `fzf`, `jq` and `bitwarden`.
- [blackbox](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a `git` repository.
- [bob](https://github.com/wintermi/zsh-bob) - Plugin for [bob](https://github.com/MordechaiHadad/bob) a cross-platform and easy-to-use Neovim version manager.
- [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
- [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
- [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - Manages `docker` on macOS.
- [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - Adds some convenience aliases for `git`.
- [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
- [brave](https://github.com/troykelly/oh-my-zsh-brave) - Manages [Brave](https://brave.com) profiles. With this plugin, you can start the Brave Browser with a specific user profile by using the brave command followed by the profile's name. The plugin also implements autocompletion for the profile names so you won't have to type the entire profile name manually.
- [brew (rhuang2014)](https://github.com/rhuang2014/brew) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
- [brew (wintermi)](https://github.com/wintermi/zsh-brew) - Simple plugin for the [Homebrew](https://brew.sh/) Package Manager.
- [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
- [brew-switcher](https://github.com/fielding/zsh-brew-switcher) - Automatically switch between Homebrew installations based on the current active arch, arm64 or x86_64, on Apple Silicon Macs.
- [browse-commit](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line.
- [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
- [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle prepending `optirun` in the command line.
- [bw](https://github.com/begris/bw-zsh-plugin) - Provides formatting options and easy access to credentials stored in [Bitwarden](https://bitwarden.com) via the Bitwarden [CLI](https://bitwarden.com/download/). The plugin tries to retrieve a valid session before each action, therefore an explicit login is not nescessary beforehand.
- [bws](https://github.com/elogiclab/zsh-bws) - Simplify and improve the retrieval of secrets from the [Bitwarden](https://bitwarden.com) Secret Manager.
- [c](https://github.com/sebastiangraz/c) - Adds some `git` shortcuts.
- [calc (arzzen)](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
- [calc (sam-programs)](https://github.com/Sam-programs/zsh-calc) - Allows you to run math calculations with no prefixes.
- [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) source for [zaw](https://github.com/zsh-users/zaw)
- [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use](https://caniuse.com) support to ZSH.
- [careful_rm](https://github.com/MikeDacre/careful_rm) - A wrapper for `rm` that adds trash/recycling and useful warnings.
- [case](https://github.com/rtuin/zsh-case) - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
- [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
- [cd-ls](https://github.com/zshzoo/cd-ls) - Automatically `ls` after `cd`.
- [cd-reminder](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
- [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to `cd` to the current repository checkout's root directory.
- [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
- [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
- [cdc](https://github.com/evanthegrayt/cdc) - Makes it easier to change directories to directories that are subdirs of a user-defined list of directories. Includes tab-completion, session history and `pushd`, `popd` and `dirs` equivalents.
- [cdh](https://github.com/johncassol/cdh) - Allows users to manage and navigate through a history of directories they have visited. It maintains a history file of directories and provides several commands to interact with this history.
- [cdhist](https://github.com/joknarf/cdhist) - cd history/subdir/locatedir navigation. simple cd history, alias builtin `cd` to add `cd` history, rapidily swich to already visited directories, can use `locate`, `mlocate` or `plocate` to rapidly cd to any directory
- [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of `cdr` for ZSH.
- [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
- [cheatsheet](https://github.com/0b10/cheatsheet) - Plugin to easily view, create, and edit cheatsheets.
- [check-deps](https://github.com/zpm-zsh/check-deps) - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Node.js and ZSH plugins if you are using the [zpm](https://github.com/zpm-zsh/zpm) framework.
- [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - Clone of `chruby` modified to make it easy to switch between multiple Go versions.
- [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
- [clipboard](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
- [cmaker](https://github.com/apalkk/Cmaker) - Makes using `cmake` easier.
- [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - Reports the status of commands including return code and duration.
- [cmd-time](https://github.com/TomfromBerlin/zsh-cmd-time) - Collects the execution time of commands and exports the result to a variable that can be used elsewhere. It is similar to the built-in [REPORTTIME](http://zsh.sourceforge.net/Doc/Release/Parameters.html) function, but it is also slightly different. Unlike when you set `REPORTTIME`, it considers user and sytem time, not just CPU time.
- [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) plugin.
- [code-review](https://github.com/xorkevin/code-review-zsh) - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
- [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - Counts keypresses and logs stats to [Code::Stats](https://codestats.net/).
- [codex](https://github.com/tom-doerr/zsh_codex) - Enables you to use OpenAI's powerful Codex AI in the command line.
- [coffee-time](https://github.com/gakimball/zsh-coffee-time) - Adds the `caf` alias, which runs `caffeinate -dims`. The extra flags keep everything awake: the system, the drive, and the display.
- [color-logging](https://github.com/p1r473/zsh-color-logging) - provides a really easy to use logging library with notifications for pushbullet and pushover, colorizes tools like `cat` and `ls` and provides a color library.
- [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
- [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - Colorize `man` pages.
- [colorize-functions](https://github.com/Freed-Wu/zsh-colorize-functions) - Colorizes functions for ZSH.
- [colorize](https://github.com/zpm-zsh/colorize) - Colorize the output of various programs.
- [colorls](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
- [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
- [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Enhanced colors for ZSH.
- [command-execution-timer](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
- [command-not-found (freed-wu)](https://github.com/Freed-Wu/zsh-command-not-found) - Uses the command-not-found package for ZSH to provide suggested packages to be installed if a command cannot be found.
- [command-not-found (tarrasch)](https://github.com/Tarrasch/zsh-command-not-found) - A mirror of the [oh-my-zsh](https://ohmyz.sh) [command-not-found](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/command-not-found) plugin so you don't have to include all of oh-my-zsh.
- [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
- [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
- [communism](https://github.com/victoria-riley-barnett/Communism/) - Displays a Marx quote of the day.
- [compe](https://github.com/tamago324/compe-zsh) - Add completion for [nvim-compe](https://github.com/hrsh7th/nvim-compe).
- [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
- [conda (themysciradata)](https://github.com/ThemysciraData/conda.plugin.zsh) - Adds function to provide a prompt segment for [conda](https://conda.io) and aliases for some base functions.
- [conda (wardhanisukoco)](https://github.com/wardhanisukoco/zsh-plugin-conda/) - Automatically loads `conda` and provides functions for detecting `conda` versions for use in themes.
- [conda-init](https://github.com/commiyou/conda-init-zsh-plugin) - Cleans up environment variables so [conda](https://conda.io) doesn't mess up `tmux`.
- [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) - Provides a `condaenv_prompt_info` function which returns the current `conda` environment name.
- [confer](https://github.com/SleepyBag/zsh-confer) - Tries to find program configuration files automatically so you can do things like `conf vim` to edit your `vim` configuration files.
- [containers](https://github.com/redxtech/zsh-containers) - Provides aliases and better interoperability between [podman](https://podman.io) and [docker](https://docker.com) commands based on which you have installed.
- [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - Copy and paste files in your terminal like you would in a GUI.
- [copyzshell](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
- [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
- [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
- [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh) - Automatically sends out a notification when a long running task has completed. Works with macOS and linux (if `hterm-notify` is installed).
- [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price.
- [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal).
- [cvideo](https://github.com/aubreypwd/zsh-plugin-cvideo) - Quickly compress video with `ffmpeg`.
- [cycle-fav-dirs](https://github.com/cibinmathew/cycle-fav-dirs) - A plugin to cycle through your favourite directories.
- [czhttpd](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH.
- [ddev](https://github.com/voronkovich/ddev.plugin.zsh) - A ZSH plugin for the [ddev](https://github.com/drud/ddev) tool for setting up PHP development environments.
- [declare-zsh](https://github.com/z-shell/declare-zsh) - A parser for [zinit](https://github.com/zdharma-continuum/zinit) commands in `.zshrc`. It allows you to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
- [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
- [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
- [def](https://github.com/thevinter/def) - Allows you to specify and run a default command in any directory of your choice.
- [defer](https://github.com/romkatv/zsh-defer) - Defers execution of a `zsh` command until `zsh` has nothing else to do and is waiting for user input. Its intended purpose is staged `zsh` startup. It works similarly to Turbo mode in [zinit](https://github.com/zdharma-continuum/zinit).
- [delete-prompt](https://github.com/aoyama-val/zsh-delete-prompt) - ZSH widget to delete the prompt texts within the current line. It is useful when executing pasted commands from the web or a README. A leading non-alphanumeric character + space is detected as a prompt.
- [deno (cowboyd)](https://github.com/cowboyd/zsh-deno) - Useful [deno](https://deno.land/) aliases and settings.
- [deno (tricked-dev)](https://github.com/Tricked-dev/deno-zsh-plugin) - Automatically installs [deno](https://deno.land/) to `$HOME/.deno` on startup if deno is not already installed.
- [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - Simple [oh-my-zsh](https://ohmyz.sh/) plugin for installing the chromium depot_tools. Installing this plugin will add all of the chromium depot_tools to your `$PATH` automatically.
- [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - Provides a lightweight version of Shopify's internal dev tool
- [dietpi](https://github.com/unixorn/dietpi.plugin.zsh) - Adds utilities for [dietpi](https://dietpi.com) to your `$PATH` (and includes aliases to automagically run them with `sudo`) when you log into a machine running  [dietpi](https://dietpi.com).
- [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) - Automatically installs [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) and enables its use in ZSH and `git`.
- [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
- [dirbrowse](https://github.com/giovannilupi/dirbrowse/) - Customized version of the [dirbrowse](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/dircycle) plugin in [oh-my-zsh](https://ohmyz.sh).
- [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
- [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - Enables [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
- [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack.
- [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
- [direnv](https://github.com/ptavares/zsh-direnv) - A plugin for installing and loading [direnv](https://github.com/direnv/direnv.git). Inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
- [dirrc](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into.
- [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying the dirstack info on a single line.
- [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
- [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
- [docker-aliases](https://github.com/webyneter/docker-aliases) - `Docker` aliases for everyday use.
- [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) - Show `docker` container status in your prompt.
- [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of `docker` helper scripts.
- [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
- [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
- [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
- [dot-up](https://github.com/toku-sa-n/zsh-dot-up) - Converts `...`, `....`, `.....`, etc., into `cd` commands to navigate parent directories.
- [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of [fzf](https://github.com/junegunn/fzf).
- [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - Keep your dotfiles in sync across multiple machines using `git`.
- [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
- [download](https://github.com/aubreypwd/zsh-plugin-download) - Helper to download files with `aria2c`.
- [dropbox](https://github.com/zpm-zsh/dropbox) - A [dropbox](https://www.dropbox.com/) plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
- [drupal](https://github.com/yhaefliger/zsh-drupal) - Adds aliases for common tasks and also tab-completion for `drush`. Inspired by [Artisan](https://github.com/jessarcher/zsh-artisan).
- [dune-quotes](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin.
- [duration](https://github.com/rtakasuke/zsh-duration) - Displays command duration if it exceeds a user-settable run time.
- [dwim](https://github.com/oknowton/zsh-dwim) - Attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
- [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - A port of [vim-easymotion](https://github.com/easymotion/vim-easymotion) for ZSH.
- [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
- [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history word completion).
- [edward cli](https://github.com/matthieusb/zsh-edward) - Adds smart completions and alises for [edward CLI micro-service launcher](https://github.com/yext/edward).
- [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
- [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs) - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
- [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a `ssh` connection, or X frames opened on the same host.
- [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
- [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - Configurable ZSH plugin for the excellent [emoji-fzf](https://github.com/noahp/emoji-fzf). It is heavily inspired by [emoji-cli](https://github.com/b4b4r07/emoji-cli).
- [emojis](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ASCII art emojis to your environment in convenient variables.
- [enhancd](https://github.com/b4b4r07/enhancd) - A simple tool that provides an enhanced `cd` command by memorizing all directories visited by a user and use it for the pathname resolution.
- [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
- [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`".
- [evalcache](https://github.com/mroth/evalcache) - Caches the output of a binary initialization command like `eval "$(hub alias -s)"`, to help lower shell startup time by loading from cache instead of re-running every new shell session.
- [evil-registers](https://github.com/zsh-vi-more/evil-registers) - Extends ZLE `vi` commands to remotely access named registers of the `vim` and `nvim` editors, and system selection and clipboard.
- [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa](https://the.exa.website), the modern replacement for `ls`.
- [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - Adds aliases for [exa](https://the.exa.website), a modern replacement for `ls`.
- [exa (ptavares)](https://github.com/ptavares/zsh-exa) - Installs and loads [exa](https://github.com/ogham/exa.git).
- [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - Adds aliases to make using [exa](https://github.com/ogham/exa.git) easier.
- [exa (todie)](https://github.com/todie/exa.plugin.zsh) - Integration and completions for [exa](https://the.exa.website/), a modern replacement for `ls`.
- [exa (zap-zsh)](https://github.com/zap-zsh/exa) - Overrides common commands to use exa instead.
- [exa (zplugin)](https://github.com/zplugin/zsh-exa) - replace `ls` with [ogham/exa](https://github.com/ogham/exa).
- [exa (zshell)](https://github.com/z-shell/zsh-exa) - replace `ls` with [ogham/exa](https://github.com/ogham/exa).
- [exa-ls (zpm-zsh)](https://github.com/zpm-zsh/ls) - Zsh plugin for ls.
- [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) - Adds aliases so that you can use [exa](https://the.exa.website) as a drop-in replacement for `ls` and `tree`.
- [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
- [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
- [expand](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases, incorrect spellings and phrases, globs, history expansion and $parameters with the spacebar key.
- [expander](https://github.com/ianthehenry/zsh-expander) - A `zle` widget that allows you to write custom expanders and select them with [fzf](https://github.com/junegunn/fzf).
- [explain-shell (brokentoaster)](https://github.com/brokentoaster/zsh-explainshell) - Uses [lynx](https://lynx.browser.org/) to look up the current command line on [explainshell.com](https://explainshell.com).
- [explain-shell (gmatheu)](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
- [extend-history](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding the exit code for each command in the history.
- [ez-cmd](https://github.com/akgarhwal/ez-cmd) - Simplifies and streamlines common command-line tasks by providing easy-to-use shortcuts and aliases.
- [ez-compinit](https://github.com/mattmc3/ez-compinit) - Wraps `compinit`, queueing up calls to `compdef`, and hooking the real `compinit` call to an event that runs at the end of your `.zshrc`. That way you get all the benefits of calling `compinit` early without any of the downsides.
- [eza (clavelm)](https://github.com/clavelm/eza-omz-plugin) - Replaces `ls` with [eza-community/eza](https://github.com/eza-community/eza).
- [eza (mohamedelashri)](https://github.com/MohamedElashri/eza-zsh) - Adds aliases for [eza](https://github.com/eza-community/eza), a modern replacement for `ls`.
- [eza (twopizza9621536)](https://github.com/twopizza9621536/zsh-eza) - Replaces `ls` with [eza-community/eza](https://github.com/eza-community/eza).
- [eza (z-shell)](https://github.com/z-shell/zsh-eza) - Replaces `ls` with [eza-community/eza](https://github.com/eza-community/eza).
- [eza-ls](https://github.com/birdhackor/zsh-eza-ls-plugin) - Adds aliases allowing [eza(https://github.com/eza-community/eza)], to act as a drop-in replacement for `ls` and `tree`.
- [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using `F1` to `F12` keys.
- [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of [oh-my-zsh](https://ohmyz.sh).
- [fast-alias-tips](https://github.com/decayofmind/zsh-fast-alias-tips) - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips](https://github.com/djui/alias-tips). Active fork of [sei40kr/zsh-fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips).
- [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) - Optimized and improved `zsh-users/zsh-syntax-highlighting` – better response times, switchable highlight themes.
- [fastcache](https://github.com/QuarticCat/zsh-fastcache) - Caches command output to improve shell startup time.
- [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) plugin that makes it really easy to add and recall named favorites of your important directories.
- [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
- [fd-plugin](https://github.com/MohamedElashri/fd-zsh) - Adds aliases for [fd](https://github.com/sharkdp/fd), a modern replacement for `find`.
- [fd](https://github.com/aubreypwd/zsh-plugin-fd) - Use [fzf](https://github.com/junegunn/fzf) to browse directories.
- [figures](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
- [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
- [firebase (seqi)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
- [firmine](https://github.com/GNUWood/firmine) - Includes decorators for user@hostname, date & time, current directory and [Kaomoji](https://en.wikipedia.org/wiki/Kaomoji) icons for last command exit status.
- [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
- [flatpak](https://github.com/claymorwan/Flatpak-zsh-plugin) - Adds aliases for [Flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html).
- [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
- [fnm (dominik-schwabe)](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) if it is missing.
- [fnm (wintermi)](https://github.com/wintermi/zsh-fnm) - Helper plugin for the fast and simple Node.js version manager [fnm](https://github.com/Schniz/fnm).
- [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` which takes advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf).
- [functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
- [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
- [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) - Adds fuzzy search for directories warped with the [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) plugin.
- [fz](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among directories in your history.
- [fzf (gimbo)](https://github.com/gimbo/fzf.zsh) - Helpers for using [fzf](https://github.com/junegunn/fzf) in ZSH. Requires [brew.sh](https://brew.sh).
- [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/) - Enables [fzf](https://github.com/junegunn/fzf) history and file searches.
- [fzf-copyq-clipboard](https://github.com/magidc/fzf-copyq-clipboard-zsh-plugin) - Add [fzf](https://github.com/junegunn/fzf) support for [CopyQ](https://hluk.github.io/CopyQ/).
- [fzf-dir-navigator](https://github.com/KulkarniKaustubh/fzf-dir-navigator) - This is a cool and user-friendly directory navigation plugin for `zsh` using `fzf` that allows the user to switch to any directory from anywhere and to anywhere. It also maintains a history of recently visited directories. Additionally, you can use hotkeys to move back and forth between directories in the shell session.
- [fzf-fasd](https://github.com/wookayin/fzf-fasd) - Integrates [fzf](https://github.com/junegunn/fzf) and [fasd](https://github.com/clvv/fasd) --- tab completion of `z` with `fzf`'s fuzzy search!
- [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat) and [fd](https://github.com/sharkdp/fd). Falls back to `find` and `cat`. Searches in the local tree of subdirectories for files.
- [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - Replaces `Ctrl+R` with an [fzf](https://github.com/junegunn/fzf)-driven history search that includes date/times.
- [fzf-it](https://github.com/micakce/fzf-it) - Make any command interactive wrapping it with [fzf](https://github.com/junegunn/fzf) functionality.
- [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
- [fzf-packagemanager](https://github.com/goarano/zsh-fzf-packagemanager) - Adds commands for installing tools via various package managers using [fzf](https://github.com/junegunn/fzf). Supports `apt`, `brew` & `dnf`.
- [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better handling of passwords using [fzf](https://github.com/junegunn/fzf) and [pass](https://www.passwordstore.org/).
- [fzf-plugin](https://github.com/Atlas34/fzf-plugin) - [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)'s `fzf` plugin extracted so it can be used easily with other plugin managers.
- [fzf-prezto](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) has been installed and enables its auto-completion and key-bindings. This plugin works as a Prezto `zstyle` configuration option.
- [fzf-tab-widgets](https://github.com/tom-power/fzf-tab-widgets) - Adds widgets for [fzf-tab](https://github.com/Aloxaf/fzf-tab).
- [fzf-tab](https://github.com/Aloxaf/fzf-tab) - Replace ZSH's default completion selection menu with [fzf](https://github.com/junegunn/fzf).
- [fzf-tools](https://github.com/happycod3r/fzf-tools) - Provides functions, aliases and key-bindings for commands such as `alias`, `find`, `ls`, `man`, `printenv` that are designed to enhance your command-line workflow by making them to default to filtering through [fzf](https://github.com/junegunn/fzf), allowing you to quickly find files, search & run commands from history, run scripts of many supported types, browse `git` commits, and more.
- [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - Provides functions to kill proceses and find in path with [fzf](https://github.com/junegunn/fzf).
- [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf).
- [fzfsh](https://github.com/ethan605/fzfsh) - Add [fzf](https://github.com/junegunn/fzf) plugins for `chezmoi`, `docker`, `git`, `kubectl` and `pass`.
- [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations.
- [gcloud-project](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Projects.
- [gcloud](https://github.com/wintermi/zsh-gcloud) - Finds the installed gcloud sdk and sources the zsh file there, along with the zsh completions file.
- [gdbm](https://github.com/zdharma-continuum/zgdbm) - Adds GDBM as a plugin.
- [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - Adds some aliases and functions to work with Gentoo Linux.
- [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
- [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
- [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's npm package version.
- [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
- [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading the jQuery library from [code.jquery.com](https://code.jquery.com).
- [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use [zeus](https://github.com/burke/zeus) with normal rails commands.
- [gimbo-git](https://github.com/gimbo/gimbo-git.zsh) - A subset of the [oh-my-zsh](https://ohmyz.sh/) [git plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/git/git.plugin.zsh) aliases, plus some new aliases, plus a few handy functions.
- [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage [Go](https://golang.org/) installations with [gimme](https://github.com/travis-ci/gimme/).
- [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run `git pull`, `git add`, `git commit` and `git push` with one keystroke.
- [git-add-remote](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your `git` fork.
- [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of [oh-my-zsh](https://ohmyz.sh).
- [git-aliases (peterhurford)](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
- [git-aliases (remino)](https://github.com/remino/omz-plugin-git-aliases) - Aliases all `git xyz` commands to `gxyz`. Also aliases `g` to `git`.
- [git-arc](https://github.com/jlduran/git-arc-oh-my-zsh-plugin) - Adds aliases and functions for [git-arc](https://github.com/freebsd/freebsd-src/tree/main/tools/tools/git), a FreeBSD development tool.
- [git-branches](https://github.com/Schroefdop/git-branches) - Makes a menu of `git` branches you can switch to without having to type long branch names.
- [git-check](https://github.com/git-girl/git-check) - Adds a ZSH hook to check if the origin of the current branch has changes to local in the background and sends a notification.
- [git-clean-branch](https://github.com/gobriansteele/git-clean-branch) - Cleans up dead `git` branches.
- [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
- [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
- [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - Adds short aliases for the `git-flow` commands.
- [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [fzf](https://github.com/junegunn/fzf).
- [git-gen](https://github.com/sharif3271/git-gen) - Handle `git` bulk branch delete and create operations.
- [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. [fzf](https://github.com/junegunn/fzf), completion, preview integrated.
- [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) - This function will return true or false depending on if it finds out your `git` repo is dirty or not.
- [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
- [git-lfs](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the `git-lfs` commands.
- [git-patch](https://github.com/marvinroman/oh-my-zsh-git-patch-plugin) - Adds custom functions and aliases to the oh-my-zsh `git` plugin.
- [git-plugin (dark-kitt)](https://github.com/dark-kitt/zsh-git-plugin) - `git` integration that displays the current directory and `git` branch.
- [git-plugin (rcruzper)](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
- [git-prompt-enhanced](https://github.com/LFabre/zsh-git-prompt-enhanced) - Provides a more granular information about a `git` repository.
- [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
- [git-prune (diazod)](https://github.com/diazod/git-prune) - Allows you to delete all branches that are already merged in your local `git` repository and/or that were merged in your remote origin `git` repository.
- [git-prune (seinh)](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches in a `git` repository.
- [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
- [git-secret](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a `git` repository.
- [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
- [git-smart-commends-wrapper](https://github.com/jelek21/omz-git-smart-commands) - Wraps [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) to make it compatible with the [oh-my-zsh](https://ohmyz.sh) plugins system.
- [git-status](https://github.com/AyoubMounim/zsh-git-status/) - Exposes functions with information about the current `git` repository.
- [git-switch-branch-skim](https://github.com/okhiroyuki/zsh-git-switch-branch-skim) - Allows you to switch `git` branches with [skim](https://github.com/lotabout/skim)
- [git-sync](https://github.com/caarlos0-graveyard/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
- [git-tree](https://github.com/dehlen/git-tree-zsh) - [fzf](https://github.com/junegunn/fzf) powered `git worktree` helper.
- [git-worktree](https://github.com/alexiszamanidis/zsh-git-worktree) - Wraps some `git worktree` operations for simplicity and productivity. Includes [fzf](https://github.com/junegunn/fzf) tooling.
- [git-worktrees](https://github.com/egyptianbman/zsh-git-worktrees) - Makes `git` worktrees more functional. Includes tab completions.
- [git](https://github.com/davidde/git) - Replacement for the stock [oh-my-zsh](https://ohmyz.sh/) `git` plugin. Provides quite a few useful aliases and functions. The motivation to replace the default plugin stems from the fact that it comes with some inconsistencies that make a few popular commands rather unintuitive, so this plugin makes the aliases consistent.
- [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - Adds command to `git clone` a repository and `cd` into the resulting directory.
- [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
- [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of the [oh-my-zsh](https://ohmyz.sh/) `gitfast` plugin.
- [gitgo](https://github.com/ltj/gitgo) - Open a GitHub/GitLab repository in your browser from the command line (macOS only).
- [github-folders](https://github.com/buzuloiu/zsh-github-folders) - Organizes your GitHub checkouts for you.
- [github](https://github.com/shakir-abdo/zsh-github-plugin) - Fork of the original [GitHub plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) embedded in [oh-my-zsh](http://ohmyz.sh/).
- [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
- [gitio (denysdovhan)](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
- [gitio (nicolodiamante)](https://github.com/nicolodiamante/gitio) - Uses [git.io](https://git.io/) to shorten `git` urls.
- [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) -  Makes it easy to show your `git` status in your prompt.
- [gitsync](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
- [goenv (bbenne10)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
- [goenv (cda0)](https://github.com/CDA0/zsh-goenv/) - Plugin for installing, updating and loading `goenv`.
- [goenv (heyvito)](https://github.com/heyvito/goenv.zsh) - Automatically reads `.goenv` files in the current directory and sets `GOPRIVATE` environment variables.
- [going_places](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
- [golang](https://github.com/wintermi/zsh-golang) - Adds tooling for the Go programming language toolchain.
- [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) - Launch golinks from your terminal.
- [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
- [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt and decrypt files or directories in place.
- [gpg](https://github.com/marvinroman/oh-my-zsh-gpg-plugin) - Adds helpful aliases for using `gpg`.
- [gpt](https://github.com/antonjs/zsh-gpt) - Enable querying ChatGPT from the command line.
- [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
- [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for `grunt`.
- [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
- [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm).
- [gtr](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in `git` using the tag name **release-YYYY-MM-DD-HH-MM*- and headline **Release YYYY-MM-DD HH:MM**.
- [guish](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
- [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/).
- [gunstage](https://github.com/LucasLarson/gunstage) - There are at least eight ways to unstage files in a `git` repository. This is a command-line shell plugin for undoing `git add`.
- [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - A `gvm` (Go version manager) plugin for ZSH.
- [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for `gvm` (Groovy enVironment Manager).
- [hab](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
- [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a random hacker quote when you open a terminal.
- [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - Adds some convenience aliases for [hadoop](https://hadoop.apache.org/) functions.
- [haiku](https://github.com/alesr/oh-my-zsh-haiku-plugin) - Prints a haiku promoting work-life balance and stress management once every 24 hours when the terminal is open.
- [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) projects.
- [hangul](https://github.com/gomjellie/zsh-hangul) - Auto correct hangul(한글, korean) to English when it was supposed to be typed in English. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
- [hbt](https://github.com/lzambarda/hbt) - Heuristic ZSH suggestion system based on past command usage.
- [hebzsh](https://github.com/admons/hebzsh) - If a command is not found as typed in Hebrew, translates the command as if it was typed on a keyboard with a US English layout and tries again.
- [help](https://github.com/Freed-Wu/zsh-help) - Colorizes the output of commands run with `--help`.
- [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
- [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
- [hist-delete](https://github.com/p1r473/zsh-hist-delete-fzf/) - Delete history items from zsh's [fzf](https://github.com/junegunn/fzf) Ctrl+R history search.
- [hist](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
- [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
- [historikeeper](https://github.com/stiliajohny/historikeeper) - Captures history in a database.
- [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer) - Enhances history search with more interaction and a multiline selection menu. Requires Node.js.
- [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
- [history-here](https://github.com/leonjza/history-here) - Binds `^G` to quickly toggle the current shell history file location.
- [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - Captures the `PageUp` key and uses `dialog` to open a popup menu with the history, so the user can interactively navigate through it and pick the history line to bring back to the prompt.
- [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
- [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
- [history-sync (vitobotta)](https://github.com/vitobotta/zsh-history-sync/) - Syncs your ZSH history across computers using a `git` private repository. Uses `openssl` to encrypt the history.
- [history-sync (wulfgarpro)](https://github.com/wulfgarpro/history-sync) - An [oh-my-zsh](https://ohmyz.sh/) plugin for [GPG](https://www.gnupg.org/) encrypted, Internet synchronized ZSH history using `git`.
- [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
- [hitokoto](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
- [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) instances.
- [homebrew](https://github.com/digitalraven/omz-homebrew) - Plugin for [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
- [hooks](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
- [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
- [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
- [hub](https://github.com/soraliu/zsh-hub) - ZSH plugin for forking model.
- [hypnosnek](https://github.com/josephcourtney/hypnosnek) - Simple utilities with p10k integration for managing `python` environments.
- [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
- [incsearch](https://github.com/aoyama-val/zsh-incsearch) - Friendlier `vim` mode for ZSH. Moves cursor with incremental search within current line.
- [ing](https://github.com/rummik/zsh-ing) - Streamlined `ping` output.
- [instant-repl](https://github.com/jandamm/instant-repl.zsh) - Activate a REPL for any command in your current ZSH session.
- [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
- [iosctl](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator.
- [ipip](https://github.com/SukkaW/zsh-ipip) - Plugin for [IPIP](https://en.ipip.net).
- [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
- [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
- [iterm-tmux-color-tabs](https://github.com/remino/omz-plugin-iterm2-tmux-color-tabs) - Every new `tmux` tab opened in iTerm2 will have the next colour from the default or specified palette.
- [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
- [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
- [iterm2-shell-integration](https://github.com/gnachman/iterm2-shell-integration) - Shell integration and utilities for iTerm2.
- [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
- [iterm2](https://github.com/laggardkernel/zsh-iterm2) - Packs iTerm 2's ZSH integration scripts into a ZSH plugin to avoid polluting your $HOME directory, with a negligible time increase of only 2ms.
- [iwd](https://github.com/zshzoo/iwd) - Similar in concept to `$PWD`, this ZSH plugin saves your initial working directory in `$IWD` for easy returns to the starting point of your session.
- [jabba](https://github.com/2m/zsh-jabba) - Adds shell integration code and completions for the [jabba](https://github.com/shyiko/jabba) Java version manager.
- [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
- [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
- [jdk-switch](https://github.com/LockonS/jdk-switch) - Switches between jdk versions. Works on macOS and Linux.
- [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
- [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of [jEnv](http://www.jenv.be/).
- [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
- [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRA tickets from the command line.
- [jq](https://github.com/reegnz/jq-zsh-plugin) - Interactively build [jq](https://stedolan.github.io/jq/) expressions. Also supports [gojq](https://github.com/itchyny/gojq). Requires [fzf](https://github.com/junegunn/fzf).
- [jrgit](https://github.com/jrocha-dev/ohmyzsh-plugin-jrgit) - Provides a suite of functions to streamline the Git user experience. It includes features for installing and configuring Git, handling large files with Git LFS, improving diff outputs, and managing credentials and keys securely.
- [jvm](https://github.com/mgryszko/jvm) - Allows selection of JDK on macOS.
- [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
- [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) - Adds aliases and tab completions for [k3d](https://k3d.io/).
- [kctl](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
- [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
- [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for [oh-my-zsh](https://ohmyz.sh).
- [kiwi](https://github.com/fruitydog/kiwi.zsh-theme) - Dog-themed, includes `git` status and last command exit status decorators.
- [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
- [kube-aliases](https://github.com/Dbz/kube-aliases) - Adds functions and aliases to make working with `kubectl` more pleasant.
- [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for `kubectl` that adds current context and namespace.
- [kubecolor (devopstales)](https://github.com/devopstales/zsh-kubecolor) - Adds aliases for the `kubecolor` command.
- [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - Simplify and colorize the output of `kubectl get events -w`
- [kubecolor (trejo08)](https://github.com/trejo08/kubecolor-zsh) - Prints colorized outputs from  `kubectl`. Includes helper functions.
- [kubeconfig-mgr](https://github.com/yhlooo/zsh-kubeconfig-mgr) - Makes managing multiple kubeconfig files easier.
- [kubectl-config-switcher](https://github.com/chmouel/kubectl-config-switcher/) - Switch between config files in `~/.kube` via the `KUBECTL` environment variable.
- [kubectl-prompt](https://github.com/superbrothers/zsh-kubectl-prompt) - Display information about the kubectl current context and namespace in your ZSH prompt. Creates `ZSH_KUBECTL_CONTEXT`, `ZSH_KUBECTL_NAMESPACE`,`ZSH_KUBECTL_PROMPT` and `ZSH_KUBECTL_USER` variables you can use to customize your prompt.
- [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing `kubectl`.
- [kubectlenv](https://github.com/rafalmasiarek/oh-my-zsh-kubectlenv-plugin) - Easily switch between multiple `kubectl` versions.
- [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - Installs and loads [kubectx](https://github.com/ahmetb/kubectx).
- [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - Automatically installs [kubectx](https://github.com/ahmetb/kubectx) and `kubens`.
- [kubernetes](https://github.com/Dbz/zsh-kubernetes) - Add [kubernetes](https://kubernetes.io) helper functions and aliases.
- [lacrimae](https://github.com/caIamity/lacrimae) - Prints a line from a collection of chants.
- [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) without having to type lando to access them.
- [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) commands.
- [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)'s workspace.
- [laravel (baliestri)](https://github.com/baliestri/laravel.plugin.zsh) - Plugin for skiping the `php` command when running `artisan` commands and `./sail` or `./vendor/bin/sail` when running `sail` commands.
- [laravel (crazybooot)](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for [Laravel](https://laravel.com/) 5, 5.1, 5.2 & 5.3.
- [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - Adds aliases for [Laravel](https://laravel.com/) 6.
- [laravel-sail](https://github.com/ariaieboy/laravel-sail) - Adds shortcuts for `sail` commands.
- [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) commands.
- [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - Keeps track of the last used working directory globally and per [tmux](https://github.com/tmux/tmux) session and automatically jumps into it for new shells.
- [last-working-directory](https://github.com/mdumitru/last-working-dir) - Broken out copy of the version in [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
- [lazy-load](https://github.com/goarano/zsh-lazy-load) - Lazy load tab completions only when you actually need them.
- [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
- [learn](https://github.com/MenkeTechnologies/zsh-learn) - Learning collection in MySQL/MariadB to save, query and quiz everything you learn.
- [lesaint-git](https://github.com/lesaint/lesaint-git) - Replacement `git` plugin for [oh-my-zsh](https://ohmyz.sh)-compatible frameworks.
- [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for [oh-my-zsh](https://ohmyz.sh).
- [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - Adds scripts for [liferay](https://github.com/liferay/liferay-portal) development.
- [linkfile](https://github.com/JaumeRF/linkfile-zsh) - Add shortcuts to your favorite directories.
- [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - Outputs a random Linus Torvalds rant when opening a terminal.
- [listbox](https://github.com/gko/listbox) - Listbox element for shell.
- [llm-suggestions](https://github.com/stefanheule/zsh-llm-suggestions) - Type something in English at the prompt, hit a definable key, and it uses LLM to generate a command line for you.
- [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
- [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
- [ls (twopizza9621536)](https://github.com/TwoPizza9621536/zsh-ls) - Adds some more aliases for `ls`.
- [ls (zpm-zsh)](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
- [lsd (tankeryang)](https://github.com/tankeryang/zsh-lsd) - Replaces `ls` and `tree` commands with [lsd](https://github.com/Peltoche/lsd).
- [lsd (wintermi)](https://github.com/wintermi/zsh-lsd) - Override `ls` and `tree` commands with [lsd](https://github.com/Peltoche/lsd).
- [lsd (z-shell)](https://github.com/z-shell/zsh-lsd) - Replaces `ls` with [lsd](https://github.com/Peltoche/lsd).
- [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts.
- [lux](https://github.com/pndurette/zsh-lux) - ZSH plugin to toggle the light & dark modes of macOS, iTerm 2, Visual Studio Code and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes a `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
- [mac-packaging](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with [Munki](https://www.munki.org/munki/).
- [macos (joow)](https://github.com/joow/macos) - A ZSH plugin for macOS.
- [macos (zshzoo)](https://github.com/zshzoo/macos) - ZSH goodies for macOS users.
- [macos-theme](https://github.com/gakimball/zsh-macos-theme) - Adds the theme command, which toggles between light and dark mode in macOS. Requires [lux](https://github.com/pndurette/zsh-lux) plugin.
- [mage2docker](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
- [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - Adds `m2` function to run magento binary, adds tab completions.
- [magic-enter](https://github.com/zshzoo/magic-enter) - Make your enter key magical by binding a ZSH command to it.
- [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
- [markedit](https://github.com/zakariaGatter/MarkEdit) - Mark files and edit them with autocompletion for existing marks.
- [markgate](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
- [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the [oh-my-zsh](https://ohmyz.sh/) maven plugin.
- [media-sync](https://github.com/redxtech/zsh-media-sync) - A plugin to facilitate copying media between two `rclone` locations.
- [mercurial](https://github.com/hcgraf/zsh-mercurial) - Extracted from [oh-my-zsh](https://ohmyz.sh) so you can use it without the rest of oh-my-zsh.
- [mfunc](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
- [mise](https://github.com/wintermi/zsh-mise) - Plugin for [mise](https://mise.jdx.dev/) (formerly called rtx) a fast polyglot version manager, replacing tools like `nvm`, `nodenv`, `rbenv`, `rvm`, `chruby`, `pyenv`, etc.
- [mkarch](https://github.com/0xRZ/mkarch) - ZSH plugin that allows you to create archives using multiple different compression formats.
- [mkcd](https://github.com/marvinroman/oh-my-zsh-mkcd-plugin) - Allows user to create a directory and if successful, `cd` into it afterward.
- [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and `vi` mode.
- [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
- [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
- [more-hooks-for-git](https://github.com/capsulescodes/more-hooks-for-git) - Adds extra hooks for `git add`, `git diff` and `git status`.
- [mouse-status](https://github.com/gryffyn/mouse-status) - Changes mouse color based on status code, uses libratbag.
- [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - [Metasploit](https://www.metasploit.com/) handler plugin for starting handlers easily.
- [multi-evalcache](https://github.com/rwwiv/multi-evalcache) - Cache multiple eval loads to improve startup time, inspired by [mroth/evalcache](https://github.com/mroth/evalcache).
- [multi-sshacc](https://github.com/harvey103565/git-multi-sshacc-asst) - Manages multiple `git` with different `ssh` keys per repo.
- [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - Allows fast switching between `maven` configurations.
- [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
- [myservice](https://github.com/jarlor/zsh-myservice) - Designed to help you manage custom systemd services and Docker containers more conveniently. This plugin provides user-friendly commands to list and check the status of your custom services and Docker containers straight from your command line.
- [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Adds color for `mysql` tables.
- [mysql-login](https://github.com/remino/omz-plugin-mysql-alias) - Adds alias for MySQL with login path.
- [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with `mysql`.
- [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
- [namelink](https://github.com/jthat/zsh-namelink) - Provides an automatically synchronized mapping of filesystem entries (typically symbolic links) in a set of directories to their counterparts in the named directory hash.
- [navi](https://github.com/icatalina/zsh-navi-plugin/) - Plugin for [navi](https://github.com/denisidoro/navi).
- [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) - Adds `htop`-like kill, directory bookmarks browser, a multi-word incremental history searcher and more.
- [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) -  Generates file from template.
- [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) - Spins up a new WordPress site using Valet.
- [nhl-schedule](https://github.com/Matt561/zsh-nhl-schedule) - Retrieves and displays the NHL schedule.
- [nice-exit-code](https://github.com/bric3/nice-exit-code) - Maps exit status codes to human readable strings.
- [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
- [nnvm](https://github.com/torifat/nnvm) - auto-switches node versions based on `.nvmrc`. Requires [n](https://github.com/tj/n).
- [no-ps2](https://github.com/romkatv/zsh-no-ps2) - When this plugin is used, Enter inserts a newline if the typed command is incomplete. No PS2!
- [nobility](https://github.com/Twilight4/nobility) - An organized colletion of shell modules designed to streamline your pentesting workflow by leveraging shell integrations such as autocompletion and prefilling, optimizing the productivity of your work and liberatating you from the hassle of juggling notes, endless copying and pasting, and tedious command editing.
- [node-env-installer](https://github.com/shiro-saber/node-env-installer) - Uses `nvm` to install new versions and modules for the current project.
- [node-path](https://github.com/andyrichardson/zsh-node-path) - Automatically adds the `npm` bin of your current directory to your `$PATH`.
- [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's Node.js plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
- [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for `nodenv` in your working directory and loads it when found.
- [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
- [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv) - Installs, updates and loads `nodenv`. Inspired by [zsh-rbenv](https://github.com/Meroje/zsh-rbenv).
- [nodo](https://github.com/nicolodiamante/nodo) - This plugin helps you prevent `node_modules` directories from filling your iCloud storage by un-syncing the directory or can save even more space by removing all `node_modules` directories within the chosen root directory. This is particularly useful for cleaning up a project that has multiple `node_modules` trees
- [nohup](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
- [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
- [notenote](https://github.com/DrgnFireYellow/notenote/) - Makes it easy to take notes.
- [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - Inspired by [terminal_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
- [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH.
- [notify (luismayta)](https://github.com/luismayta/zsh-notify) - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
- [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
- [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin) - Adds `npm` aliases. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
- [npm (zfben)](https://github.com/zfben/zsh-npm) - Use `n` as `npm` aliases with `noglob` prefix and more. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
- [npms](https://github.com/torifat/npms) - Utility powered by [fzf](https://github.com/junegunn/fzf) for using npm scripts interactively. Requires [fzf](https://github.com/junegunn/fzf) and [jq](https://stedolan.github.io/jq/).
- [nvim-appname](https://github.com/mehalter/zsh-nvim-appname) - Maintain multiple Neovim configurations with `NVIM_APPNAME` with full tab completion of available flags, available neovim applications, and neovim arguments/flags. Requires neovim v0.9+
- [nvim-switcher](https://github.com/dacarey/zsh-nvim-switcher)- Manages switching between `nvim` distributinons such as [Lazyvim](https://www.lazyvim.org/), [kickstart](https://github.com/nvim-lua/kickstart.nvim) or a home made configuration.
- [nvm-auto-use (jrr997)](https://github.com/jrr997/zsh-nvm-auto-use) - Automatically manages your Node.js versions with [nvm](https://github.com/nvm-sh/nvm) based on your current directory.
- [nvm-auto-use (tomsquest)](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
- [nvm-deferred](https://github.com/davidparsson/zsh-nvm-deferred) - Defers loading of the `nvm` oh-my-zsh plugin using [zsh-defer](https://github.com/romkatv/zsh-defer) to speed up shell startup.
- [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy) - Plugin for lazy loading of oh-my-zsh's **nvm*- plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
- [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
- [oath](https://github.com/alexdesousa/oath) - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
- [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
- [oh-my-gpt](https://github.com/vicotrbb/oh-my-gpt) - Provides an easy-to-use interface for interacting with OpenAI's GPT models directly from your terminal. It allows you to send queries, analyze files, and get AI-powered assistance for various tasks.
- [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
- [oh-my-posh-manager](https://github.com/wintermi/zsh-oh-my-posh) - Manages the oh-my-posh theme engine, along with providing a default powerline-like theme.
- [oh-my-tmux-manager](omt-manager) - Lets you easily manage your tmux configurations.
- [ollama](https://github.com/plutowang/zsh-ollama-command) - Integrates the OLLAMA AI model with [fzf](https://github.com/junegunn/fzf) to provide intelligent command suggestions based on user input requirements.
- [omz-full-autoupdate](https://github.com/Pilaton/OhMyZsh-full-autoupdate) - Automatically update [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) plugins and themes.
- [omz-git](https://github.com/aeons/omz-git) - [Oh-My-ZSH](https://ohmyz.sh/)'s [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) plugin re-packaged to be standalone.
- [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) - Gives you the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) themes without requiring everything else that comes with oh-my-zsh
- [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
- [open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
- [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
- [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
- [opera-gx](https://github.com/troykelly/oh-my-zsh-opera-gx) - Enables starting Opera GX with a specific user profile by using the `opgx` command followed by the profile's name. The plugin also implements autocompletion for profile names.
- [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
- [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
- [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - Configures proxy environment variables based on macOS's system preferences.
- [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on a macOS install.
- [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
- [paci](https://github.com/iloginow/zsh-paci) - Plugin for arch linux package managers.
- [pack](https://github.com/fourdim/zsh-pack/) - Pack your source code with ZSH.
- [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) - Easy installing of any Node modules inside the plugin directory, exposing their binaries via shims (i.e.: forwarder scripts) created automatically by [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) annex.
- [packer](https://github.com/BreakingPitt/zsh-packer) - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
- [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
- [passwordless-history](https://github.com/jgogstad/passwordless-history) - Keeps passwords from entering your command line history.
- [path-ethic](https://github.com/sha1n/path-ethic) - Helps manage your `$PATH` quickly and easily. Doesn't touch your existing `.zshrc`, `.zprofile`, but adds on top of your existing environment instead.
- [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
- [peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing `ctrl+R`.
- [penmux](https://github.com/mfulz/zsh-penmux) - A session manager plugin meant to be used for penetration testing sessions and tracking the terminal sessions to be used in reports.
- [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - Aliases and functions for the lazy penetration tester.
- [per-directory-history](https://github.com/jimhester/per-directory-history) - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
- [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
- [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - Installs [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
- [pew](https://github.com/shosca/zsh-pew) - Sets up and manages Python virtualenvs using [pew](https://github.com/berdario/pew), automatically switches virtualenvs as you move directories.
- [pg](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with [PostgreSQL](https://www.postgresql.org/).
- [ph-marks](https://github.com/lainiwa/ph-marks) - Bookmark pornhub videos from your terminal.
- [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) if an rc-file is present in a directory.
- [php-version-switcher](https://github.com/Akollade/php-version-switcher.plugin.zsh) - Changes php versions if a `.php-version` file is found.
- [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
- [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
- [pins](https://github.com/mehalter/zsh-pins) - ZSH plugin for pinning directories. Like a CLI folder bookmark manager with tab completions.
- [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct Python virtualenvs so they don't conflict with any other python requirements on your system.
- [pip-env](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a `pipenv` project.
- [pipe](https://github.com/pipe-felipe/zsh-pipe-plugin) - Includes `docker` and package-related scripts.
- [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - Automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
- [pipenv (sudosubin)](https://github.com/sudosubin/zsh-pipenv) - Enables `pipenv`'s `$PATH` and adds completions.
- [pipx](https://github.com/thuandt/zsh-pipx) - Autocompletions for [pipx](https://github.com/pypa/pipx).
- [pkenv](https://github.com/ptavares/zsh-pkenv) - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git).
- [plenv](https://github.com/TwoPizza9621536/zsh-plenv) - Plugin for the perl [plenv](https://github.com/tokuhirom/plenv) version manager based on jenv.
- [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
- [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
- [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
- [plugin](https://github.com/darrenbutcher/plugin) - Creates custom [oh-my-zsh](https://ohmyz.sh) plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
- [pnpm (baliestri)](https://github.com/baliestri/pnpm.plugin.zsh) - Adds useful aliases for many common [pnpm](https://pnpm.io/) commands. Includes tab-completions.
- [pnpm (leizhenpeng)](https://github.com/Leizhenpeng/zsh-plugin-pnpm) - Adds useful aliases for common [pnpm](https://pnpm.io/) commands.
- [pnpm (mat2ja)](https://github.com/mat2ja/pnpm.plugin.zsh) - Better [pnpm](https://pnpm.io/) aliases.
- [pnpm (ntnyq)](https://github.com/ntnyq/omz-plugin-pnpm) - Adds useful aliases for common [pnpm](https://pnpm.io/) commands.
- [poetry (darvid)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)-created python virtualenvs.
- [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
- [popman](https://github.com/jdsee/popman) - Ever found yourself in the middle of composing a long command and needing to check a man page? Popman lets you instantly pop open a man page for any command you're typing and jump right back to where you left off, making your command-line experience smoother and more efficient.
- [portal](https://github.com/anasouardini/portal/) - A very basic script for jumping to/from paths without having to do write the whole path, open multiple terminal sessions or do a file system search using [fzf](https://github.com/junegunn/fzf). Heavily inspired by [Z](https://github.com/rupa/z).
- [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
- [ppsmon](https://github.com/mzpqnxow/ppsmon) - Reads `/sys/class/net/$interface/` to keep track of packet transmission rates. It stores the current rate to a file in the RAM backed filesystem where it can be easily accessed for display in a shell-prompt. Linux-only due to use of `/sys`.
- [pr-cwd](https://github.com/zpm-zsh/pr-cwd) - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
- [pr-eol](https://github.com/zpm-zsh/pr-eol) - Displays an EOL symbol which can be embedded in the prompt.
- [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
- [pr-git](https://github.com/zpm-zsh/pr-git) - Creates a global variable with `git` status information that can be displayed in prompts.
- [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
- [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - Creates an environment variable which can be used to display background job information in a custom prompt.
- [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display Node.js information in a custom prompt.
- [pr-return](https://github.com/zpm-zsh/pr-return) - Plugin for ZSH which displays the exit status of the last command run.
- [pr-user](https://github.com/zpm-zsh/pr-user) - Creates a global variable that can be used in prompts.
- [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
- [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
- [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - Converts raw seconds into human-readable strings.
- [prettyping](https://github.com/unixorn/prettyping) - Adds a wrapper around the standard ping tool with the objective of making the output prettier, more colorful, more compact, and easier to read.
- [prezto-last-working-dir](https://github.com/JoniVanderheijden/prezto-last-working-dir) - Keeps track of the last used working directory and automatically jumps into it for new shells, unless the starting directory is not `$HOME`. Includes a `lwd` alias.
- [print-alias](https://github.com/brymck/print-alias) - Prints commands with aliases expanded whenever you use an alias at the command line.
- [printc](https://github.com/philFernandez/printc) - Allows you to print in any color in the RGB space via a simple `printc` call.
- [printdocker](https://github.com/elvitin/printdocker-zsh-plugin) - Pretty print [docker](https://docker.com) objects.
- [profile-secrets](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
- [project (gko)](https://github.com/gko/project) - Create node/python/ruby projects both locally and on GitHub (private or public repository).
- [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
- [projen](https://github.com/p6m7g8/p6-zsh-projen-plugin) - Adds aliases for [projen](https://github.com/projen/projen).
- [prompt-dir-perms](https://github.com/xPMo/zsh-prompt-dir-perms) - Creates a segment displaying the permissions of the current directory you can use in your ZSH prompt.
- [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator) - Generates custom themes. Some generated themes require powerline-compatible fonts.
- [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
- [proxy](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
- [psgrep](https://github.com/voidzero/omz-plugin-psgrep/) - Makes `ps grep` hide its own process from the results of a `ps aux | grep`.
- [purge-history-secrets](https://github.com/jotasixto/purge-history-secrets) - Uses [gitleaks](https://github.com/gitleaks/gitleaks) to periodically scan your ZSH history for secrets and purge them if found. Requires [jq](https://jqlang.github.io/jq/).
- [pwp](https://github.com/ttkalcevic/pwp) - Provides a convenient way to display the present working path in the terminal prompt and lists the current working directory along with its parent directories. Additionally, it includes a custom command .. to navigate to parent directories easily.
- [pyenv (mattberther)](https://github.com/mattberther/zsh-pyenv) - Inspired by **zsh-rbenv**. Installs, updates or loads `pyenv`, and adds extra functionality.
- [pyenv (twopizza9621536)](https://github.com/TwoPizza9621536/zsh-pyenv) - Based on the oh-my-zsh [pyenv](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/pyenv) plugin with modifications from the rbenv and jenv plugins.
- [pyenv (xlshiz)](https://github.com/xlshiz/pyenv-zsh-plugin) - Loads [pyenv](https://github.com/pyenv/pyenv) into the current shell and provides prompt info via the `pyenv_prompt_info` function. Also loads [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) if available.
- [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
- [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load [pyenv](https://github.com/pyenv/pyenv). The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
- [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast) - Launch a Python `venv` with one command. Designed for use with [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv).
- [q (cal2195)](https://github.com/cal2195/q) - Add `vim`-like macro registers to your ZSH shell.
- [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
- [qiime2](https://github.com/misialq/zsh-qiime2) - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) easier.
- [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
- [quotify](https://github.com/dpretet/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
- [qwy](https://github.com/Ryooooooga/qwy) - ZSH fuzzy completion plugin.
- [randeme](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
- [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - Displays random quotes or facts.
- [ranger (niziL)](https://github.com/NiziL/ranger.plugin.zsh) - provide prompt element for [ranger](https://github.com/ranger/ranger). Shows current `RANGER_LEVEL`, displaying nothing when the environment variable is unset, something when it is equals to 1, and something else when it is greater than 1.
- [ranger (rc2dev)](https://github.com/rc2dev/ranger-zshz) - Integrates [zsh-z](https://github.com/agkozak/zsh-z) into [ranger](https://github.com/ranger/ranger).
- [ranger-autojump](https://github.com/fdw/ranger-autojump) - Adds [autojump](https://github.com/wting/autojump) support to the [ranger](https://github.com/ranger/ranger) console file manager.
- [raspberryPi4Temperature](https://github.com/KidesLeo/RaspberryPi4TemperaturePromptPlugin) - Puts the Raspberry Pi temperature into a spaceship prompt segment
- [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - Change the colour of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires [OpenRazer](https://openrazer.github.io) linux drivers.
- [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the `rbenv` plugin from [oh-my-zsh](https://ohmyz.sh/).
- [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original [oh-my-zsh](https://ohmyz.sh/) `rbenv` plugin.
- [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) - Inspired by [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby `rbenv` environments.
- [rc-files](https://github.com/0b10/rc-files) - Adds shortcut functions for editing various rc files.
- [recall](https://github.com/mango-tree/zsh-recall) - Makes using command history easier.
- [redis](https://github.com/z-shell/redis) - Will run [redis-server](https://redis.io/) pointing it to the `redis.conf` configuration file. This can be used with the [zdharma/zredis](https://github.com/z-shell/zredis) plugin to share variables between shells.
- [redo](https://github.com/joknarf/redo) - Adds an interactive history menu to replace `Ctrl-R` and `ESC+/`.
- [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
- [reload](https://github.com/aubreypwd/zsh-plugin-reload) - Adds function to quickly reload your `.zshrc`.
- [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
- [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - Converts `...` to `../..`
- [require](https://github.com/aubreypwd/zsh-plugin-require) - Adds ability to `require commandname` and then (if [brew](https://brew.sh) is installed) automatically `brew install commandname` if it isn't already installed.
- [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
- [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - Displays random riddles.
- [ripz](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep).
- [robo](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://github.com/consolidation/robo/).
- [rockz](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
- [ros2-env](https://github.com/Butakus/ros2-env) - Manage [ROS 2](https://github.com/ros2) environment and workspaces.
- [rose-pine-man](https://github.com/const-void/rose-pine-man) - Colorizes `man` pages.
- [run-scripts](https://github.com/Aireck2/zsh-run-scripts) - Runs scripts from `package.json`.
- [rust (cowboyd)](https://github.com/cowboyd/zsh-rust) - Configure your [rust](https://www.rust-lang.org/) toolchain, installing [rustup](https://rustup.rs) if it is not currently installed already.
- [rust (wintermi)](https://github.com/wintermi/zsh-rust) - Plugin for the [rust](https://www.rust-lang.org/) toolchain.
- [rvm](https://github.com/johnhamelink/rvm-zsh) - Initiates [rvm](https://github.com/rvm/rvm) and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
- [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - Add some safety when running [kubectl](https://kubernetes.io/docs/reference/kubectl/) by warning what context you're in after a definable number of seconds since the last `kubectl` command.
- [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
- [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - Add safe-`rm` functionality so that `rm` will put files in your OS' trash instead of permanently deleting them.
- [sail](https://github.com/Razzaghnoori/Sailor/) - Adds convenience aliases for [sail](https://laravel.com/docs/10.x/sail).
- [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
- [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
- [sandboxd](https://github.com/benvan/sandboxd) - Speed up your `.zshrc` & shell startup with lazy-loading by only running setup commands (e.g. `eval "$(rbenv init -)"`, etc) when you need them.
- [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of [vim-sensible](https://github.com/tpope/vim-sensible).
- [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) - Script to automatically update apps on a seedbox.
- [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
- [sdkman](https://github.com/ptavares/zsh-sdkman) - Installs [sdkman](https://github.com/sdkman) and adds completions and aliases for it.
- [sealion](https://github.com/xyproto/sealion) - Allows you to set reminders that will appear in your terminal when your prompt is refreshed.
- [search-directory-history](https://github.com/cmaahs/search-directory-history) - Allows complex search of per-directory history created using the [per-directory-history](https://github.com/jimhester/per-directory-history) plugin.
- [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - Adds keybindings to do global search and replace on current command line.
- [select-history-skim](https://github.com/okhiroyuki/zsh-select-history-skim) Rummage through your history with [skim](https://github.com/lotabout/skim).
- [select-with-lf](https://github.com/chmouel/zsh-select-with-lf) - Lets user select files or a directory using [lf](https://github.com/gokcehan/lf).
- [select](https://github.com/z-shell/zsh-select) - Multi-term searched selection list with approximate matching and uniq mode.
- [selector](https://github.com/joknarf/selector) - Make it easy to create selection menus.
- [send](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
- [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
- [senv](https://github.com/joepvd/senv) - Report presence of sensitive environment variables in the prompt
- [session-sauce](https://github.com/ChrisPenner/session-sauce) - An [fzf](https://github.com/junegunn/fzf) interface for tmux session creation and management for all your projects.
- [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
- [setpath](https://github.com/mys721tx/set_path) - Adds some local paths to your `fpath` and `$PATH`.
- [shelf](https://github.com/ecmma/shelf) - Utility which can be used to bookmark and access directly any file using mnemonics.
- [shell-fns](https://github.com/Hdoc1509/shell-fns) - Includes `git`, `neovim`, `npm`, `pip` extended functionality.
- [shellcolor](https://github.com/SaltedBlowfish/zsh-shellcolor) - Changes the terminal background color based on the presence of a `.shellcolor` in the current directory.
- [shellfirm](https://github.com/kaplanelad/shellfirm) - Shellfirm is a handy utility to help avoid running dangerous commands without an extra step of approval. When risky patterns is detected you will immediately get a small prompt challenge that will verify your action.
- [shift-select](https://github.com/jirutka/zsh-shift-select) - Emacs shift-select mode for ZSH - select text in the command line using Shift, as in many text editors, browsers and other GUI programs.
- [shortcuts](https://github.com/fairy-root/Zsh-Shortcuts-Plugin) - Enhance your terminal productivity with the Shortcuts plugin for [oh-my-zsh](https://ohmyz.sh/). Easily manage command shortcuts with robust features.
- [show-git-user](https://github.com/luisprgr/zsh-show-git-user) - When you need to work with multiple `git` users on the same machine this plugin will show which `git` user name is active in your prompt.
- [show-path](https://github.com/redxtech/zsh-show-path) - Provides a function shows the `$PATH` line by line.
- [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
- [singularityenv](https://github.com/saravanabalagi/zsh-plugin-singularityenv) - Provides a `singularityenv_prompt_info` function which returns the current singularity environment name
- [skaffold](https://github.com/todie/skaffold.plugin.zsh) - ZSH integration and completions for [skaffold](https://skaffold.dev) local kubernetes development environment.
- [skim (casonadams)](https://github.com/casonadams/skim.zsh) - Tries to determine where [skim](https://github.com/lotabout/skim) is installed, then enables its fuzzy auto-completion and key bindings.
- [skim (hackerchai)](https://github.com/hackerchai/skim-zsh) - Adds support for [skim](https://github.com/lotabout/skim)
- [slugify](https://github.com/lashoun/slugify) - Converts filenames and directories to a web friendly format.
- [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
- [smartcache](https://github.com/QuarticCat/zsh-smartcache) - Caches command output to speed up shell startup time.
- [smartinput](https://github.com/momo-lab/zsh-smartinput) - When you type brackets or quotes, the corresponding end brackets/quotes are automatically added.
- [smile](https://github.com/fundor333/smile) - Adds function to display random smileys.
- [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
- [snr](https://github.com/raisedadead/zsh-snr) - Passes the selected output of the first command to the next.
- [solarized-man](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in the terminal.
- [spaceship-ocm](https://github.com/iamkirkbater/spaceship-ocm-plugin) - Queries your OpenShift Cluster Manager (ocm) configuration to show which environment you're connected to. Requires [NerdFont](https://www.nerdfonts.com/font-downloads) in your terminal.
- [spack](https://github.com/Game4Move78/zsh-spack) - Includes some useful aliases and functions for loading/unloading [Spack](https://github.com/spack/spack)-generated modules. As it makes use of the `module` command it is much more efficient than `spack load`.
- [ssh-connect](https://github.com/gko/ssh-connect) - A simple `ssh` manager.
- [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
- [ssh-quickconnect](https://github.com/breda/zsh-ssh-quickconnect) - Simple utility to quickly connect to hosts from your `ssh` config & `known_hosts` file.
- [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
- [startify](https://github.com/NorthIsMirror/zsh-startify) - Shows recently used `vim` files, shell-util files, active `tmux` sessions, recently-run `git` commands and more.
- [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
- [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
- [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
- [sublime](https://github.com/valentinocossar/sublime) - Same as the official [Sublime](https://www.sublimetext.com/) plugin for [Oh My Zsh](https://ohmyz.sh/), but this opens files in the current Sublime window, if there is one already open.
- [sudo (hcgraf)](https://github.com/hcgraf/zsh-sudo) - The `sudo` plugin from [oh-my-zsh](https://ohmyz.sh/), extracted to a standalone. Toggles `sudo` before the current/previous command by pressing *ESC-ESC- in emacs-mode or vi-command mode.
- [sudo (none9632)](https://github.com/none9632/zsh-sudo/) - Adds `sudo` as a prefix to the current command by typing `ESC`-`ESC`.
- [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - Directly open files in the shell using ZSH's suffix aliases.
- [sussysh](https://github.com/sussynuggetz/sussysh-zsh) - Based on xiong-chiamiov.
- [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - Rewrite of the stock [oh-my-zsh](https://ohmyz.sh/) [svn](https://subversion.apache.org/) plugin.
- [switch-git](https://github.com/robin-mbg/switch-git) - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
- [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for [Symfony](https://symfony.com/).
- [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
- [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this *before* [zsh-users/zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) or they will both break.
- [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
- [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
- [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for `vi` emulation keymaps. It works under Linux, macOS and Android (via Termux).
- [systemd](https://github.com/le0me55i/zsh-systemd) - Adds many aliases for `systemd`.
- [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
- [tab-title (p1r473)](https://github.com/p1r473/tab-title/) - Rename [tmux](https://github.com/tmux/tmux/wiki) and [screen](https://www.gnu.org/software/screen/manual/screen.html) panes and windows.
- [tab-title (trystan2k)](https://github.com/trystan2k/zsh-tab-title) - Set the terminal tab title according to current directory or running process. Forked from [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh).
- [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
- [take](https://github.com/amyreese/zsh-take) - Replicates `take` from [oh-my-zsh](https://ohmyz.sh/).
- [tasko](https://github.com/knid/tasko) - Allows you to annotate [TaskWarrior](https://github.com/GothenburgBitFactory/taskwarrior) tasks.
- [telepresence](https://github.com/alexgervais/telepresence-ps1) - Add the current [Telepresence](https://www.telepresence.io/) connection status and context to your ZSH prompt.
- [terminal-aliases](https://github.com/dvir-levy/terminal-aliases) - Adds convenience aliases for [terraform] [git] and more.
- [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new macOS El Capitan Terminal.app features.
- [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - Adds a `set-term-title` function you can use to title terminal windows.
- [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
- [termux](https://github.com/zpm-zsh/termux) - Adds compatibility for [Termux](https://termux.com/).
- [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - Add [terraform](https://www.terraform.io/) workspace to prompt.
- [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) - Extends the original [oh-my-zsh](https://ohmyz.sh/) plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
- [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - Add convenience aliases for [terraform](https://terraform.io/), tab completions and helper function to add your terraform workspace in the prompt.
- [terraform (ptavares)](https://github.com/ptavares/zsh-terraform) - Adds aliases, functions and tab completions. Also installs [terraform-docs](https://github.com/terraform-docs/terraform-docs), [tfsec](https://github.com/aquasecurity/tfsec) and [tflint](https://github.com/terraform-linters/tflint).
- [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for [terraform](https://terraform.io/), along with completions for `terraform` and `terragrunt`.
- [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - Plugin for [Terragrunt](https://github.com/gruntwork-io/terragrunt), a thin wrapper for [Terraform](https://terraform.io/) that provides extra tools.
- [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads `tfenv` inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
- [tfswitch](https://github.com/ptavares/zsh-tfswitch) - Installs and loads [tfswitch](https://github.com/warrensbox/terraform-switcher).
- [tgenv](https://github.com/ptavares/zsh-tgenv) - Installs and loads [tgenv](https://github.com/cunymatthieu/tgenv.git). Includes a function to manually update `tgenv`.
- [tgswitch](https://github.com/ptavares/zsh-tgswitch) - Installs and loads [tgswitch](https://github.com/warrensbox/tgswitch).
- [thefuck](https://github.com/laggardkernel/thefuck) - Loads [thefuck](https://github.com/nvbn/thefuck) (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
- [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - Convenience functions for working with [theia-ide](https://github.com/theia-ide/theia).
- [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) - Adds a few advanced bindings for [tig](https://github.com/jonas/tig) and also provides a `tig-pick` script.
- [timewarrior](https://github.com/svenXY/timewarrior) - Adds support for [timewarrior](https://timewarrior.net/), a time-tracking application.
- [tinted-shell](https://github.com/tinted-theming/tinted-shell) - Adds a script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
- [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips).
- [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
- [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
- [tm](https://github.com/kjhaber/tm.zsh) - Simplifies creating new [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
- [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
- [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
- [tmux-sessionizer](https://github.com/nikevsoft/tmux-sessionizer) - [tmux](https://tmux.github.io) sessionizer as seen on ThePrimeagen.
- [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) with ZSH.
- [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) pane.
- [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
- [tmux](https://github.com/zpm-zsh/tmux) - Plugin for [tmux](https://tmux.github.io).
- [tmuxrepl](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L [tmux](https://tmux.github.io) session.
- [todotxt](https://github.com/Neluji/omz-todotxt) - Adds aliases for [todo.sh](https://github.com/benignoc/alfred-todotxt/).
- [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
- [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix) - Add a widget to toggle a prefix to a command. Binds Alt+s to prefix a command with `sudo` by default.
- [toolbox](https://github.com/paxcoder/zsh-toolbox) - Automagically updates [homebrew](https://brew.sh) plugins. Allows enabling/disabling notice during startup and alias setup.
- [touchplus](https://github.com/raisedadead/zsh-touchplus) - Create files with `touch` including the path.
- [traista](https://github.com/exaluc/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
- [travis](https://github.com/denolfe/zsh-travis) - Opens the [Travis CI](https://www.travis-ci.com/) page for the current repo if one exists.
- [tre](https://github.com/redxtech/zsh-tre) - Makes using [tre](https://github.com/dduan/tre#editor-aliasing) easier.
- [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager.
- [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
- [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
- [ugit](https://github.com/Bhupesh-V/ugit) - Lets you undo your last `git` operation.
- [uncloudium](https://github.com/Talon1024/omz-uncloudium) - Adds helper script to download crx files from the Google Chrome web store.
- [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
- [unique-id](https://github.com/z-shell/zsh-unique-id) - Provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
- [unix-simple](https://github.com/redxtech/zsh-unix-simple) - A command that shows a graphic about the simplicity of unix.
- [unraid](https://github.com/donbuehl/zsh-unraid) - Adds convenient aliases and functions for managing your Unraid server directly from the command line.
- [unwrap](https://github.com/foxleigh81/unwrap-zsh-plugin) - Allows you to remove a directory without removing the contents - it puts them in the directory's parent directory.
- [up (cjayross)](https://github.com/cjayross/up) - A simple way to navigate up through directories.
- [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
- [up-dir](https://github.com/sgpthomas/zsh-up-dir) - Binds `ctrl-h` to navigating up a directory. This makes it very easy to go up a few directories without having to type any commands.
- [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom [oh-my-zsh](https://ohmyz.sh/) plugins. Only works with the oh-my-zsh framework.
- [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
- [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original [oh-my-zsh](https://ohmyz.sh/) `venv` module.
- [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - A wrapper plugin for [vagrant](https://www.vagrantup.com/) that allows for calling `vagrant` commands from outside of the box directory. The plugin also ships with a few extra commands that help to manage more than one box, along with custom tab-completion.
- [valet](https://github.com/NasirNobin/zsh-valet/) - Reads `.valetphprc` from the project root and will switch to that PHP version automatically.
- [vanilli.sh](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
- [vapor](https://github.com/notf0und/zsh-vapor) - Laravel [vapor](https://github.com/laravel/vapor-cli) plugin for ZSH to help you to run `vapor` from anywhere in the project tree, with auto-completion!
- [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - Help vcsh users require GitHub repositories using `vcsh` for auto-installation in `~/.zshrc`, etc.
- [velocity](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
- [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) (though you don't *have- to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
- [venv-wrapper](https://github.com/glostis/venv-wrapper) - Provides ZSH functions to ease the management of your virtual environments using `venv`.
- [venv](https://github.com/lucasheartcliff/venv) - Run 'source venv/bin/activate' automatically every time there's a path `venv/bin/activate` file in the directory.
- [vi-increment](https://github.com/zsh-vi-more/vi-increment) - Add `vim`-like increment/decrement operations.
- [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly `vi`(`vim`) mode plugin for ZSH.
- [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) - Add extra `vi`-like functionality.
- [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - Add more `vi`-like functionality to ZSH.
- [vi-motions](https://github.com/zsh-vi-more/vi-motions) - Add new motions and text objects including quoted/bracketed text and commands.
- [vi-quote](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
- [viexchange](https://github.com/okapia/zsh-viexchange) - A `vi` mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
- [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
- [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
- [vimman](https://github.com/yonchu/vimman) - View `vim` plugin manuals (help) like `man` in ZSH.
- [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
- [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv ZSH plugin for [oh-my-zsh](https://ohmyz.sh).
- [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream [oh-my-zsh](https://ohmyz.sh/). Adds support for customizing the virtualenv prompt in [oh-my-zsh](https://ohmyz.sh) themes.
- [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
- [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An [oh-my-zsh](https://ohmyz.sh/) plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
- [visit](https://github.com/justinpchang/visit) - Custom plugin for faster navigation.
- [vivid](https://github.com/ryanccn/vivid-zsh) - Make it easier to use `LSCOLORS` with [vivid](https://github.com/sharkdp/vivid).
- [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - Seamlessly install and configure the [Volta](https://volta.sh) Node.js toolchain manager.
- [volta](https://github.com/ri7nz/zsh-volta) - Installs and loads [Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
- [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An [oh-my-zsh](https://ohmyz.sh/) plugin to control [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
- [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for [Visual Studio Code](https://code.visualstudio.com/) on macOS.
- [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - Simple plugin to open [Visual Studio Code](https://code.visualstudio.com/) a little more easily across systems.
- [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
- [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run `emacs` commands directly from [vterm](https://github.com/vterm/vterm) shell sessions.
- [vtex](https://github.com/xdigu/zsh-vtex) - Adds helper aliases for [vtex](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-command-reference#default-commands) cli commands.
- [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
- [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
- [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc](https://github.com/garabik/grc).
- [watch](https://github.com/enrico9034/zsh-watch-plugin) - Easily prefix your current or previous commands with watch by pressing `CTRL + W`.
- [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for the [watson](https://github.com/TailorDev/Watson) time management system.
- [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
- [web-search (anant-mishra1729)](https://github.com/Anant-mishra1729/web-search/) - Adds aliases for searching with Google, Bing, Wiki, YouTube, Yahoo, Duck Duck Go, GitHub, Stack Overflow and other services straight from the command line.
- [web-search (sinetoami)](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
- [web-search (yabanahano)](https://github.com/Yabanahano/web-search) - Adds aliases for searching with Google, Wiki, Bing, YouTube and other popular services.
- [welcome-banner](https://github.com/joshuadanpeterson/zsh-welcome-banner) - Displays a login banner with a random quote.
- [westchange](https://github.com/TomiVidal99/westchange) - Allows you to quickly change between directories. Requires [fzf](https://github.com/junegunn/fzf).
- [which-jspm](https://github.com/zkuzmic/which-jspm/) - Adds `npm`, `yarn` or `pnpm` to the end of your prompt depending on what lockfile(s) it detects in the current directory.
- [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
- [window-title](https://github.com/olets/zsh-window-title) - Adds informative tiles to your terminal windows.
- [windows-title](https://github.com/mdarocha/zsh-windows-title) - Dynamically updates terminal window title with current directory and the last command run.
- [wordle](https://github.com/zechris/zwordle) - Wordle for ZSH, with tab-completions.
- [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
- [worktree](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
- [wsl](https://github.com/florentinl/omz-wsl) - Adds helper functions to make it easier to work in ZSH when running inside WSL.
- [wsl2-ssh-pageant](https://github.com/antoinemartin/wsl2-ssh-pageant-oh-my-zsh-plugin) - Use your Yubikey stored GPG keys from WSL. This packages the instructions from [wsl2-ssh-pageant repo](https://github.com/BlackReloaded/wsl2-ssh-pageant) as a ZSH plugin.
- [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - plugin for [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
- [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local `yadm` configuration changes.
- [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's `pip` environment if `pipenv` detects the presence of one.
- [yazi-zoxide](https://github.com/fdw/yazi-zoxide-zsh) - This plugin for [zsh](https://www.zsh.org) adds just one shortcut, but unfolds the magic of both [Zoxide](https://github.com/ajeetdsouza/zoxide) and [yazi](https://github.com/sxyazi/yazi/). Without arguments, `y` just opens yazi. If you supply an argument that is a directory, `yazi` is opened in that directory. But if you supply anything else as an argument, `zoxide` is called with the argument and `yazi` is opened there.
- [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's [Yeoman](http://yeoman.io/) plugin for [oh-my-zsh](https://ohmyz.sh/), compatible with yeoman version ≥1.0 (includes options and command auto-completion).
- [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
- [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - Adds `yt` aliases to download videos from YouTube.
- [youtube-dl](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/).
- [yup](https://github.com/redxtech/zsh-yup) - Adds helper function to upgrade all the dependencies in a `yarn`/`npm` project.
- [z.lua](https://github.com/skywind3000/z.lua) - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
- [zabb](https://github.com/Mellbourn/zabb) - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z](https://github.com/ajeetdsouza/zoxide) to unambiguously jump to that directory.
- [zabrze](https://github.com/Ryooooooga/zabrze) - A ZSH abbreviation expansion plugin.
- [zapmarks](https://github.com/iliutaadrian/zapmarks) - Provides quick access to your most used command-line bookmarks. It allows you to save, search, and execute complex commands with ease.
- [zautoload](https://github.com/Doc0x1/zautoload) - Autoloader for ZSH config files.
- [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
- [zbrowse](https://github.com/zdharma-continuum/zbrowse) - When doing shell work, it is often the case that `echo $variable` is invoked multiple times, to check the result of a loop, etc. With ZBrowse, you just need to press `Ctrl-B`, which invokes the ZBrowse – Zshell variable browser.
- [zce](https://github.com/hchbaw/zce.zsh) - Vim's EasyMotion / Emacs's ace-jump-mode for ZSH.
- [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
- [zconvey](https://github.com/zdharma-continuum/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
- [zed](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z](https://github.com/rupa/z) to install it via a ZSH plugin.
- [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) - Provides an environment that uses [zellij](https://github.com/zellij-org/zellij). Requires [tmux](https://github.com/tmux/tmux). Deprecated by author, now [supported natively](https://zellij.dev/documentation/integration.html#autostart-on-shell-creation).
- [zellij (tranzystorek-io)](https://codeberg.org/tranzystorekk/zellij.zsh) - Provides an environment that autostarts [zellij](https://github.com/zellij-org/zellij) as your terminal's multiplexer.
- [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
- [zenplash](https://github.com/Chivier/zenplash) - Creates files from templates stored in a user directory.
- [zenv](https://github.com/janitha/zenv) - Isolated working shell enviornments per directory (like direnv, but uses a new shell instance to provide cleaner isolation).
- [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the GitHub page for installation details. Includes `git` and `hg` status decorators.
- [zeza](https://github.com/duggum/zeza) - Manages and customizes [eza](https://github.com/eza-community/eza), the very colorful `ls` replacement.
- [zflai](https://github.com/zdharma-continuum/zflai) - A fast logging framework for ZSH.
- [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
- [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make `compinit` run only once after all loading is done by [zgen](https://github.com/tarjoilija/zgen).
- [zgenom-ext-eval](https://github.com/jandamm/zgenom-ext-eval/) - Zgenom extension for creating plugins inline.
- [zhooks](https://github.com/agkozak/zhooks) - Displays the contents of any ZSH hook arrays and the code of any hook functions that have been defined. Useful for debugging.
- [zi-rbenv](https://github.com/z-shell/zi-rbenv) - Fast `rbenv` loads if you're using [zi](https://github.com/z-shell/zi/).
- [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for [zimfw](https://github.com/zimfw/zimfw), packaged into a zimfw plugin.
- [zinfo_line](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes.
- [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) - [zinit](https://github.com/zdharma-continuum/zinit) extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
- [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) - Allows user to define ices active for multiple zinit commands.
- [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) - [Zinit](https://github.com/zdharma-continuum/zinit) extension that generates man pages for all plugins and snippets
- [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) - Install groups of plugins with a single label ([zinit](https://github.com/zdharma-continuum/zinit) only).
- [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) - [zinit](https://github.com/zdharma-continuum/zinit) extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
- [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) - Adds function to automatically download the newest version of a file to which URL is hosted on a webpage.
- [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) - [zinit](https://github.com/zdharma-continuum/zinit) extension that that installs rust and cargo packages inside plugin directories.
- [zinit-annex-submods](https://github.com/z-shell/z-a-submods) - [zinit](https://github.com/zdharma-continuum/zinit) extension that allows installing and managing additional submodules within a plugin or snippet.
- [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) - [zinit](https://github.com/zdharma-continuum/zinit) extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
- [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) - Allows installing plugins for [zinit](https://github.com/zdharma-continuum/zinit) without specifying the user name by querying the Github API.
- [zinit-console](https://github.com/z-shell/zinit-console) - A semigraphical (curses) consolette for the [zinit](https://github.com/zdharma-continuum/zinit) plugin manager.
- [zinsults](https://github.com/ahmubashshir/zinsults) - Prints insults if a command fails.
- [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
- [zlitefetch](https://github.com/ippee/zlitefetch) - Lightweight system information plugin.
- [zload](https://github.com/mollifier/zload) - Hot Reload for ZSH functions. Enables rapid development.
- [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses `notify-send` and rings a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
- [zman](https://github.com/mattmc3/zman) - Use [fzf](https://github.com/junegunn/fzf) to quickly browse ZSH manuals.
- [znotify](https://github.com/rudeigerc/znotify) - A simple plugin for sending notifications to other services.
- [znvm](https://github.com/Ajnasz/znvm) - A [Node.js](https://nodejs.org) version manager for ZSH similar to [nvm.sh](https://github.com/nvm-sh/nvm) but faster.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A fast alternative to `cd` that learns your habits.
- [zplug-blame](https://github.com/jkcdarunday/zplug-blame) - A [zplug](https://github.com/zplug/zplug)-specific plugin that displays how long each of your plugins took to load.
- [zpy](https://github.com/AndydeCleyre/zpy) - Manage Python Environments, dependencies, and isolated app installations, with a ZSH frontend to [pip-tools](https://github.com/jazzband/pip-tools).
- [zredis-cmd](https://github.com/z-shell/zredis-cmd) - Utilizes variable sharing done by [zredis](https://github.com/zdharma-continuum/zredis) plugin to implement remote command execution.
- [zredis](https://github.com/zdharma-continuum/zredis) - Adds [Redis](https://redis.io/) database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
- [zservice-py3http](https://github.com/z-shell/zservice-py3http) - Serve a given directory with Python 3's http server from the standard library.
- [zsh-expand](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases and incorrect spellings and phrases with the spacebar key. Native expansions such as globs, command/process substitution, `=command expansion`, history expansion and `$parameters` are also expanded by default but can be turned off.
- [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - Automates ZSH + [oh-my-zsh](https://ohmyz.sh/) installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
- [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - Provides a function that automatically shames the user for forgetting they weren't in `vim`.
- [zsh-select](https://github.com/z-shell/zsh-select) - Displays a selection list. It is similar to `selecta`, but uses the curses library to do display, and when compared to [fzf](https://github.com/junegunn/fzf), the main difference is approximate matching instead of fuzzy matching.
- [zsh-watch](https://github.com/Thearas/zsh-watch) - Simple `watch` that supports alias and completion.
- [zsh-z (agkozak)](https://github.com/agkozak/zsh-z) - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
- [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - Installs and loads [z](https://github.com/rupa/z.git).
- [zshange_directory_recent](https://github.com/Kjeldgaard/zshange_directory_recent) - Change to a recent directory. Requires [fzf]( https://github.com/junegunn/fzf).
- [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for [oh-my-zsh](https://ohmyz.sh).
- [zshrc-sync](https://github.com/Skylor-Tang/zshrc-sync) - Detects changes to `.zshrc` and pushes them to github when `zsh` exits.
- [zshrc](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes.
- [zshrpg](https://github.com/aliervo/zshrpg) - A wrapper that fully integrates [rpg-cli](https://github.com/facundoolano/rpg-cli/) with ZSH!
- [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
- [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
- [ztouch](https://github.com/mjrafferty/ztouch) - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
- [ztrace](https://github.com/zdharma-continuum/ztrace) - Catches output of commands, allows to reuse that output, glue it with history content.
- [zui](https://github.com/zdharma-continuum/zui) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)
- [zypper-short](https://github.com/justanotherinternetguy/zypper-short) - Plugin for OpenSuse Tumbleweed's package manager, `zypper`.

## Completions

These plugins add tab completions without adding extra functions or aliases.

- [1password-op](https://github.com/unixorn/1password-op.plugin.zsh) - Loads autocompletions for 1Password's [op](https://developer.1password.com/docs/cli/get-started/) command line tool.
- [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
- [aircrack](https://github.com/Doc0x1/Aircrack-Zsh-Completions) - Adds completions for `airbase-ng`, `aircrack-ng`, `airdecap-ng`, `airdecloak-ng`, `aireplay-ng`, `airmon-ng`, `airodump-ng`, `airolib-ng`, `airserv-ng`, `airtun-ng`, `airventriloquist-ng`.
- [aliyun](https://github.com/thuandt/zsh-aliyun) - Add completions for the [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
- [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for [viasite-ansible/ansible-server](https://github.com/viasite-ansible/ansible-server).
- [antibody](https://github.com/sinetoami/antibody-completion) - This plugin provides completion for the [Antibody](https://github.com/getantibody/antibody) plugin manager.
- [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
- [argc-completions](https://github.com/sigoden/argc-completions) - Uses [argc](https://github.com/sigoden/argc) and [jq](https://github.com/stedolan/jq) to add ZSH tab completions.
- [audogombleed.sh](https://github.com/i-love-coffee-i-love-tea/audogombleed.sh) - Makes it easy to generate completion files using a declarative syntax, quickly and without coding.
- [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg.
- [autorestic](https://github.com/naegling/zsh-autorestic) - automatically installs [Restic](https://github.com/cupcakearmy/autorestic/)'s completions for you, and keeps them up to date as your autorestic version changes.
- [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - Adds completion support for `awscli` to manage AWS profiles/regions and display them in the prompt.
- [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the `aws_manager` CLI.
- [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - Support `bash` completions for commands when no native ZSH one is available.
- [batect](https://github.com/batect/batect-zsh-completion/) - Adds tab completions for [batect](https://batect.dev/) build system.
- [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
- [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
- [bio](https://github.com/yamaton/zsh-completions-bio/) - Completions for bioinformatics tools.
- [bitbake](https://github.com/antznin/zsh-bitbake) - Completions for [bitbake](https://git.openembedded.org/bitbake).
- [bosh (krujos)](https://github.com/krujos/bosh-zsh-autocompletion) - Adds [BOSH](https://github.com/cloudfoundry/bosh) autocompletion.
- [bosh (thomasmitchell)](https://github.com/thomasmitchell/bosh-complete) - Tab completion for [BOSH](https://github.com/cloudfoundry/bosh)].
- [brew-completions](https://github.com/z-shell/brew-completions) - Brings [Homebrew Shell Completion](https://docs.brew.sh/Shell-Completion) under the control of ZSH & [ZI](https://github.com/z-shell/zi/).
- [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for [homebrew](https://brew.sh) services.
- [buidler](https://github.com/gonzalobellino/buidler-zsh) - Adds completion and useful aliases for NomicLabs Buidler tool.
- [bw](https://github.com/CupricReki/zsh-bw-completion) - Adds completion for [Bitwarden](https://bitwarden.com/).
- [cabal (d12frosted)](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
- [cabal (ehamberg)](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
- [carapace-bin](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer.
- [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - this does not automatically generate completions as needed, you have to explicitly run it to generate completions for a command.
- [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - All the functionality of the original oh-my-zsh cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
- [carthage](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage).
- [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
- [chezmoi](https://github.com/mass8326/zsh-chezmoi) - Adds completions and aliases for [chezmoi](https://www.chezmoi.io/). Detects if you have `git` aliases and generates `chezmoi` aliases for them.
- [click-completion](https://github.com/click-contrib/click-completion) - Add automatic completion support for [Click](http://click.pocoo.org/), including displaying the options and commands help during the tab completion.
- [cod](https://github.com/dim-an/cod) - A completion demon for `bash`/`fish`/`zsh` which creates completion functions on the fly when it sees you run something with `--help`.
- [codeception](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
- [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - Tab completions for [comonicon](https://github.com/Roger-luo/Comonicon.jl).
- [complete-lastf](https://github.com/chougousui/complete-lastf) - Adds a tab completion to select the most recently modified file or directory.
- [complete-mac](https://github.com/vitkabele/complete-mac) - Add completions for macOS `ioreg`, `lsmp`, `scselect`, `system_profiler` and `tmutil` commands.
- [completion-sync](https://github.com/BronzeDeer/zsh-completion-sync) - Automatically loads completions added dynamically to `FPATH` or `XDG_DATA_DIRS`.
- [completions (clarketm)](https://github.com/clarketm/zsh-completions) - This includes the zsh-users[completions](https://github.com/zsh-users/zsh-completions), zchee's [completions](https://github.com/zchee/zsh-completions), nilsonholger's [osx-zsh-completions](https://github.com/nilsonholger/osx-zsh-completions) and various other custom completions.
- [completions (zchee)](https://github.com/zchee/zsh-completions) - Yet another collection of tab completions.
- [completions (zsh-users)](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
- [conda](https://github.com/conda-incubator/conda-zsh-completion) - ZSH tab completion for [conda](http://conda.pydata.org/).
- [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
- [crazy-complete](https://github.com/crazy-complete/crazy-complete) - Every program should have autocompletion in the shell to enhance user experience and productivity. `crazy-complete` helps solve this task by generating robust and reliable autocompletion scripts.
- [cross-compiler](https://github.com/Freed-Wu/zsh-completions-for-cross-compilers) - In cross compilations, there are many tools like x86_64-w64-mingw32-gcc, x86_64-linux-android32-clang, arm-none-eabi-gcc, etc. This plugin provides ZSH completions for them.
- [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop](https://github.com/bcicen/ctop).
- [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) - Completions for dagger.
- [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
- [ddc](https://github.com/Shougo/ddc-zsh) - Adds tab completions for [ddc](https://github.com/Shougo/ddc.vim).
- [deno](https://github.com/marcelohmdias/zsh-deno) - Tab completions for [deno](https://deno.com/).
- [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
- [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
- [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - Add tab completions for `docker` and `docker-compose`.
- [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet tab completion.
- [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
- [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
- [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell).
- [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) - Tab completions for `efibootmgr`.
- [elm](https://github.com/kraklin/elm.plugin.zsh) - Tab completion for [elm](https://elm-lang.org/).
- [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
- [expressvpn](https://github.com/tk7r/zsh-expressvpn) - Adds tab completions for the [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) client.
- [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
- [extract (thetic)](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
- [fancy-completions](https://github.com/z-shell/zsh-fancy-completions) - Provides various completions tools, libraries and integrations.
- [flatpak](https://github.com/bilelmoussaoui/flatpak-zsh-completion) - Tab completions for [Flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html).
- [fluxcd](https://github.com/l-umaca/omz-fluxcd-plugin) - Adds tab completion for the [FluxCD command line](https://fluxcd.io/flux/cmd/) tool, as well as some aliases for the most common flux commands.
- [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://concourse-ci.org/fly.html) commands.
- [fnm](https://github.com/zap-zsh/fnm) - Adds tab completions for Fast Node Manager [fnm](https://github.com/Schniz/fnm).
- [fvm](https://github.com/olrtg/zsh-fvm) - Adds tab completions for the [Flutter Version Manager (FVM)](https://fvm.app/).
- [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - Fuzzy completion to navigate and preview all Google Cloud SDK `gcloud` CLI commands
- [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - Add tab completion for ZSH, `bash` & applications using GNU Readline.
- [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - Fuzzy completions for [fzf](https://github.com/junegunn/fzf) and [ZSH](https://www.zsh.org/) that can be triggered by a trigger sequence that defaults to `**`.
- [fzshell](https://github.com/mnowotnik/fzshell) - Fetches fuzzy completions from sources predefined by a user.
- [gardenctl](https://github.com/holgerkoser/gardenctl) - Tab completions for the [Gardener](https://github.com/gardener/gardenctl-v2) command-line interface, as well as some aliases for common gardenctl commands
- [gcloud (littleq0903)](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK.
- [gcloud (wintermi)](https://github.com/wintermi/zsh-gcloud) - Adds Google Cloud Command Line Interface ([gcloud](https://cloud.google.com/cli) CLI) completions.
- [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - Provides ZSH completion support to various Gentoo tools that lack completion scripts upstream.
- [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands.
- [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow](http://github.com/nvie/gitflow).
- [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf) - ZSH plugin that wraps `git` operations for simplicity and productivity. It also contains completions and combines support for [fzf](https://github.com/junegunn/fzf).
- [git-profiles](https://github.com/baliestri/git-profiles.plugin.zsh) - Manages multiple git users in a single `.gitconfig` file.
- [git-recent-branches](https://github.com/Zacharyjlo/git-recent-branches) - Makes it easy to check view and checkout recently checked-out branches.
- [github-cli](https://github.com/sudosubin/zsh-github-cli) - Tab completions for the GitHub cli.
- [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
- [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
- [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
- [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
- [gstreamer](https://github.com/CraigCarey/gstreamer-tab) - Tab completion for [GStreamer](https://gstreamer.freedesktop.org/).
- [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
- [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
- [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
- [haskell](https://github.com/coot/zsh-haskell) - Adds completions for `cabal`, `ghc` and `ghc-pkgs` commands.
- [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
- [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
- [inshellisense](https://github.com/microsoft/inshellisense) - Provides IDE style autocomplete for shells. It's a terminal native runtime for autocomplete which has support for 600+ command line tools. inshellisense supports `bash`, `fish`, `zsh` and `pwsh` on the Windows, Linux, & MacOS operating systems.
- [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.tech).
- [jenv](https://github.com/cmuench/zsh-jenv) - Tab completions for [jEnv](https://github.com/jenv/jenv).
- [joe](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) gitignore editor.
- [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
- [jx](https://github.com/haysclark/zsh-jx) - Adds tab completions for the Jenkins-X cli.
- [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
- [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://book.keybase.io/docs/cli).
- [kind](https://github.com/TomerFi/zsh-kind)- Loads tab completions for [kind](https://kind.sigs.k8s.io/).
- [kitty](https://github.com/redxtech/zsh-kitty) - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
- [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
- [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/).
- [kubectl (chrishrb)](https://github.com/chrishrb/zsh-kubectl) - Automatically loads completions for [kubectl](https://github.com/kubernetes/kubectl).
- [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - Fast and powerful [fzf](https://github.com/junegunn/fzf)-powered autocompletion for `kubectl`.
- [kubectl-plugin](https://github.com/MartinSimango/kubectl-plugin_completion) - Generates `kubectl` completion scripts to extend the `kubectl` auto complete functionality to accomodate for plugin sub-commands.
- [kustomize](https://github.com/ralgozino/oh-my-kustomize) - Adds tab completions for [kustomize](https://kustomize.io/)
- [lazycomplete](https://github.com/rsteube/lazycomplete) - Lazy loading for shell completion scripts.
- [lets-cli](https://github.com/lets-cli/lets-zsh-plugin) - Add autocompletion for [lets](https://github.com/lets-cli/lets) cli task runner.
- [ls-go](https://github.com/MohamedElashri/ls-go-zsh) - Adds some useful aliases for [ls-go](https://github.com/acarl005/ls-go).
- [mac](https://github.com/scriptingosx/mac-zsh-completions) - Completions files for macOS specific commands and third party tools.
- [mcfly](https://github.com/cantino/mcfly) - Replaces your default ctrl-r shell history search with an intelligent search engine that takes into account your working directory and the context of recently executed commands. McFly's suggestions are prioritized in real time with a small neural network.
- [mill](https://github.com/carlosedp/mill-zsh-completions) - Tab completions for Scala's [Mill](http://mill-build.com/) build tool.
- [miniconda](https://github.com/cmuench/zsh-miniconda) - Tab completions for [miniconda](https://docs.conda.io/en/latest/miniconda.html).
- [misc-completions](https://github.com/syohex/zsh-misc-completions) - Adds completions for more unix and perl commands.
- [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
- [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 ZSH compsys completions!
- [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Tab completions for Metasploit.
- [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
- [myincr](https://github.com/gaojunbin/zsh-myincr/) - Speeds up pasting with autosuggest and incr.
- [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
- [ngrok](https://github.com/bostonaholic/ngrok.plugin.zsh) - Auto-loads [ngrok](https://ngrok.com) and its completions into the shell.
- [nix](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
- [node-ace](https://github.com/romch007/node-ace-zsh-completion) - Completions for `node ace`.
- [nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
- [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - Autocompletion support for `npm run`.
- [npm-scripts-autocomplete](https://github.com/grigorii-zander/zsh-npm-scripts-autocomplete) - Shows autocomplete suggestions from scripts found in the current directory's `package.json`. Works with `npm` and `yarn`.
- [nx](https://github.com/jscutlery/nx-completion) - Completions for [nx](https://nx.dev). Requires [`jq`](https://stedolan.github.io/jq/).
- [oh-my-update](https://github.com/utox39/oh-my-update) - Updates plugins in [oh-my-zsh](https://ohmyz.sh/).
- [okta](https://github.com/sirhc/okta.plugin.zsh) - Provides command line completions for the [`aws-okta`](https://github.com/segmentio/aws-okta) and [okta-awscli](https://github.com/jmhale/okta-awscli) commands.
- [ollama](https://github.com/Katrovsky/zsh-ollama-completion) - Tab command completion for Ollama AI models management.
- [op](https://github.com/sirhc/op.plugin.zsh) - Tab completions for [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
- [openstack](https://github.com/florentinl/openstack-zsh-plugin) - Add functions and aliases for managing [OpenStack](https://www.openstack.org/).
- [osx-zsh-completions](https://github.com/nilsonholger/osx-zsh-completions) - Tab completions for some macOS-specific commands like `launchctl`.
- [packer](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io).
- [pagerduty](https://github.com/jedelson-pagerduty/pagerduty-omz-plugin) - Adds completions for the pagerduty [cli]( https://github.com/martindstone/pagerduty-cli)
- [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
- [parallels](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
- [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) command completion for ZSH.
- [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
- [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
- [pipenv (gangleri)](https://github.com/gangleri/pipenv) - Completions for `pipenv`.
- [pmy](https://github.com/relastle/pmy) - General purpose context-aware ZSH completion engine powered by [fzf](https://github.com/junegunn/fzf).
- [poetry](https://github.com/fourdim/zsh-poetry) - Tab completions for [poetry](https://python-poetry.org/).
- [prettier](https://github.com/sambergo/zsh-prettier-completion/) - Tab completion for [prettier](https://prettier.io/.)
- [quickjump](https://github.com/fikovnik/zsh-quickjump) - Adds tab completion support for [skim](https://github.com/lotabout/skim) for recent files and directories using [fasd](https://github.com/whjvenyl/fasd).
- [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
- [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
- [rancher](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
- [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) - Adds completions for [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
- [rustup](https://github.com/pkulev/zsh-rustup-completion) - Tab completions for Rustup.
- [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - Adds tab completions for [s3cmd](https://s3tools.org/s3cmd).
- [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion) - ZSH command completion for the Salesforce CLI. Requires [jq](https://stedolan.github.io/jq/).
- [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) - Adds completions for [saml2aws](https://github.com/Versent/saml2aws).
- [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - Autocomplete plugin for Salesforce [sfdx](https://developer.salesforce.com/tools/salesforcecli).
- [speedtest](https://github.com/Yash-Singh1/zsh-plugin-speedtest) - Tab completions for the speedtest [cli](https://www.speedtest.net/insights/blog/introducing-speedtest-cli/).
- [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
- [ssh (sunlei)](https://github.com/sunlei/zsh-ssh) - Better host completion for `ssh`.
- [ssh (zpm-zsh)](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`.
- [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
- [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
- [ssh-agent (twfksh)](https://github.com/twfksh/zsh-ssh-agent) - A bloat free utility plugin for managing ssh-agent in ZSH. This plugin automatically starts and manages `ssh-agent` whenever a new ternimal session starts. After running zsh-ssh-agent, you only need to `ssh-add` your keys once. The plugin will handle the rest.
- [ssh-config-suggestions](https://github.com/yngc0der/zsh-ssh-config-suggestions)- Loads completions for `ssh` from `~/.ssh/config`.
- [supabase](https://github.com/Taimoor-Tariq/zsh-supabase) - Tab completions for the [supabase cli](https://supabase.com/docs/guides/cli/getting-started)
- [symfony (Akollade)](https://github.com/Akollade/symfony.plugin.zsh) - Adds completions for [Symfony](https://symfony.com/), including the `bin/console` and `sf` commands.
- [symfony-complete](https://github.com/voronkovich/symfony-complete.plugin.zsh) - Universal completion for [Symfony](https://symfony.com/doc/current/components/console.html) based CLI applications: `composer`, `php-cs-fix`, `bin/console`, `artisan`, `php-cs-fixer` and etc. This supports autocompletion for subcommands and GNU-style options (`--help`)
- [tailscale (heroeslament)](https://github.com/HeroesLament/zsh-tailscale-plugin) - Tab completion and aliases for [tailscale](https://www.tailscale.com/).
- [tailscale (hsrzq)](https://github.com/hsrzq/PluginForTailscale) - Tab completions for [tailscale](https://www.tailscale.com/). Only works on macOS.
- [talosctl](https://github.com/RusMephist/talosctl-zsh-plugin) - Tab completion for [Talos Linux](https://www.talos.dev/v1.6/introduction/what-is-talos/).
- [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
- [terragrunt](https://github.com/jkavan/terragrunt-oh-my-zsh-plugin) - Tab completion for [Terragrunt](https://github.com/gruntwork-io/terragrunt).
- [test-kitchen](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
- [tinygo](https://github.com/sago35/tinygo-autocmpl) - Add tab completions for [tinygo](https://tinygo.org/).
- [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
- [tofu](https://github.com/marknefedov/oh-my-zsh-tofu) - Autoloads tab completions for `tofu`.
- [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) command.
- [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
- [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) command.
- [vorpal](https://github.com/VorpalBlade/vorpal-zsh-completions) - Adds completions for some projects whose upstream appears dead, including [duperemove](https://github.com/markfasheh/duperemove), [optimus-manager](https://github.com/Askannz/optimus-manager) and [pacutils](https://github.com/andrewgregory/pacutils).
- [web-open](https://github.com/AndrewHaluza/zsh-web-open) - Adds alias to open web pages. Only works with Ubuntu 20.
- [web-search](https://github.com/GowayLee/zsh_web_search) - Runs a search in the specified search engine in your default browser.
- [wsl-notify](https://github.com/masonc15/wsl-notify-zsh) - Uses [wsl-notify-send](https://github.com/stuartleeks/wsl-notify-send) to notify when a command takes longer than 15 seconds. Windows-only.
- [xcode](https://github.com/keith/zsh-xcode-completions) - Completions for some Xcode command line tools - `genstrings`, `nm`, `plutil`, `xcode-select`, `xcodebuild`, `xcrun`, `simctl`, `strings`, `swift-demangle`, `swift` and `lipo`.
- [yabai](https://github.com/Amar1729/yabai-zsh-completions) - Add completions for macOS [yabai](https://github.com/koekeishiya/yabai/) tiling window manager.
- [yarn-extra-completion](https://github.com/BuonOmo/yarn-extra-completion) - Inspired by [lukechilds/zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion).
- [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - Add autocompletions for `yarn add`, `yarn remove`, `yarn upgrade`, `yarn why` and `yarn run`.
- [yt-dlp](https://github.com/clavelm/yt-dlp-omz-plugin) - Tab completions for [yt-dlp](https://github.com/yt-dlp/yt-dlp).
- [zargparse](https://github.com/ctil/zargparse) - Pass it a script that uses `argparse` and it will write a ZSH completion to your current directory.
- [zoxide](https://github.com/jnooree/zoxide-zsh-completion) - Tab completions for [zoxide](https://github.com/ajeetdsouza/zoxide).
- [zpacman](https://github.com/Yttehs-HDX/zsh-zpacman/) - Add tab completions for [zpacman](https://github.com/Yttehs-HDX/zpacman.git).

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. If you're using [zgenom](https://github.com/jandamm/zgenom), add them to your `init.zsh` with `zgenom load githubuser/reponame`.

- [021011](https://github.com/guesswhozzz/021011.zsh-theme) - Minimalist. Includes a single `git` marker for VS Code.
- [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
- [14degree](https://github.com/saims0n/14degree-zsh-theme/) - Includes `git`, `virtualenv` and `rvm` status decorations.
- [1999](https://github.com/DTan13/zsh1999) - Powerline-esque theme. Includes `git` status decorations, network and battery status.
- [a](https://github.com/chammanganti/a-zsh-theme) - Simple theme with current directory and `git` status decorations.
- [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme) - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
- [abhiyan](https://github.com/abhiyandhakal/abhiyan.zsh/) - Segmented prompt. Includes decorators for `git` branch, staged file count, unstaged file count & untracked file count, username, current working directory and the time. Requires Powerline-compatible fonts.
- [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with decorators for `git` status, `node` version and the exit code from the last command.
- [abzt](https://github.com/stentibbing/abzt-zsh-theme) - No nonsense theme with decorators for `git` status and directory information. Requires a nerdfont.
- [acenoster](https://github.com/himdek/Acenoster-ZSH-Theme) - A multi-purpose theme with very detailed `git` and `mercurial` support. Also includes decorators for AWS profile name, virtual environment name if any, number of background tasks, current directory and previous command's exit code if non-zero.
- [achab](https://github.com/niotna/antoinechab-theme) - Includes decorators for the current folder path, the current user and the current `git` branch. Decorator colors are easily customizable.
- [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - Includes decorators for `git` status, the name of your AWS profile, the name of your Azure Service Principal, kubernetes context, terraform workspace, last command exit status and current working directory.
- [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
- [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - Modified version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) with dynamic path shortening.
- [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
- [aftermath](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run in your shell.
- [agitnoster](https://github.com/dbestevez/agitnoster-theme) - Based on [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt). Shows detailed information about `git` status.
- [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) - Uses three asynchronous methods to keep the ZSH prompt responsive while displaying the `git` status and indicators of SSH connection, exit codes, and `vi` mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
- [agnoster (fcamblor)](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) terminal.
- [agnoster (fseguin)](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
- [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) that includes user@hostname and `git` status decorations. Works better with a unicode font.
- [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - Optimized for [solarized](https://ethanschoonover.com/solarized/) color scheme, `git` or other VCS tools, and unicode-compatible fonts. Includes decorators for status of last command run, user@hostname, `git` status, working directory, whether running as root, whether background jobs are running, and other information.
- [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
- [agnoster-multiline](https://github.com/mxkrsv/agnoster-multiline) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). Includes decorators for current directory and `git` status. Requires a font with powerline and `git` glyphs. Automatically disables non-ascii glyphs on linux ttys.
- [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
- [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
- [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
- [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
- [agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires a Powerline-compatible font.
- [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster](https://gist.github.com/agnoster/3712874) themes and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
- [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, `git` status, current directory and user & host information.
- [ai-hayasaka](https://github.com/aeghost/ai-hayasaka-zsh-theme) - Minimalist theme with `git` status, ruby env and python virtualenv decorators.
- [air](https://github.com/Ivan-Kuzmichev/air) - Minimalist theme with `git` status decorations.
- [akzsh](https://github.com/awkimball/akzsh) - Works best with a dark terminal theme, includes `git` decorations.
- [al-magic](https://github.com/Alustrat/al-magic/) - Clone of the oh-my-zsh [af-magic](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme) theme with the time added at the right of the prompt.
- [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - Minimalist theme with `git` status decorations.
- [ale](https://github.com/alepimentel/ale-zsh) - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
- [alesrosina](https://github.com/alesrosina/oh-my-zsh-alesrosina-theme) - Includes decorators for `git` information, current directory and the last command's return status.
- [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
- [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
- [almel](https://github.com/Ryooooooga/almel) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme), written in Rust. Includes `git` status, user@host, last command exit status and working directory decorations
- [aloy (garethclews)](https://github.com/garethclews/aloy) - Fork of [@elenapan's](https://github.com/elenapan/dotfiles) lena theme. Includes magic enter from subnixr's [minimal](https://github.com/subnixr/minimal) where hitting enter without any further commands prints out some useful `ls`, `git` and current working directory information.
- [aloy (karetsu)](https://github.com/karetsu/aloy) - Fork of [@elenapan's](https://github.com/elenapan/dotfiles) lena ZSH theme. extended to give a little more information in it. It also includes the 'magic enter' from subnixr's [minimal](https://github.com/subnixr/minimal) where hitting enter without any further commands prints out some useful `ls`, `git` and current working directory information.
- [alp](https://github.com/zrut747/alp/) - A simple theme with decorations for current directory, root status, username and host.
- [alpha](https://github.com/Republic-Of-Lunar/alpha-zsh-theme) - Includes decorators for username@hostname and current directory.
- [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark terminals. It's a modified version of the [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
- [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
- [amplify](https://github.com/clintfoster/ohmyzsh-theme-amplify) - Minimalist, includes AWS Amplify envioronment and `git` status decorations.- [andy](https://github.com/andymcguinness/andys-theme) - Modified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme with better `git` support.
- [antoinechab](https://github.com/antoinechab/antoinechab-theme) - Includes `git` status, username, time and current directory decorations.
- [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
- [aofxta](https://github.com/aofxta/aofxta.zsh-theme/) - Includes decorators for last command's execution time, `git` information, current directory and current time.
- [ap2](https://github.com/aungphyo-dev/ap2.zsh) - Minimalist them with decortators for time, OS, current directory, `git` status and the last command's exit status.
- [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
- [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
- [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
- [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - A heavily customizable, compatible and performant ZSH theme that uses modules to enable features.
- [appa](https://github.com/givensuman/appa-zsh-theme) - A tidy little theme based on omz's [refined](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/refined.zsh-theme). Requires a Nerd Font.
- [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), includes `vcs` status decorations. Colors customizable by setting vars in your `.zshrc`.
- [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) - Minimalist theme with `git` status decorations.
- [arael](https://github.com/aknackd/zsh-themes) - Fork of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
- [archcraft](https://github.com/mrx04programmer/ZshTheme-ArchCraft) - Greenish theme, optimized for dark backgrounds. Includes `git` status decorations.
- [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH theme. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) theme.
- [arity](https://github.com/hybras/Arity-Zsh-Theme) - A simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
- [aronhoyer](https://github.com/aronhoyer/zsh-theme) - Minimalist theme with right-side `git` status decorations.
- [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - A minimal ZSH theme with `git` decorations.
- [arrow](https://github.com/milon/arrow-zsh-theme) - Minimal theme, includes `git` status decorations.
- [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
- [asq](https://github.com/AugustoQueiroz/asq-theme) - Based on [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
- [astral (skippyr)](https://github.com/skippyr/astral) - Dual line theme with decorators for user@hostname, current directory, python virtual environment and `git` information.
- [astral (xwmx)](https://github.com/xwmx/astral) - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) plugin. Includes decorators for execution time of last command, when it was run, its exit status, machine name, current path, `ssh` status, and `git` status.
- [astro](https://github.com/iplaces/astro-zsh-theme) - Based on the `ys` and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
- [async](https://github.com/mje-nz/zsh-themes) - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
- [aterminal](https://github.com/guiferpa/aterminal) - Displays Node.js, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
- [aub](https://github.com/FraSharp/aub) - Includes decorations for `git` and `hg` status and `username` at `host`.
- [australis](https://github.com/Kimitzuni/australis-theme) - Lightweight theme with decorators for `git` information and current directory. Requires `git` plugin from [oh-my-zsh](https://github.com/ohmyzsh).
- [avil](https://github.com/avil13/avil-zsh-theme) - Minimalist theme with `git` decorations.
- [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
- [avit-mod](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme.
- [avoleo](https://github.com/flameleo11/avoleo-zsh-theme) - Features a date and time prompt for each command, as well as a command number in history. In addition, it uses special symbols '⠾' and '⡶' to display `git` information if applicable in the current path. It also supports custom colors based on the Gnome-Terminal default color palette.
- [aws](https://github.com/chiemerieezechukwu/aws-zsh-theme) - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell), with an extra decorator to show your `$AWS_PROFILE` when it is set.
- [backbone](https://github.com/42LM/backbone-zsh-prompt) - A bare minimum single file prompt, fast as a roadrunner MEEP! MEEP. Includes `git` status and current directory decorations.
- [bahman](https://github.com/bahmanworld/bahman-zsh-theme) - Requires Nerd Font. Has `git` status decorator.
- [banana](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
- [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
- [bar (anki-code)](https://github.com/anki-code/bar-theme) - Minimalist settings for [p10k](https://github.com/romkatv/powerlevel10k).
- [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - Includes username, host, pwd, `git` status decorations and  3x hour reminders to drink water.
- [barion](https://github.com/SEbbaDK/barion) - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) to build.
- [bash](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
- [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) theme and Pasquale D'Silva's [Saturn Terminal](https://github.com/psql/saturn-colors) theme.
- [bashlover](https://github.com/Vu0811/bashlover) - Designed for those who appreciate the powerful features of ZSH shell but still prefer a simple, classic interface similar to the `bash` shell. Includes decorators for `git` information, user@host and the current working directory
- [bashplus](https://github.com/Elagoht/BashPlusZshTheme) - Colorized replica of the default `bash` prompt with decorators for `virtualenv` and `git` status.
- [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [gitster](https://github.com/zimfw/gitster) theme for [ZIM](https://github.com/zimfw/zimfw).
- [bearable](https://github.com/JanmanX/bearable-zsh) - Works well with dark terminal backgrounds.
- [bearings](https://github.com/liamg/bearings) - A fast, clean, super-customizable shell prompt. Includes decorators for current directory, `git` status, exit code of last command, duration of last command, background jobs & username.
- [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - Inspired by [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes decorators for `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
- [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme), but with beer icons.
- [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
- [berghain](https://github.com/meshkinyar/berghain.zsh-theme) - Minimalist theme. Includes decorators for the exit code of the last command run and for `git` status.
- [bernkastel](https://github.com/JamesLaverack/bernkastel) - Based on [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme). Includes decorations for kubernetes context, current directory, last command exit status and `git` status.
- [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
- [bigshrimp](https://github.com/taksyon/BigShrimp-zsh-theme) - A clear and concise theme that includes decorators for username@host, current directory and `git` status.
- [bigyls](https://github.com/Bigyls/Bigyls-zsh-theme) - Based on [lpha3cho](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters). Includes decorators for date, time, IP address, `git` status, plugins and current directory.
- [bira](https://github.com/zimfw/bira) - Fork of Oh-My-ZSH [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme. Includes decorators for working directory, username@host, `git` status information, Python [venv](https://docs.python.org/3/library/venv.html) and a status code when the last command had an error.
- [birame](https://github.com/maniat1k/birame) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
- [biraskull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), includes root status and `git` status decorations.
- [biratime](https://github.com/vemonet/biratime) - Based on the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme, but displays the date instead of the username in the prompt.
- [birav2](https://github.com/shahid64/birav2-theme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes `git`, `rvm` and `virtualenv` status decorations.
- [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, and vcs info decorations.
- [blackrain](https://github.com/ginfuru/zsh-blackrain) - Another `git`-aware theme.
- [blaze](https://github.com/danieltodor/blaze) - Visually similar to powerline. Requires `make` and `g++`. Works best with your terminal set to use a nerd font. Includes decorators for current directory, execution time of last command, exit status of last command, `git` status information, date, time, username and host. Can be extended with custom segments.
- [blazux](https://github.com/blazux/omz-theme) - Includes `git` status decoration and a smiley/sad face indicator of the last command's exit status.
- [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - Adds mercurial support to oh-my-zsh's [blink](https://github.com/max13fr/blinks.zsh-theme) theme.
- [blinks-xfan](https://github.com/ixfan/blinks-xfan) - Based on the existing theme [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
- [bliss](https://github.com/joshjon/bliss-zsh) - A delicate theme that injects color without overwhelming your workspace. Designed to be used with the [bliss iTerm](https://github.com/joshjon/bliss-iterm) color scheme and [bliss dircolors](https://github.com/joshjon/bliss-dircolors). Includes `git` status decorations.
- [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
- [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
- [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information.
- [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme.
- [bluo](https://github.com/varunpbardwaj/bluo) - Colorful prompt segments reminiscent of [bullet-train](https://github.com/caiogondim/bullet-train.zsh) or [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes `git` status decorations.
- [boban](https://github.com/TheEdgeOfRage/boban-zsh) - A powerline-style file based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). Includes decorators for user@hostname, `git` status, current working directory, python venv, AWS profile, `$KUBECONFIG`, the terraform workspace and the exit status of the last command run. Requires a Nerd Font for symbols to render properly.
- [bogo](https://github.com/cubasepp/zsh-bogo-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme). Includes `git` and ruby version decorations.
- [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
- [born-in-the-purple](https://github.com/LeonardMH/born-in-the-purple) - Simple theme with a purple motif. Inspired by [Pure](https://github.com/sindresorhus/pure).
- [bouni](https://github.com/Bouni/bouni-zsh-theme) - Includes decorators for user@host, current directory, active python virtualenv, and `git` status.
- [boxy](https://github.com/evil-tim/boxy-zsh-theme) - Works well with solarized terminal colors. Includes decorators for `username@hostname`, current directory, `git` status, return code for last command, and time last command was run.
- [braundo](https://github.com/Braundo/braundo-zsh-theme) - Straightforward theme with username, current directory, `git` status, and timestamp.
- [bref](https://github.com/mpostaire/bref-zsh-prompt) - A simple prompt. It includes decorators to display `git` status asynchronously, a notification if the `ssh` session is remote, the battery level and the number of background jobs.
- [brisa](https://github.com/ambrisolla/oh-my-zsh-brisa-theme) - Multiline theme based on [fino-time](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme). Includes decorations for username, host, current directory, and `git` status.
- [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
- [brs](https://github.com/evenhold/brs-zsh-theme) - Displays the current song in the prompt with `audtool`.
- [bruh](https://github.com/haze/bruh) - Includes `git` status decorations.
- [brunty](https://github.com/Brunty/omz-brunty) - Includes `git` status decorations.
- [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
- [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme. Includes `git` status decorations.
- [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
- [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme). Works best with [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
- [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - Based on [bubblified (hohmannr)](https://github.com/hohmannr/bubblified). Changes color when root. Includes decorators to show user@host and current directory.
- [buddha](https://github.com/BuddhaDom/zsh-buddha) - Includes decorators for `git` status, current directory, exit status of last command run and username@hostname.
- [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
- [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
- [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
- [bureau-env](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the `git` block.
- [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - Based on [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme). Includes `git` decorations.
- [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes `git` status optimized for large repositories.
- [buster](https://github.com/grantbuster/buster_zsh_theme) - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
- [cactus](https://github.com/welksonramos/cactus) - Minimalist theme with `git` status decorations.
- [cafeconbits](https://github.com/ricard-ferrero/cafeconbits-zsh-theme) - Simple theme with a coffee cup icon. Includes decorators for `git` status, current directory and the exit status of the last command.
- [calma](https://github.com/luislve17/calma) - Minimalist theme that works well on dark backgrounds. Includes decorators for truncated current directory, `git` information, time, and for the exit status of last command.
- [candy-fantasy](https://github.com/fffelix-huang/candy-fantasy) - Modified version of [Candy Kingdowm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/candy-kingdom.zsh-theme)theme.
- [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
- [carriage-return](https://github.com/treyssatvincent/carriage-return.zsh-theme) - omz's [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with an added carriage return.
- [catpuccin](https://github.com/JannoTjarks/catppuccin-zsh) - Minimalist theme. Includes decorators for current directory, exit status of last command and `git` status.
- [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
- [celestialorb](https://github.com/celestialorb/zsh-theme) - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
- [cezhanne](https://github.com/gambardellawill/cezshanne) - Minimalist ZSH theme with `git` status decorators. Requires a [Nerd Font](https://www.nerdfonts.com).
- [cf-ps1](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
- [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - Lean and simple theme.
- [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme) - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
- [chaos](https://github.com/kusamaxi/chaos-zsh) - Inspired by dogenpunk and smt themes, optimized for `git` users and Python developers. Includes decorators for `git` status, python virtual environment, background jobs, error status of last command, user@hostname and current directory. Requires a font with emoji.
- [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
- [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) dark terminal theme.
- [checkmate](https://github.com/skippyr/checkmate) - Decorated with chess pieces. Includes decorators for python venv, current directory, `git` status and whether you're running as root. Requires a Nerd Font.
- [cheeky](https://github.com/kampanosg/zsh-cheeky-prompt) - Includes chicken emoji, decorators for current directory, `git` information and current GCP cluster and project.
- [chello](https://github.com/Abdalla981/chello) - Works well on dark backgrounds. Depends on [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
- [chi](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS.
- [chill](https://github.com/JKerboeuf/chill.zsh-theme) - Has decorations for the current working directory, last command exit status and `git` status.
- [chinatown](https://github.com/skippyr/chinatown) - Powerline-esque theme with decorators for the exit status of the last command run, user@hostname, virtual environments and current directory. Requires a nerdfont font.
- [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme) - Minimalist theme that includes `git` decorations. Requires powerline-compatible fonts and the [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) plugin.
- [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme) - Includes `git` decorations. Requires a powerline-compatible terminal font.
- [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
- [clarity](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility.
- [classic](https://github.com/freakinu/classic-zsh-theme) - A classic unix theme with decorators for username, host, current directory and `git` status.
- [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
- [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh). Works better with dark backgrounds. Includes `git` status decorations.
- [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme.
- [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
- [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - Fork of the upstream [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
- [cleansh](https://github.com/diegoos/cleansh) - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
- [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
- [clipper](https://github.com/Robert-96/clipper) - Minimalist ZSH theme with `git` support. It includes decorations for pwd, last command exit status code and `git` status & branch.
- [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
- [clover](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure).
- [club-house](https://github.com/skippyr/club-house) - Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts). Has decorators for username, hostname, python virtual environment, current working directory, `git` status information and the exit code of the last command run.
- [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for `cmder`that is configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
- [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows. Includes `node` and `git` status decorations.
- [cn](https://github.com/shinqcn/cn-zsh/) - Includes `username`, `directory` and `git` status decorations.
- [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
- [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
- [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays decorators for `git` info, whether you're logged in via `ssh`, and the return code of last command.
- [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on [agnoster](https://gist.github.com/3712874), with a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
- [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme) - A blue-grey theme designed for reading comfort. Includes `git` decorations.
- [collon](https://github.com/lambdalisue/collon.zsh) - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
- [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
- [common](https://github.com/jackharrisonsherlock/common) - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
- [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - Brightly colored theme optimized for dark backgrounds.
- [coolmelon](https://github.com/omkarpai/coolmelon-zsh-theme/) - Includes decorators for user@host, time, current directory, node version and `git` information.
- [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
- [cr](https://github.com/cruzrovira/cr-zsh-theme) - Includes directory, time, host name, last command exit status, and `git` status decorations.
- [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for GitHub plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
- [cravend](https://github.com/cravend/theme) - Includes `hostname` decorator (only in active `ssh` sessions) and `git` status decorations.
- [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
- [croque](https://github.com/Ryooooooga/croque) - Powerline-inspired theme with decorators for OS, user@host, `git` information, `git` username, current directory and exit status of last command.
- [cryo-long](https://github.com/cryocaustik/cryo-long-zsh-theme) - Variant of [cryo](https://github.com/cryocaustik/cryo-zsh-theme/) with added decorators for hostname and current directory.
- [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - A standalone clone of the original oh-my-zsh theme with date and time added.
- [cryptic](https://github.com/thederpykrafter/cryptic.zsh-theme) - Based on [aphrodite-terminal-theme](https://github.com/win0err/aphrodite-terminal-theme). Includes decorators for current directory, `git` status, time, username, hostname and virtual environment.
- [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - A macOS oh-my-zsh shell theme with cute emoji based on the Powerline Vim plugin.
- [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - Works well on dark background, has `git` status decorations.
- [cybensis](https://github.com/cybensis/cybensis-zsh-theme) - Based on [af-magic](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme). Includes decorators for `git` information, `hg` information, and python virtualenv.
- [cypher-ruby](https://github.com/ston1x/cypher-ruby) - Similar to [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) but includes the active Ruby version.
- [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
- [daily-emoji](https://github.com/huytran-wq/zsh-daily-emoji-theme/) - Shows random emoji at the beginning of each command depending on the day of the week.
- [daily](https://github.com/ghlin/zsh-theme-daily) - Includes `git` and `ssh` status decorations.
- [daivasmara](https://github.com/Daivasmara/daivasmara.zsh-theme) - Chill theme with decorators for current directory (truncated if necessary) and `git` information, including time since last commit.
- [dalailahner](https://github.com/dalailahner/dalailahner.zsh-theme) - Minimalist theme with decorators for `git` status, username and current directory. Based on Steve Losh's [Prose](https://github.com/sjl/oh-my-zsh/blob/master/themes/prose.zsh-theme) theme.
- [damino](https://github.com/njdom24/Damino-Zsh-Theme) - Minimal powerline-esque theme with `git` decorations.
- [dangerroom](https://github.com/abbreviatedman/dangerroom) - Informative, minimal, and, above all, X-Men themed. Includes decorators for `git` status, working directory, parent directory and `vim` mode.
- [dango](https://github.com/ann-kilzer/annkilzer.zsh-theme) - Includes decorations for current directory and `git` status.
- [danielparks](https://github.com/danielparks/danielparks-zsh-theme) - Works well on dark backgrounds. Includes decorators for `git` status, user@host when in an `ssh` session, success/failure of last command, working directory, python virtualenv, execution time of last command and whether running as `root`.
- [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) - Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
- [dark-modern](https://github.com/d-exclaimation/vscode-dark-modern.zsh-theme) - Includes decorators for `git` status and current directory.
- [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
- [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Based on the `ys` and [astro](https://github.com/iplaces/astro-zsh-theme) themes.
- [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - Includes battery status and load average decorations.
- [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme) - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
- [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
- [delta-prompt](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt.
- [devil-puppet](https://github.com/skippyr/devil-puppet) - Theme decorated by a pentagram. Has decorators for username, hostname, python virtual environment, current working directory, `git` status information and the exit code of the last command run.
- [devj121](https://github.com/cjeonguk/devj121-zsh-theme) - Includes `git` decorations with branch glyphs.
- [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
- [dfrx](https://github.com/Dofoerix/Dfrx-Prompt-Theme) - Oh-My-Posh theme. Includes decorators for current directory, execution time of last command, root status, and the time.
- [dino](https://github.com/OdilonDamasceno/dino-zsh-theme) - Includes decorations for node, golang, flutter, lua, python & java, also includes `git` decorations. Requires nerdfonts.
- [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom `LSCOLORS` and `LS_COLORS` settings files, works with both dark and light terminal themes.
- [diy-ys](https://github.com/aprilnops/zsh-theme) - Variant of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) without hostname or time.
- [djkakaroto](https://github.com/djkakaroto/theme-zsh/) - Includes `git` status decorations, works with all fonts.
- [dkniffin](https://github.com/dkniffin/zsh-theme) - Includes `ruby` version and `git` status.
- [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
- [domixgit](https://github.com/tariqdomi/ohmyzsh-domixgit) - Prompt with `git` status and current directory decorators.
- [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - Minimalist theme, includes `git`, `terraform` and `aws` status decorations.
- [doom](https://github.com/CMOISDEAD/doom-zsh) - Doom-inspired. Looks similar to powerline. Has customizable segments, decorators for `git` status, `rust`, `Node.js`, `python` and `ruby` versions.
- [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
- [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - Works well on dark backgrounds, includes `git` status decorations.
- [dracula](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
- [dragon (jeop10)](https://github.com/jeop10/dragon) - Inspired by kali linux. Includes `git` status and working directory decorations.
- [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
- [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) - Reminiscent of [Powerline](https://github.com/powerline/powerline). Includes directory, `git` status, and hostname decorations.
- [droolmaw](https://github.com/isuke/droolmaw) - Configurable prompt that resembles [Powerline](https://github.com/powerline/powerline). Requires a Nerd font. Includes decorators for username, current directory, current directory path, datetime, `git` author, `git` status, `mise` language version and a configurable message based on the exit status of the last command run.
- [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
- [dtheme](https://github.com/OlukaDenis/DTheme) - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
- [duckster](https://github.com/ducky/duckster) - A fork of the [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ZSH theme that's more ducky fresh.
- [ducula](https://github.com/janjoswig/Ducula) - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
- [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
- [dyzsh](https://github.com/daotoyi/dyzsh-zsh-theme) - Based on [astro](https://github.com/iplaces/astro-zsh-theme). Includes decorators for `git` branch & hash, current directory, user, host & time.
- [easytocloud](https://github.com/easytocloud/oh-my-easytocloud) - Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme). Includes decorators for AWS environment, `git` status, username and the current directory.
- [eckig](https://github.com/fouladi/eckig) - Minimalist theme with utf-8 icons. Includes `git` status decorations and a clock.
- [efritas](https://github.com/erikfritas/efritas) - Includes username, hostname, `venv`, `rvm` and `git` status decorations.
- [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
- [elagoht](https://github.com/Elagoht/Elagoht.zsh-theme) - Includes decorators for user@hostname, current directory, virtual environment, `git` status, whether it is running in an `ssh` session, and the execution time of the last command.
- [elessar](https://github.com/fjpalacios/elessar-theme) - A `git`-aware theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme). Requires a Powerline-compatible font.
- [elm](https://github.com/gacallea/elm-zsh-theme) - Includes `git` status, user@host, date, time and path decorators.
- [elsa](https://github.com/faycito/elsa) - Includes root status, pwd and `git` status decorations.
- [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://ohmyz.sh/) theme.
- [emoji](https://github.com/meiokubo-zz/emoji.zsh-theme) - Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme with the `git` prompt symbols replaced with emoji for better clarity.
- [emojirussell](https://github.com/Bergiu/emojirussell) - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme, with status decorations for current working directory, last command exit status, `git` branch and status.
- [endless-dog](https://github.com/qwelyt/endless-dog) - oh-my-zsh-compatible theme that mimics grml-zsh-config.
- [enlightenment](https://github.com/w33tmaricich/enlightenment) - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
- [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal.
- [erfan](https://github.com/ekm507/erfan-zsh-theme) - Combination of the of [af-magic](https://github.com/andyfleming/oh-my-zsh) and [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` and `virtualenv` status decorations.
- [eriner](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired [agnoster](https://github.com/agnoster/agnoster-zsh-theme) prompt theme. Includes `git` status decorations.
- [escape](https://github.com/fesmjke/escape/) - Includes decorators for `git` information, username, time, current directory and last command exit status.
- [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
- [eucalyptus](https://github.com/relastle/eucalyptus) - Simple one-line theme for minimalist vi-mode users inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
- [even-more-emojis](https://github.com/odunlop/even-more-emojis) - Customized version of [emoji](https://github.com/meiokubo-zz/emoji.zsh-theme) which adds more emojis and more information. Includes decorators for `git` status, current directory and the exit status of last command.
- [excess](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme.
- [ez-pz](https://github.com/mangosmoothie/ez-pz) - Minimalist theme with `git` status decorations, inspired by [bureau](https://github.com/isqua/bureau).
- [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
- [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
- [fbi](https://github.com/bateman/fbi-zsh-theme) - Powerline-inspired fork of [Bureau](https://github.com/isqua/bureau) with decorators for `nvm` environment, `git` status, username@hostname and current directory.
- [fdT2K](https://github.com/FDT2k/FDT2K-theme)- Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme), preset to include virtualenv, last command status, `nvm`, `docker machine` and `git`, `hg` and `bzr` status decorations.
- [fe80](https://github.com/fe80/fe80.zsh-theme) - Includes decorators for `git` information, current directory, user@hostname, time, and the return code of last command when it is nonzero.
- [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
- [filthy](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt.
- [firefoxic](https://github.com/firefoxic/firefoxic-zsh-theme/) - Fork of [Bureau](https://github.com/isqua/bureau) with tweaks to the node and `git` decorators.
- [fish (raniconduh)](https://github.com/Raniconduh/zshfish) - ZSH theme reminiscent of the default `fish` shell theme. Includes `git` status decorations.
- [fish (sbfkcel)](https://github.com/sbfkcel/oh-my-zsh-theme) - Minimalist theme with decorators for `git` status, current directory and username.
- [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
- [fishy2](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
- [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
- [flux](https://github.com/jmg-duarte/flux-zsh) - A no-nonsense minimalist theme with `git` status decorations.
- [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - Custom setup for [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status decorations.
- [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory.
- [frank](https://github.com/ronmackley/frank-theme) - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
- [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - Fork of [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) theme.
- [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
- [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
- [fritz](https://github.com/fritzccc/fritz-zsh-theme) - Works well on dark backgrounds. Includes `git` status decorations.
- [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
- [frontcube](https://github.com/ronitkrshah/frontcube/) - Requires a nerd font. Based on the official [Frontcube](https://github.com/ornicar/oh-my-zsh/blob/master/themes/frontcube.zsh-theme) theme. Includes decorators for `git` status and current directory.
- [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - A colorful two-line theme with support for `git` and `svn`.
- [funkydrac](https://github.com/warshanks/funkydrac) - Multiple Dracula-themed omz themes based on [funky](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/funky.zsh-theme) and an [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) theme based on [alien](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/aliens.omp.json)
- [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
- [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - Colorful theme, works better on a dark background.
- [gabriel2m](https://github.com/gabriel2m/gabriel2m-oh-my-zsh-theme) - Minimalist theme with decorators for the current directory and `git` status.
- [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - Originally a fork of [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetes, virtualenv, rbenv and Java versions. Includes `git` status integration.
- [gal](https://github.com/x6r/gal) - Minimalist theme based on [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
- [gallifrey-war](https://github.com/cdubos-fr/gallifrey-war) - Inspired by [gallifrey](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#gallifrey). Includes decorators for `git` information, user@host and current directory.
- [garden](https://github.com/fecat233/garden) - Works better with a dark terminal background, includes `git` status decorations.
- [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
- [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
- [gbt](https://github.com/jtyr/gbt) - Go Bullet Train is a very customizable prompt builder inspired by Bullet Train and [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) that runs much faster. Includes many different status cars. Includes a [prompt-forwarding](https://github.com/jtyr/gbt#prompt-forwarding) feature than enables the user to forward their user-defined prompt to a remote machine and have the same-looking prompt across all machines via SSH but also in Docker, Kubectl, Vagrant, MySQL or in Screen without the need to install anything remotely.
- [gcloud-prompt](https://github.com/ocadaruma/zsh-gcloud-prompt) - Shows the current gcloud configuration in the prompt.
- [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - Breaks out the oh-my-zsh `gentoo` theme into a separate repository for non-omz users.
- [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
- [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) theme.
- [gerry](https://github.com/GerryLarios/gerry-prompt) - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#bureau), includes decorations for `git` status, current time, username, hostname and current directory.
- [get-to-work](https://github.com/Diogo13Antunes/Get_To_Work) - Minimalistic design, includes decorators for `git` status, virtual environment and the time.
- [gg](https://github.com/YourBrightSmile/ggZshTheme) - Includes decorators for time and `git` status.
- [ghoti](https://github.com/lonr/ghoti) - Mimics the `fish-shell` default prompt. Includes `git` decorations.
- [gianu-alternative](https://github.com/zbentzinger/gianu-alternative-theme) - An alternative to [OMZ Gianu](https://github.com/ohmyzsh/ohmyzsh/blob/61dd3682e69aa990a8a3589c5c61ea2e1edf8312/themes/gianu.zsh-theme) that changes prompt based on privilege. Includes `git` status and current directory decorators.
- [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - Inspired by [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), includes `git` decorations, IP address, host and path.
- [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - A variant of [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
- [gimme](https://github.com/nralbrecht/gimmezsh) - A simplistic theme for ZSH with `git` integration. Inspired by the [gitsome](https://github.com/mtully/gitsome) theme.
- [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
- [git-kali](https://github.com/Green0wl/zsh-git-kali-prompt) - Based on [An informative `git` prompt for kali](https://github.com/olivierverdier/zsh-git-prompt). Includes decorators for `git` status, username@host, and the current directory.
- [git-prompt (awgn)](https://github.com/awgn/git-prompt) - A fast `git` prompt for `bash`, `zsh` and `fish`.
- [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
- [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - A fast, customizable, pure-shell, asynchronous `git`-aware prompt for ZSH heavily inspired by Olivier Verdier's [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) and very similar to the "Informative VCS" prompt of fish shell.
- [git-prompt-kit](https://github.com/olets/git-prompt-kit) - A configurable set of components for creating feature rich, high performance Git-aware zsh prompts (aka themes) with minimal coding.
- [git-simple](https://github.com/ZakharEl/git-simple-theme) - Simple theme that includes detailed `git` status decorations.
- [gitbash](https://github.com/eddieantonio/gitbash-zsh-theme/) - Mimics the default prompt from [Git for Windows](https://gitforwindows.org/). Includes `git` status, user@host and current directory decorators.
- [github](https://github.com/Debdut/github.zsh-theme/) - A GitHub-inspired theme. Shows decorators for (truncated) current directory, hostname and `git` status. Includes both light and dark modes and detects system settings for that on macOS and Linux.
- [gitneko](https://github.com/gynamics/zsh-gitneko/) - Has a neko `(^>ω<^)` prompt with `git` status information.
- [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
- [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - Shows command and `git` status decorations.
- [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
- [gitster (zimfw)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) prompt theme
- [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - Forked from the original [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) theme.
- [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) - Includes `git` status decorations and full path to current directory.
- [glider](https://github.com/MrRedacted/zsh-glider) - Based on [strug](https://github.com/triplepointfive/oh-my-zsh/blob/master/themes/strug.zsh-theme). Includes decorators for `git` status, username, hostname and current directory.
- [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host decorators.
- [gndx](https://github.com/gndx/gndx-zsh-theme) - Includes `git` status, hostname, directory and last command exit status decorations.
- [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) from oh-my-zsh.
- [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH. Uncludes `git` status, user@host, path and date decorators.
- [goldenprompt](https://github.com/Goldeneye128/goldenprompt) - A simple prompt that incorporates fish-like functionality and decorators for `git` status, current directory.
- [goprompt](https://github.com/NonLogicalDev/shell.async-goprompt) - Lightning fast. Includes decorators for truncated current directory, last command duration & exit status, vim-mode indicators, `git` information, datetime and parent process name.
- [gops](https://github.com/noxer/gops) - Fast powerline-like prompt. Includes `git` status, current directory, root status decorations.
- [gorchak](https://github.com/evgenygorchakov/oh-my-zsh-gorchak-theme/) - Inspired by [robbyrussell(https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell)] and [af-magic](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#af-magic). Includes decorators for `git` information and Node.js version.
- [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - Simple yet informative theme that includes `git` decorations and the return status of the last command.
- [green-lambda](https://github.com/Ishidawg/minimal-green-lambda) - Minimalist Lambda theme. Includes `git` decorations.
- [greencastle](https://github.com/GustavGroenborg/greencastle-zsh-theme/) - Minimalistic theme, that supports really, **really**, long branch names, without severely truncating the prompt. The theme is inspired by the [jonathan theme](https://github.com/thlorenz/oh-my-zsh/blob/master/themes/jonathan.zsh-theme) and the [robby russel theme](https://github.com/thlorenz/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme). Includes decorators for current directory, `git` information and the exit status of the last command run.
- [greenclean](https://github.com/dmicha16/greenclean) - Fork of [akz92/clean](https://github.com/akz92/clean) with a bit more green and permanent clock on the right.
- [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - Minimalist, includes `git` status decorations.
- [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status, user id and working directory decorators.
- [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) - Sets colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
- [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
- [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - Minimalist, includes `git` status decorations.
- [gugulenok](https://github.com/gugulen0k/gugulenok/) - Has both a dark and a light mode. Includes decorators for `git` status, time and current directory.
- [guri](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure)'s design.
- [gus](https://github.com/gusye1234/Gus-zsh-theme/) - Hackable transient theme. Includes decorators for conda, `git` information and current directory.
- [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run decorators embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
- [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - Minimalist theme with `git` decorations.
- [halil](https://github.com/5m0k3r/zsh-themes) - Fork of oh-my-zsh's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) theme.
- [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme) - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
- [handy](https://github.com/hanleylee/handy) - Colorful and lightweight theme. Shows root status, `git` status, current directory and `user@hostname` decorations.
- [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
- [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - Based on oxide, includes `git` status decorations and current user/host information.
- [happy-coding](https://github.com/lexhuismans/happy-coding/) - Stripped down version of [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion). Includes decorators for time, `git` branch, last command execution time and last command exit status.
- [haribo](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt.
- [hcompact](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
- [headline](https://github.com/Moarram/headline) - A responsive ZSH theme featuring Git status information and a colored line above the prompt.
- [heapbytes](https://github.com/heapbytes/heapbytes-zsh) - Includes decorators for current directory, tun0 ip if on a VPN, wlan ip when not on VPN and `git` information.
- [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
- [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau), with added `git` status decorations and `npm` status.
- [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
- [hematite](https://github.com/bigdave/hematite) - Minimalist promot that tries to show only the status decorations that are actively useful at a given time.
- [hex](https://github.com/hectorBrown/hex-zsh) - Heavily based on [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira), and [gruvbox](https://github.com/sbugzu/gruvbox-zsh), which in turn is based on [agnoster](https://gist.github.com/agnoster/3712874). Includes decorators for current directory, `git` status information, active python virtualenv, exit status of the last command run. Requires a Powerline-compatible font.
- [hexagon](https://github.com/diogoazevedos/hexagon) - Minimalist ZSH theme based on [geometry](https://github.com/geometry-zsh/geometry).
- [hfulldate](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
- [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
- [hietan](https://github.com/Hietan/Hietan_ZshTheme) - Includes decorators for current directory, date & time, `git` status and the exit value of the last command run. Requires a Nerd Font.
- [hijack](https://github.com/thegodheehee/hijack-zsh) - Includes decorators for user@hostname, current directory, and `git` information.
- [hina](https://github.com/ucpr/hina) - Written in `golang`, includes `git` status decoration and kubernetes context.
- [hip-fellow](https://github.com/haitaim/hip-fellow) - Includes `git` status decorations and works with standard fonts.
- [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
- [ho-my-zsh](https://github.com/Mboukhal/hoMyZsh_theme) - Includes decorators for current directory and `git` information.
- [hoffish](https://github.com/emilHof/hoffish-zsh-theme) - If the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme and [fish](https://fishshell.com/) shell had a ZSH theme for a child. Includes decorators for `git` status, trimmed path to current directory, root status, exit status of the last command run and the active python virtualenv. Requires a Powerline font and the [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [shrink-path](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/shrink-path/shrink-path.plugin.zsh) plugins.
- [hogbal](https://github.com/hogbal/hogbal.zsh-theme) - Works best with a dark background and a 256 color terminal program. Includes decorators for `virtualenv`, `git` information, `username@hostname` and current directory.
- [home](https://github.com/sheerun/home) - Pretty and short one-line theme that makes you feel at home.
- [hometown](https://github.com/olets/hometown-prompt) - A feature rich, high performance `git`-aware ZSH theme with segments for the user, host, time, the current working directory and its parent, and detailed full Git status within a Git repo.
- [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
- [hoozeeth](https://github.com/hooay233/Hoozeeth) - Minimalist theme, includes decorators for user@hostname, the date & time, and the current working directory.
- [horizontal](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
- [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
- [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
- [htb](https://github.com/ibyf0r3ns1cs/zsh-htb-theme) - Inspired by the pwnbox on a HackTheBox machine. Includes decorators for user@host, IP address and the current directory.
- [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
- [hug](https://github.com/xxninjabunnyxx/hug-zsh) - When you're working and need a hug. Includes `git` status.
- [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with left-aligned `condaenv`, `virtualenv` and `git` status. Requires [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) plugin.
- [hydrogen](https://github.com/xylous/hydrogen) - A simple multiline ZSH theme. It shows username, hostname, current directory and `git` status decorations.
- [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
- [hyperzsh](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
- [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
- [iay](https://github.com/aaqaishtyaq/iay) - A `{ba,z}sh` prompt written in Rust. Includes decorations for the current directory and `git` status.
- [ice](https://github.com/Lenart12/ice.zsh-theme) - Very lightly modified [bureau](https://github.com/isqua/bureau) theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
- [ichirei](https://github.com/ichirei/ichirei.zsh-theme) - Colorful. Includes decorators for `git` status, time & current directory. Requires a Nerd Font.
- [icicle](https://github.com/JamesConlan96/Icicle) - Includes `git` status decorations, and whether running as root.
- [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
- [igeek](https://github.com/Saleh7/igeek-zsh-theme) - Displays system information when starting a new terminal session.
- [iggy](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
- [igorsilva](https://github.com/igor9silva/igorsilva-zsh-theme) - Shows current directory, customizable delimiter, current branch, and `git` status decorators.
- [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - Includes `git`, `nvm` and `venv` decorations.
- [illusion](https://github.com/shabane/illusion) - Includes username, current working directory, `git` status and last command status decorators.
- [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - Fork of [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
- [imp](https://github.com/igormp/Imp) - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
- [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
- [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
- [integral](https://github.com/Readf0x/integral-prompt) - Math-inspired, includes decorators for time, current directory and `git` status.
- [inthedeepspace](https://github.com/alionapermes/inthedeepspace/) - Based on [intheloop](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#user-content-intheloop) and inspired by [vim-deep-space](https://github.com/tyrannicaltoucan/vim-deep-space).
- [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
- [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
- [itlbv](https://github.com/itlbv/itlbv-ohmyzsh-theme) - Minimalist. Includes decorators for `git` status and the current directory.
- [ittecture](https://github.com/ittecture/ittecture-omz-theme) - Includes decorators for current directory and `git` information.
- [ivabus](https://github.com/ivabus/ivabus-zsh-theme) - Inspired by the GitHub Codespaces prompt. Includes decorators for `git` status, username and current directory.
- [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy) - Works well on dark backgrounds. Includes user@host, `git` status and time decorators. Based on the [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) theme.
- [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme) - Based on refined and ys themes, includes `git` status decorations. Includes an optional iterm2 color scheme.
- [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - Shows the time, the current directory, and `git` branch information including the branch name and a red + if the branch has un-pushed changes.
- [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
- [jax](https://github.com/jhammerberg/jax-theme) Reminiscent of Powerline. Includes decorators for current directory and current user.
- [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
- [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the `ys` theme.
- [jeff](https://github.com/jbaranski/jeff-zsh-theme) - Includes decorators for user@host, time, current directory and `git` status. Based on [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira).
- [jerome](https://github.com/jeromescuggs/jerome-theme) - Colorful theme based on the [dieter](https://github.com/jeromescuggs/jerome-theme) theme, but with a yellow hostname. Includes `git` decorations.
- [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
- [jnooree](https://github.com/jnooree/jnooree-zsh-theme) - Minimalist theme with colors adapted from the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Includes decorators for `git` status, whether running as non-default user and current working directory.
- [joje](https://github.com/joje6/joje.zsh-theme) - Includes decorators for `git` status and current directory.
- [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - A simplified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
- [jovial](https://github.com/zthxxx/jovial) - Shows decorators for host, user, path, development environment, `git` branch, and which `python` venv is active.
- [jpegleg](https://github.com/jpegleg/zshrc) - Similar to dark blood theme, includes timestamp and `git` decorations.
- [js-magic](https://github.com/JSextonn/js-magic) - A simplified take on [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes current working directory and `git` status decorations.
- [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
- [july](https://github.com/skippyr/july) - Minimalist prompt. Includes decorators for user, host and current directory.
- [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
- [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner) - Counts down the days until Christmas. Includes `git` status decorations.
- [jwalter](https://github.com/jeffwalter/zsh-jwalter) - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
- [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
- [kali-like](https://github.com/clamy54/kali-like-zsh-theme) - Inspired by the Kali Linux default ZSH theme. Includes decorators for user@host, current directory and `git` information.
- [kali](https://github.com/h4ck3r0/kali-theme) - Includes `git` decorations.
- [kalsowerus](https://github.com/kalsowerus/kalsowerus.zsh-theme) - Colorful powerline-inspired multi-line theme, includes decorations for `git` status, directory, last command exit status and `nvm` information.
- [karu](https://github.com/zaari/karu) - Minimalist single line ZSH prompt.
- [kawaii](https://github.com/LeonidPilyugin/kawaii-oh-my-zsh/) - Has terminal and virtual console modes. Includes decorators for username, directory, last command exit status, timestamp and `git` status.
- [keloran](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes.
- [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
- [kevin](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes.
- [kgzsh](https://github.com/Kashugoyal/kgzsh) - Includes `git` status deorations, works well on darker backgrounds.
- [kido](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
- [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
- [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user@machine in `ssh` sessions and docker containers.
- [kirkdawson](https://github.com/kdawson133/KirkDawson) - Powerline-inspired. Includes prompt decorations for `git` status, last command exit status, user@hostname, working directory and whether the user is running as root.
- [kiss](https://github.com/rileytwo/kiss) - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
- [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
- [ko](https://github.com/JoshBenn/KoTheme-for-Oh-My-Zsh/) - Includes decorators for `git` status and current directory.
- [korittg](https://github.com/dkorittki/korittg-zsh-theme) - Minimalistic but informative. Includes decorations for `git` status, current directory and the `kubectl` context and namespace.
- [kote](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
- [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - Two line theme designed for dark terminals, has `git` decorations.
- [krak3n](https://github.com/krak3n/zsh-theme) - Shows golang version and the current `git` branch.
- [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
- [ksposh](https://github.com/KSposh/ksposh-zsh-theme) - Includes decorators for python virtual environment, `git` information, current directory and username.
- [kube](https://github.com/tigerjz32/kube-zsh-theme) - Based on [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal), includes `kubectl` context. Has time, directory, and `git` status decorations.
- [kumavis](https://github.com/kumavis/kumavis-zsh-theme) - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
- [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
- [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
- [lacerate](https://github.com/Petrushevsky-A/Lacerate-zsh-theme) - Minimalist theme with decorations for `git`, `hg` and python `venv` status.
- [laconic](https://github.com/Saka7/laconic.zsh-theme) - Simple theme with `git` status and current directory decorators.
- [lagnoda](https://github.com/jashezan/lagnoda) Inspired by [agnoster](https://gist.github.com/agnoster/3712874) and `lambda` themes. Includes decorators for username@hostname, current directory, `git`, `hg`, or `bzr` status, current virtualenv, exit status of last command run, and current aws profile.
- [lagune](https://github.com/noplay/lagune) - A minimal ZSH theme.
- [lambda (bluedragon1221)](https://github.com/bluedragon1221/zsh-lambda-prompt) - Includes decorators for current directory and `git` status.
- [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) -  Inspired by the [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
- [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
- [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit) - Includes blazing fast, detailed `git` information. Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) and the [gitstatus](https://github.com/romkatv/gitstatus) plugin.
- [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information.
- [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - Simple theme based on lambda with `git` status and virtualenv information.
- [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - A simple ZSH theme, optimized for `git` usage.
- [lambda-p](https://github.com/paimanbandi/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) and [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) themes. Includes `git` status decorations.
- [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on [pure](https://github.com/sindresorhus/pure), with added Node.js version decorator.
- [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes, includes `git` status decorations.
- [lambda-zen](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) with graphical `git` status decorations.
- [lambder](https://github.com/avillen/zsh-theme-lambder) - Includes `git` status decorations, works best with a dark terminal theme.
- [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme) - Works best on a dark background. Based on the great `ys` theme and [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh). Shows root status and `git` status decorations.
- [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
- [leafia](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information.
- [lean](https://github.com/miekg/lean) - Inspired by [pure](https://github.com/sindresorhus/pure). Has decorators for `git` status information, exit status of last command run, and the elapsed time of last command.
- [lemon](https://github.com/carlosvitr/lemon_zsh) - Many beautiful colors for you to enjoy. done with care and patience. Includes `git` status and ruby version decorations.
- [leon](https://github.com/prince-an/Leon_zshTheme) - Works well on light background. Includes `git` status, time, username@host, working directory and last command exit status decorations.
- [less-noise](https://github.com/ablil/less-noise) - Minimalist theme with decorators for `git` status, current directory and the current time.
- [leverage](https://github.com/gschnall/leverage) - Based on [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
- [lewis](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
- [lgbtq](https://github.com/PhoenixSmaug/zsh-lgbtq-themes) - A collection of lgbtq themes for your terminal.
- [light](https://github.com/InfinityUniverse0/light-zsh) - Works best on a light background. Includes decorators for username@hostname, `git` status and the current directory.
- [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - Includes decorations for kernel, OS version, uptime and `git`.
- [lighthaus](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) theme. Shows `git` information, GitHub/GitLab logo and shows changes as and when they occur.
- [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
- [lildragon](https://github.com/skippyr/lildragon) - Dragon-themed. Includes decorators for `git` status, current directory & username. Requires a font with emoji glyphs.
- [lilith](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) and [hyperzsh](https://github.com/tylerreckart/hyperzsh).
- [lime](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
- [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
- [linear](https://github.com/MrYazdan/zsh-linear-theme) - Reminiscent of Powerline. Includes segments with `git` status, Pythonvirtualenv, current directory and current time.
- [link](https://github.com/kylegl/link-zsh-theme) - Minimalist. Includes `git` status and last command exit decorations.
- [linuxer](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood's `ys`, and the [Bureau](https://github.com/isqua/bureau) theme.
- [linuxero](https://github.com/andreshincapier/linuxero) - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
- [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
- [lish](https://github.com/bashelled/lish) - A casual theme. No roughness, just smooth. Includes `git`, user@host, last command exit status, current directory, current time and root status decorators.
- [liver](https://github.com/RenoirTan/liver.zsh-theme) - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
- [llama](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas.
- [logico](https://github.com/logico/logico-zsh-theme) - Has `git` decorations. Shows remote status and indicator for vi-mode.
- [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
- [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - Includes `git` and compact `pwd` decorations.
- [lorond](https://github.com/lorond/zsh-lorond/) - Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes `git` status, works with standard fonts.
- [lperezp](https://github.com/lperezp/lperezp-zsh-theme) - Includes decorators for user@hostname, `git` status, current directory and the exit status of the last command run.
- [lpha3cho](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme for pentesters which includes the date, time, and IP address for pentest logging.
- [luceast](https://github.com/LucEast/luceast-zsh-theme) - Optimized for `git`. Includes decorations for username, host, time & working directory.
- [luckycoding](https://github.com/ZitherPeng/oh-my-zsh-luckycoding-theme) - Based on the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme, includes `git` decorations and the last command's exit code.
- [ludvig](https://github.com/daviludvig/ludvig-theme-zsh) - Minimalist. Includes decorators for `git` status, current directory, current time and the last command's exit status.
- [ludwigws](https://github.com/LudwigWS/my-zsh-theme) - Variant of [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) theme. Has `git` decorations, requires a powerline-compatible terminal font.
- [luke](https://github.com/xueguangl23/luke_zsh_theme) - Includes `git` decorations. Based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
- [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) theme. Includes decorations for `git` status and the status of the last command run.
- [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) - Minimalist theme.
- [macos](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
- [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - Includes `git` status and last command execution time decorations.
- [madas](https://github.com/utauyo/madas-zsh-theme) - Inspired by af-magic. Includes decorators for `git` status, user@host, and whether the last command failed.
- [magento](https://github.com/cmuench/zsh-magento-cloud/blob/main/zsh-magento-cloud.plugin.zsh) - Add Magento Cloud Command Line Interface ([magento-cloud CLI](https://experienceleague.adobe.com/docs/commerce-cloud-service/user-guide/dev-tools/cloud-cli.html?lang=en)) completions.
- [magicmace](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
- [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
- [magpie](https://github.com/wdjcodes/magpie) - Minimalist theme with custom logic to display paths relative to the root of the current `git`. Includes decorators for time, current directory, username@hostname and `git` status.
- [mainnika](https://github.com/mainnika/zsh-theme-mainnika/) - Includes decorators for last command exit status and the 1, 5 and 15 minute load averages.
- [maivana](https://github.com/nylo-andry/zsh-themes) - Includes `kubectl` context, `git` status decorations.
- [majemoji](https://github.com/metalogica/majemoji) - Adds a random emoji to each session's prompt. Includes `git` status decorations.
- [malev](https://github.com/mvinan/malev-zsh-theme) - Has minimalist and normal variants. Includes decorators for hostname, directory, `git` status and the last command's exit status.
- [mantis](https://github.com/dann254/mantis-zsh-theme) - Minimal theme with `git` status and information decorators.
- [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
- [matrix](https://github.com/pot-code/matrix-zsh-theme) - Variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
- [matter](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
- [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) and [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) themes.
- [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv](https://github.com/jenv/jenv) integration.
- [mdmini](https://github.com/MarioDena/MDmini) - Includes `git` and `ssh` status decorations.
- [meganerd](https://github.com/meganerd/meganerd-zsh/) - Inspired by jonathan. Includes decorators for `git` status, user@hostname, current directory, time and the last command's exit status.
- [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) plugin.
- [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - Includes `git` status decorations, shows exit code of last command if nonzero.
- [mexassi](https://github.com/Mexassi/mexassi-zsh-theme) - Checks the `/sys/class/power_supply` folders to determine if the system is installed on a laptop or desktop machine. Reads the battery percentage grepping acpi command and displays it in the prompt. Includes `git` decorations.
- [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - Includes `rvm` and `git` status decorations.
- [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX-friendly cross-platform [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
- [michelebira](https://github.com/mortinger91/michelebira) - Variation of the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme. Includes decorators for `git` status, username, current directory and the return code of the last command run.
- [midin](https://github.com/xlshiz/midin) - Works well on dark terminal background, includes `git` status decorations.
- [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) - Minimalist, includes `git` status decorations.
- [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
- [min](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt.
- [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
- [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt) - Minimalist. Includes `vcs` status decorations.
- [minima](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
- [minimal (glsorre)](https://github.com/glsorre/minimal/) - A minimal asynchronous ZSH theme optimized for use with the [Fira Code](https://github.com/tonsky/FiraCode) font and the [Solarized Light](https://ethanschoonover.com/solarized) terminal theme.
- [minimal (subnixr)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
- [minimal-improved](https://github.com/gdsrosa/minimal_improved) - Theme for dark terminals, includes `git` decorations in the right-side prompt.
- [minimal-os](https://github.com/nkurata/zsh-theme) - A minimalist prompt with helpful `git` status and system-specific decorators.
- [minimal-terminal](https://github.com/Lissy93/minimal-terminal-prompt) - Includes decorators for username@host, current directory, `git` information and the last command's exit code.
- [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
- [minimalx](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh.
- [mint](https://github.com/FalconLee1011/mint-zsh-theme) - Includes decorators for current directory, whether running on a laptop or a desktop, and `git` status.
- [mira](https://github.com/mbStavola/mira) - A modified [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) with time info and a simplified start prompt.
- [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) - Includes prompt decorations for `git` status, last command exit code, whether `sudo` timestamp file is present and current active Python virtual environment.
- [miramare](https://github.com/franbach/oh-my-deepin-miramare) - Includes `git` status decorations. Works best with [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
- [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
- [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
- [mnml](https://github.com/mnml-theme/prompt) - Minimal theme with `git` status decorations.
- [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
- [mochi2](https://github.com/mochidaz/zsh-themes) - Minimalist theme. Includes `git` and `hg` status decorations.
- [moderno](https://github.com/obrassard/moderno-zsh) - A simple and modern ZSH theme inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme from Oh-My-ZSH. Includes `git` status decorations.
- [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned. Requires [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) plugin.
- [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
- [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme) - Reminiscent of powerline. Includes decorations for `git` status, username, and working directory.
- [monsi](https://github.com/rafa-wine/monsi_oh-my-zsh_theme) - Includes `git` status, last command exit status and current directory decorators.
- [moon-lite](https://github.com/anotherlusitano/moon-light) - Minimalist. Includes decorators for `git` status, current directory and the exit status of the last command run.
- [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
- [moux](https://github.com/gagbo/moux) - Works well with a dark terminal background, includes `git` decorations in `RPROMPT`.
- [msys2](https://github.com/water-logger/MSYS2-Theme/) - Inspired by MSYS2. Includes decorators for user@host, `git` status and the current directory.
- [mu](https://github.com/seamile/mu-zsh-theme) - Improves display of multiple `git` statuses. Inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme). Requires a powerline-compatible font.
- [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
- [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
- [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
- [musy](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
- [my](https://github.com/fabiendelpierre/my-zsh-theme/) - Variant of [kolo](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#kolo).
- [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
- [mzt](https://github.com/honbey/mzt) - Sets up `LS_COLORS`, colorizes `diff` and includes `git` status and current working directory decorations.
- [nablaman](https://github.com/kokkonisd/nablaman-zsh-theme) - Similar to [powerlevel10k](https://github.com/romkatv/powerlevel10k). Includes decorators for the last command's exit status, user@hostname, `git` status and the current directory. Works best with a dark terminal theme.
- [nanika](https://github.com/justforuse/nanika-zsh-theme/) - Optimized variant of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell). Includes `git` status decorations.
- [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
- [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - Minimalist theme with text `git` status decorations.
- [nctu](https://github.com/leovincentseles/nctu.zsh-theme) - Lightweight theme with an emphasis on speed. Includes `git` status decorations.
- [neewbie](https://github.com/neewbee/neewbee.zsh-theme) - Minimal theme with `git` decorations. Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
- [neo++](https://gitlab.com/migoa/neo) - Simpler, more intuitive, and less clustered than the one above.
- [neon-potato](https://github.com/algosuna/neon-potato) - Colorful and minimalist theme. Includes `git` decorations.
- [neon](https://github.com/sahariko/neon) - A pretty and minimal ZSH theme with `git` decorations.
- [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH which uses [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).
- [nerdp](https://github.com/joknarf/nerdp) - Nerd powerline-style prompt. Requires a nerd font. Includes decorators for `git` status, username@hostname, current directory, Python virtualenv, filesystem usage check, 1 minute CPU load, available memory and the time.
- [nerdps1](https://github.com/joknarf/nerdps1) - Reminiscent of powerline. Requires a nerd font. Includes decorators for user@hostname, `git` information, truncated current directory, python virtualenv, exit status of last command run and the time.
- [nescalante](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
- [netmask](https://github.com/swomf/netmask-zsh-theme) - Termux-first theme. Includes decorators for ip address, full path to current directory, `git` status and python virtual environment.
- [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - Includes `git` decorations and `vi`-mode indicator.
- [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
- [newton](https://github.com/sebastienfilion/zsh.newton) - Includes `git` status and external IP address decorations.
- [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
- [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
- [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
- [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
- [ninik](https://github.com/NimaNikfar/ninik-zsh-theme) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [ubunly](https://github.com/alejandromume/ubunly-zsh-theme). Includes decorators for OS, current directory, python virtualenv and `git` status. Requires a Nerd Font or Powerline-patched font.
- [niotna](https://github.com/niotna/niotna-theme) - Includes decorators for `git` status and current directory. Customizable colors.
- [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
- [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
- [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh's Node.js theme, broken out to make it easier to use with other plugin managers.
- [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on the ys theme, with added Node.js version (from NVM plugin).
- [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
- [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
- [normanius](https://github.com/normanius/normanius-zsh-theme) - Derived from [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes decorators for `git` status, `user@host`, python `virtualenv`, and ruby `rvm` version.
- [nostalgia](https://github.com/skippyr/nostalgia) - Minimalist theme inspired by Windows CMD prompt. Includes decorators for user@hostname, `git` status, current directory and python virtualenv.
- [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
- [nova](https://github.com/body20002/nova) - Includes `git` status decroations. Overrides `LS_COLORS` and `LSCOLORS` settings.
- [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
- [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or `~` when outside `git` repo), time since last commit, current SHA, branch and branch state.
- [nunorc](https://github.com/nunorc/nunorc.zsh-theme) - Minimalist theme, works well on dark backgrounds. Includes `git`, `mercurial` and `svn` satus decorations.
- [nuqle](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - A simple theme for prezto and oh-my-zsh.
- [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
- [oblong](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last command run, `git` branch and its clean/dirty status.
- [odie](https://github.com/masterodie/zsh-theme-odie/) - Works well on a dark background. Includes `git` status, python virtualenv and `vi`-mode status decorations.
- [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
- [odra](https://github.com/ErikBenavides/odra.zsh-theme) - Colorful, works well on dark backgrounds. Includes decorators for `git` status, current directory, username and exit status of the last command.
- [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - Multiline theme with `git` decorations.
- [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and ZSH.
- [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
- [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
- [ohmypc](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
- [om](https://github.com/sirshikher/zsh-om) - Minimal theme, works with dark backgrounds, includes `git` status decorations.
- [omszt](https://github.com/MU001999/omszt) - Minimalist theme with `git` decorations.
- [omuse](https://github.com/ouuan/omuse-zsh-theme) - Based on Oh-My-ZSH's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme). Has decorations for `git` status, time, absolute pwd, RAM usage, time used by last command, and last command exit status.
- [operator](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline).
- [ortiz (andres-ortizl)](https://github.com/andres-ortizl/ortiz-zsh-theme) - Fork of [eriner](https://github.com/zimfw/eriner) with decorations for the interval between commands and k8s context.
- [ortiz (guezwhoz)](https://github.com/guesswhozzz/guezwhoz-zsh-theme) - Simplified fork of [eriner](https://github.com/zimfw/eriner) with `git` status, `kubectl` context and elapsed time decorations.
- [osx2](https://github.com/RizkiIqbal02/zsh-theme-custom) - Based on archcraft. Minimalist. Includes decorator for current directory.
- [otter](https://github.com/OtterArkar/otter-zsh/) - Otter-themed theme with `git` status, user@host and current directory decorators.
- [outer-space](https://github.com/skippyr/outer-space) - Includes decorators for user@hostname, active python virtual environment, current directory and `git` status.
- [owczarczak](https://github.com/ThemysciraData/owczarczak.zsh-theme) - Inspired by bira, dieter and [fino-time](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme). Includes `venv` and vcs status decorations.
- [owi](https://github.com/owitech/zsh-theme/) - Minimalist theme with `git` status decorations.
- [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
- [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
- [ozono](https://github.com/sfabrizio/ozono-zsh-theme) - 🌏 OZ0NO - Let's Breathe a clean ZSH.
- [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - A theme for the [powerlevel10k](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
- [pacmandoh](https://github.com/pacmandoh/omz-theme-pacmandoh) - Enhance your command-line with a sleek theme. Includes decorators for `git` integration, permissions feedback, Python environment support, and dynamic prompts, all in one, customizable with a single installation script and selectable styles.
- [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
- [page](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
- [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
- [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - Shows detailed `git` status information with icons in the prompt.
- [panda](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
- [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
- [paramour](https://github.com/espeon/paramour) - Simple and clean, has decorators for `git` status, username, time, current directory and username. Requires a nerd font in your terminal.
- [paroape](https://github.com/ParoaPe/ParoaPe-zsh-theme) - Based on [lpha3cho](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters)
- [parrot-htb](https://github.com/Lloyd-Leo/parrot-htb-zsh-theme) - Includes decorators for current directory, `git` status and username@hostname.
- [parrot](https://github.com/trabdlkarim/parrot-zsh-theme) - Based on Parrot OS bash theme. Includes decorators for user@host, `git` information, exit status of last command, time and current directory.
- [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) - Includes decorations for current time, `git` status, last command run time in milliseconds, and the exit status of the last command. Requires coreutils on macOS.
- [pastel](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free). Includes `git` decorations.
- [paxton](https://github.com/p1xt4n/ohmyzsh-theme-paxton) - Inspired by powerline. Includes segments for `git` branch, time, last command exit status and current directory. Requires a powerline-compatible font.
- [pecodez](https://github.com/pecodez/pecodez-zsh-theme) - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
- [pedantic](https://github.com/nemeshnorbert/pedantic-zsh-theme) - Customizable colors and output. Includes decorators for detailed `git` information, root status, last command's exit status, user@host, current directory and the time.
- [persi](https://github.com/persiliao/persi-zsh-theme) - Includes `git` decorations. Works with both light and dark backgrounds.
- [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - Minimal theme in the spirit of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
- [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from the [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) theme.
- [pi](https://github.com/tobyjamesthomas/pi) - A minimalist theme with `git` status decorations.
- [piboy](https://github.com/sflems/piboy-zsh-theme) - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
- [pico](https://github.com/PicoGeyer/zsh-pico-prompt) - Simple prompt modified from [zap-prompt](https://github.com/zap-zsh/zap-prompt) with decorators for `git` information, user@hostname and working directory.
- [pifabs](https://github.com/pifabs/pifabs-zsh-theme) - Minimal theme with decorators for `git` status, username, host and working directory.
- [plain-ui](https://github.com/purveshpatel511/plain-ui) - Minimalist, but includes `git` status decorations.
- [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
- [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
- [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - Simple, no-frills theme.
- [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
- [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
- [pog7x](https://github.com/pog7x/pog7x-zsh-theme) - Works with unicode. Includes decorators for `git` information, current directory, last command exit status & execution time, time, virtualenv, nvm, rvm, rust, go, kubernetes context, and elixir.
- [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
- [polyglot](https://github.com/agkozak/polyglot) - a dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `dash`, and busybox `ash` that uses basic ASCII symbols (and color, when possible) to show username, whether it is a local or remote `ssh` sesssion, abbreviated path, `git` branch and status, exit status of last command if non-zero, any virtual environment created with `virtualenv`, `venv`, `pipenv`, `poetry`, or `conda`.
- [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
- [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
- [powerbash](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
- [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
- [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ZSH theme. Can be used as a drop-in replacement for powerlevel9k, when given the same configuration options it will generate the same prompt, only faster.
- [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen), and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
- [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - Add-on for [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
- [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
- [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
- [powerline (syui)](https://github.com/syui/powerline.zsh) - A `git` aware powerline theme.
- [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
- [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) shell, and is easy to extend.
- [powerline-hs](https://github.com/rdnetto/powerline-hs) - A [Powerline](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
- [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - Written in Ruby, uses powerline characters to simulate pills with useful information.
- [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
- [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Includes decorators for `git`/`svn`/`hg`/`fossil` branch, last command exit status, shortened path to current directory and the current python virtualenv and is easy to customize/extend.
- [powerline-train](https://github.com/sherubthakur/powerline-train) - A powerline variant.
- [powerline](https://github.com/carlcarl/powerline-zsh) - A [Powerline](https://github.com/Lokaltog/vim-powerline)-like prompt, based on [powerline-bash](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
- [powermore](https://github.com/primejade/powermore-zsh) - Forked from [powerless](https://github.com/martinrotter/powerless). Simple prompt that shows `git` status and current directory.
- [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
- [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
- [predawn-shell](https://github.com/jamiewilson/predawn-shell) - Theme optimized for dark terminal themes.
- [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
- [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
- [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
- [princess](https://github.com/mellypop/princess) - Modeled after [abhiyan.zsh](https://github.com/abhiyandhakal/abhiyan.zsh) with perhaps a bit too much pink and arguably too few emojis. Includes decorators for current directory and `git` status.
- [probe](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
- [prompt_blocks](https://github.com/MiloradFilipovic/promptblocks) - A minimal node js + git theme. Includes decorators for `git` status, node version and current directory.
- [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
- [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
- [prompt](https://github.com/nathanblair/prompt) - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
- [promptly](https://github.com/manuelcattelan/promptly) - Lightweight, async ZSH theme for a prompt(ly) experience.
- [promptor](https://github.com/MickaelBlet/Promptor) - Powerline-inspired. Includes decorators for `git` status, username, hostname, working directory and time.
- [promptus](https://github.com/willeccles/promptus) - Simple, minimalist and configurable shell prompt program in C which can be used to make your prompt the same on any shell. Includes exit code and working directory decorations.
- [pronto (arzezak)](https://github.com/arzezak/pronto) - A super simple prompt with decorators for the current directory and `git` information.
- [pronto (jthat)](https://github.com/jthat/zsh-pronto) - Simple and fast theme with `git` decorations and timing information.
- [prowpt](https://github.com/alpaca-honke/prowpt) - Simple, lightweight, and customizable Powerline-like prompt, with decorators for `git` information, user, hostname, current directory, time and exit status of the last command.
- [ps1.py](https://github.com/jwodder/ps1.py) - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
- [pskfyi](https://github.com/pskfyi/zsh-theme) - Based on [lambda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#lambda). Themed for ubuntu but easily tweaked.
- [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt).
- [pure-agnoster](https://github.com/yourfin/pure-agnoster) - Mashup of [pure](https://github.com/sindresorhus/pure) and [agnoster](https://gist.github.com/3712874). Has `git` decorations and works well with both dark and light terminal backgrounds.
- [pure](https://github.com/sindresorhus/pure) - A pretty, minimal and fast ZSH prompt. Includes `git` status decorations, prompt turns red if last command failed, username and host decorations when in a remote session or container, and current folder and command when a process is running.
- [purify (banminkyoz)](https://github.com/banminkyoz/purify) - A simple, fast & cool prompt.
- [purify (kyoz)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
- [purity](https://github.com/petermbenjamin/purity) - Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the [pure](https://github.com/sindresorhus/pure) prompt.
- [purpleblood](https://github.com/HFMorais/oh-my-zsh-purpleblood-theme/) - Based on [darkblood](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/darkblood.zsh-theme). Includes decorators for `username@host`, `git` status, and current directory.
- [purr](https://github.com/mubinben/purr-zsh-theme) - Includes decorators for current directory and `git` status.
- [purs](https://github.com/xcambar/purs) - A fast [pure](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
- [pustelto](https://github.com/Pustelto/shell_theme) - Colorful theme inspired by the [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
- [pwn](https://github.com/gh05t-4/pwn-theme) - Includes decorators for user@host, `git` & `hg` status, ruby version, python virtualenv and current working directory.
- [pyhack](https://github.com/williamcanin/pyhack) - Works well with dark terminal themes. Shows Python version, Python package version (pyproject.toml) and `git` current branch information.
- [qi3ber2](https://github.com/nichus/qi3ber2) - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
- [qoomon](https://github.com/qoomon/zsh-theme-qoomon) - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings.
- [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes decorations for the current time, user, directory and `git` status.
- [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
- [rabbit](https://github.com/Hera-Moon/My-rabbit-Zsh-Theme) - Optimized for `git`. Requires a terminal program that works with unicode. Includes decorators for `git` status, current working directory and the current virtual environment.
- [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
- [radius](https://github.com/erikcc02/radius-zsh-theme) - Includes `git` status, username, hostname, and directory decorations, plus [desk](https://github.com/jamesob/desk) support.
- [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
- [ramiel](https://github.com/aknackd/zsh-themes) - Fork of the [node](https://github.com/skuridin/oh-my-zsh-node-theme).
- [random-emoji-robbyrussell](https://github.com/parwatcodes/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
- [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
- [ranger-zoxide](https://github.com/fdw/ranger-zoxide) - Adds [zoxide](https://github.com/ajeetdsouza/zoxide) support to the [ranger](https://github.com/ranger/ranger) console file manager.
- [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - Includes `git`, python, time, current host and path decorations.
- [raytek](https://github.com/Raytek/raytek-zsh-theme) - Simple and colorful theme with `git` status decorations.
- [raz](https://github.com/razman786/ohmyzsh-theme-raz) - Minimal prompt, includes `git` status decorations.
- [rb](https://github.com/rberenguel/rb-zsh-theme) - Powerline-styled ZSH theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
- [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
- [redline](https://github.com/DrissTM/redline.zsh-theme) - Minimalist theme. Includes `git` status, time, user.
- [refined-flower](https://github.com/idaMakelaWork/refined-flower) - Requires a terminal program that can handle emoji. Includes `git` status decorator.
- [refpx](https://github.com/refpx/refpx-zsh-theme) - Includes `git` status, last command status, user@hostname and directory decorations.
- [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
- [rei](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character 零(rei), the number 0. Includes `git` status decorations.
- [remiii](https://github.com/Remiii/remiii.zsh-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for [solarized](https://github.com/altercation/solarized) terminal themes.
- [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), using emojis for tracking `git` context. Only works with [Prezto](https://github.com/sorin-ionescu/prezto).
- [renanborgez](https://github.com/renanborgez/ohmyzsh-theme-renanborgez) - Works well on dark backgrounds. Includes decorators for `nvm` and `git` information.
- [rho](https://github.com/andrii-rieznik/rho-zsh-theme) - Minimalist theme. Includes decorators for `git` status, hostname and current directory.
- [ribbon](https://github.com/pyjamafish/ribbon-prompt) - Reminiscent of powerline. Includes Python `virtualenv` decorator.
- [rigel](https://github.com/othiagos/rigel-zsh-theme/) - Includes decorators for `git` information, user@hostname and current directory.
- [risbow](https://github.com/waddupp00/risbow) - A [risto](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/risto.zsh-theme) inspired ZSH theme with a lolcat like rainbow effect.
- [ritz](https://github.com/Ritzier/ritz.zsh-theme) - Includes decorators for time, current directory, `git` status, exit status and time used for last command run.
- [river-dreams](https://github.com/skippyr/river-dreams) - Includes decorators for `git` information, machine's IP address, time, disk usage on `/`, current Python `venv`, current directory, root status, and the last command's exit status.
- [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
- [riverside](https://github.com/skippyr/riverside) - A more portable descendent of [River Dreams](https://github.com/skippyr/river_dreams) inspired by robbyrussell and kafeitu. Includes decorators for `git` status, user@hostname, current directory and the current python virtual environment.
- [rkj-logik](https://github.com/logik93/rkj-logik.zsh-theme) - Based on omz's [rkj](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/rkj.zsh-theme). Includes decorators for user@host, current directory, time & date.
- [rkj-with-conda](https://github.com/cain986/rkj-with-conda-zsh-theme) - Based on omz's [rkj](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/rkj.zsh-theme) and adds conda environment and `git` status decorators.
- [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
- [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - The original [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with a fullpath in the prompt.
- [robbyrussell-plus](https://github.com/jackjyq/robbyrussell-plus-zsh-theme) - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), adds a hostname decorator.
- [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
- [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
- [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
- [rounded](https://github.com/daniilty/rounded-zsh-theme) - Includes current directory and `git` status decorations.
- [roundy](https://github.com/nullxception/roundy) - Fast, cute and roundy theme. Includes decorators for `git` status, current directory and last command execution time. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) and a unicode-capable terminal application.
- [rs](https://github.com/sam-621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
- [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
- [rummik](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
- [russtone](https://github.com/russtone/prompt-russtone) - Inspired by [pure](https://github.com/sindresorhus/pure) and [sorin](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
- [ruweird](https://github.com/ruweird/ruweird.zsh-theme) - Minimalist. Has decorators for `git` status and current directory. Shows an umbrella with raindrops and exit code of the last command if non-zero.
- [rwahasugui](https://github.com/rafawhs/rwahasugui.zsh-theme/) - Includes decorators for `git` information, current time, current working directory and active python  virtualenv.
- [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - Colorful theme, includes `git` decorations and the current directory.
- [rzh](https://github.com/patwhatev/rzh) - Theme with `git` states indicated by emojis.
- [s1ck3r](https://github.com/pseifer/s1ck3r) - Sleek, transient and space-efficient. Includes decorators for `vi`-mode, elevated permissions, last command exit status, if background jobs are running, working directory and `git` status,
- [s1ck94](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
- [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme) - Works well with dark backgrounds. Includes `git` status decorations.
- [sailormoon](https://github.com/Domanowska/zshSailorMoonThemes) - A collection of Sailor Moon themed themes.
- [samshell](https://github.com/samuelb/samshell) - A minimalist ZSH theme with `git`, kubernetes and python virtualenv decorations.
- [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
- [sashimi](https://github.com/simonmader17/sashimi-zsh-theme) - Includes decorators for `git` status and the exit status of the last command run.
- [saturn](https://github.com/gantoreno/saturn-prompt) - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
- [savior](https://github.com/Savecoders/Savior-zsh-theme) - Minimalist theme with decorators for current directory, exit status of last command run and `git` status.
- [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows decorators for `git` status, `user@host` information, the exit status of last command, and whether running as root.
- [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
- [scythe](https://github.com/kostoskistefan/scythe) - Powerline-reminiscent theme. Includes `git`, last command exit status and directory decorations.
- [sdkman (matthieusb)](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
- [sdkman (yongxingzhao)](https://github.com/yongxingzhao/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
- [searocket](https://github.com/dk949/searocket/) - Slimmed down version of [spaceship](https://github.com/denysdovhan/spaceship-prompt). Includes decorators for working directory, last command exit code, user, background jobs, `bun`, `d`, elm, go, nodejs, python, zig and `git` status. Requires `D` build chain.
- [seashell](https://github.com/jottenlips/seasonal-zshthemes) - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
- [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
- [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by the dieter theme, uses color-coding to provide information.
- [senpai](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes decorators for `git` status, the kubernetes context, AWS profile, GCP project and Azure active cloud.
- [sensa](https://github.com/miccou/sensa-theme) - Includes decorators for `git` status, GitHub username and current directory.
- [sepshell](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
- [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - A simple oh-my-zsh-compatible theme with a corresponding iTerm 2 color scheme.
- [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
- [shades of purple](https://github.com/nmcc1212/shades-of-purple-windows-terminal/) - Purple theme for Windows terminal that is reminiscent of [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
- [shadow](https://github.com/agentshadow/shadow-zsh-theme) - Includes `git` status, directory, host name, username and time decorations.
- [shayan](https://github.com/shayanh/shayan-zsh-theme) - Simple theme with `git` status decorations.
- [shelby](https://github.com/athul/shelby) - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
- [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with a `git` branch decorator. Requires a Powerline-compatible font.
- [shichi](https://github.com/arturoalviar/shichi-zsh-theme) - A simple theme with the first character being 七(shichi/nana), the number 7. The primary color is red with a yellow accent. Includes `git` status decorations.
- [shiftys](https://github.com/shifty0g/shiftys-zsh-theme/) - Tweaked version of the kali theme.
- [shini](https://github.com/bashelled/shini) - A tiny theme that just shouts out small. Includes directory, username, hostname, time and `git` decorations.
- [shinkansen](https://github.com/MRZ07/shinkansen.zsh-theme) - A fast, customizable and easily extended theme. Includes decorators for rhw python version in the active virtualenv, current ruby version if you're using `chruby`, current Node.js version, current java version, current go version, current perl version if using `chperl`, current elixir version, `git` status, time, current directory, exit code and execution time of the last command, and an optional custom message. Requires a powerline-compatible font.
- [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - Includes `git` status and `user@hostname` decorations.
- [shiro (arturDobrowolski)](https://github.com/ArturDobrowolski/shiro-zsh-theme) - Includes decorators for current directory, `git` status, and exit status and execution time of last command run.
- [shiro (shirozuki)](https://github.com/shirozuki/shiro-zsh-theme) - Includes decorators for current directory, `git` status and execution time and exit status of last command run.
- [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - Forked from [sixlive](https://github.com/sixlive/sixlive-zsh-theme). Has `git` decorations.
- [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - Based on the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme. Includes `git` and `hg` status decorations.
- [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - Includes `git` decorations.
- [shrug](https://github.com/to-var/shrug-zsh-theme) - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status and current directory decorations.
- [shuttle](https://github.com/Pandademic/Shuttle/) - Written in `golang`. Has decorators for OS, user, current directory, and the exit code of the last command run.
- [siegerts](https://github.com/siegerts/zsh-theme) - Includes `git` status decorations in right prompt.
- [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). A faster rust port of [bronze](https://github.com/reujab/bronze). Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts). Very configurable, includes `git` status decorations.
- [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
- [simpl](https://github.com/MrNeoTr1n0/simplzshell) - Minimalist theme focusing on elegance and simplicity. Decorators for root status, current directory and `git` status.
- [simple (daopengz)](https://github.com/DaopengZ/simple-zsh-theme) - Works well with both light and dark terminal themes. Includes `vcs`, `username` and `path` decorations.
- [simple (drNoob13)](https://github.com/drNoob13/SimpleZshTheme/) - Includes decorators for python virtual environment, `git` status and current directory.
- [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - Minimalist theme based on [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
- [simple (rkitover)](https://github.com/rkitover/sh-prompt-simple) - A simple, lightweight, and nice looking prompt that runs quickly even in very slow shells like MSYS2, Cygwin and WSL. It shows decorations for the short name of the current environment (distribution, OS, etc.) the `git` branch when in a `git` checkout, as well as the last command exit status (green checkmark for success and red X mark for non-zero exit).
- [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - Simple and minimalist theme with `git`, `username` and execution status decorations.
- [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) - Minimalist prompt, includes `git` status decorations.
- [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - Minimal prompt, doesn't require special fonts.
- [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
- [simple-chack](https://github.com/chack93/simple-chack.zsh-theme) - Works well with solarized terminal color scheme. Includes `git` status decorations.
- [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme). Includes `git` decorations.
- [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
- [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
- [simply-perfect](https://github.com/SetOfAllSets/simply-perfect-zsh-theme/) - Reminiscent of Powerline and Bullettrain. Includes decorators for `git` status, current directory, last command exit status, current time and username.
- [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme. Includes `git` status decorations.
- [sit](https://github.com/svensen/sit.zsh-theme) - Minimalist theme with `git`, command exit status and path decorations.
- [sixlive](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
- [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
- [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
- [skgeek](https://github.com/skippyr/skgeek) - Includes decorators for hostname, directory and `git` branch.
- [skiff](https://github.com/xiaoshihou514/skiff) - Lightweight ZSH theme with `git` status and current directory decorators.
- [skill (asafaeirad)](https://github.com/ASafaeirad/oh-my-zsh-skill-theme) - Includes decorations for working directory, `git` working branch, working directory status and tracking branch status.
- [skill (frontendmonster)](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - Optimized for a dark terminal, displays `git` status decorations.
- [skull](https://github.com/tahadostifam/skull-zsh) - Includes `git` status, python virtual environment and ruby `rvm` status decorations.
- [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
- [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) and [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt). Requires `cargo` for installation.
- [slimline](https://github.com/mengelbrecht/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
- [sm](https://github.com/blyndusk/sm-theme) - A **Simplist** & **Minimalist** theme for your **favorite** terminal. Includes `git` status decorations.
- [smail](https://github.com/nimacpp/themes-zsh) - Includes decorators for `git` status, current directory and exit status of last command run.
- [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - A variant of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme in [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
- [smelly](https://github.com/Vicfs/smelly-theme/) - Minimalist prompt that includes decorators for Python `venv` and `git` status.
- [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
- [snowflake](https://github.com/angelina-tsuboi/snowflake-zsh-theme) - An elegant, simple, and neat ZSH theme including an aesthetically pleasing cool color palette that harmonizes with dark themes.
- [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
- [softblobby](https://github.com/gsalami00/softblobby/) - A theme for people who love unicorns, pink and purple. Includes decorators for `git` information, current directory, time and username.
- [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
- [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - Solarized powerline variant.
- [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) terminals.
- [sorin-modified-dark](https://github.com/hrmeetsingh/sorin-modified-dark) - Based on [sorin](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#sorin). Minimalist, adds decorators for `git` status and current directory.
- [spaceship](https://github.com/denysdovhan/spaceship-prompt) - Theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful status decorators.
- [spectere](https://github.com/Spectere/spectere-omz-theme) - Powerline-esque. Includes decorators for current directory, root status, and `git` status.
- [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
- [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) - Includes time, `git` and current directory decorations.
- [ssfprompt](https://github.com/hugoh/zsh-ssfprompt) - Simple, slim, fast. Includes `ssh`, virtualenv and vcs decorations.
- [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
- [starboy](https://github.com/prdpx7/Starboy) - A simple ZSH theme.
- [starship (wintermi)](https://github.com/wintermi/zsh-starship) - A simple plugin to use the Starship prompt, along with a powerline theme.
- [starship](https://starship.rs/) - Minimal, fast, extremely customizable.
- [starship2k](https://github.com/2KAbhishek/starship2k) - Includes powerline support, decorators for `git` information, multiple languages and a multiline prompt.
- [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
- [steef (danihodovic)](https://github.com/danihodovic/steeef) - Oh-my-zsh steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
- [steef (zelongguo)](https://github.com/ZelongGuo/steeef) - Based on the [zimfw steef theme](https://github.com/zimfw/steeef). Includes decorators for username@hostname, python venv, `git` status and current directory. Requires [git-info](https://github.com/zimfw/git-info).
- [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) theme.
- [steeple](https://github.com/erwanjugand/steeple-zsh-theme) - Minimalist theme with `git` status decorations.
- [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) - Minimal, pastels.
- [stigmata](https://github.com/VLtim43/stigmata.zsh-theme) - Includes decorators for user@host and current directory.
- [sublime](https://github.com/pjmp/sublime) - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
- [sugar-free](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes.
- [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
- [sulfurium](https://github.com/Sulfurium/zsh-theme) - The official ZSH theme of sulfuriumOS.
- [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - Similar to [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) but includes the active Ruby version.
- [sunrise](https://github.com/tech8i/zsh_sunrise) - Includes decorators for battery status, current directory, date and time.
- [superkolo](https://github.com/Minipada/superkolo) - Add date and return status to the [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) theme.
- [susi](https://github.com/carcruz/susi-zsh-iterm) - Includes `git` status decorations and an accompanying iTerm2 color scheme.
- [svs](https://github.com/SvS30/svs-theme) - Clean and distraction free theme with `git` status and current path decorations.
- [sy](https://github.com/ttttmr/sy-zsh-theme) - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), includes `git` status decorations.
- [t2colorful](https://github.com/AmirhosseinAbutalebi/t2colorful-oh.my.zsh) - Includes decorators for `git` information, current directory, last command exit status, and current time.
- [t2er](https://github.com/t2er/t2er-zsh-theme) - Minimalist theme with `git` decorations.
- [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
- [tarcadia](https://github.com/Tarcadia/tarcadia-zsh-theme) - Based on [jonathan](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/jonathan.zsh-theme). Includes decorators for current directory and `git` status.
- [tcr](https://github.com/tulioribeiro/zsh-tcr-theme) - Minimalist theme, shows decorators for current directory, `git` status information & `nvm` version.
- [temeraf](https://github.com/filiptoma/temeraf-zsh) - Minimalist theme with decorations for `git` status, timestamps and last exit status.
- [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - Includes `git` status decorations and conda/virtualenv status.
- [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - Minimalist theme.
- [termuxer](https://github.com/patrick330602/termuxer) - Theme inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and linuxer.
- [thayne](https://github.com/tmccombs/thayne.zsh-theme) - Includes decorators for exit status of last command, time to run if > 1 second, current time, current directory and `git` status. Requires a Nerd Font.
- [the-time-lord](https://github.com/jhwhite/the-time-lord) - A theme based on [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
- [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status.
- [themer](https://github.com/MrRedacted/zsh-themer) - Includes multiple color scheme options, with `git` status decorators. There are also multiple icons to choose from within the `.zsh-theme` file. Based on [strug](https://github.com/triplepointfive/oh-my-zsh/blob/master/themes/strug.zsh-theme).
- [themeraf](https://github.com/oliver-svrcek/Themeraf) - Has decorators for username, last two directories in working directory path, `git` status, timestamp, last exit status and also name of active virtual environment.
- [theozera](https://github.com/theogandara/zsh-theme) - Includes decorators for `git` status, a truncated current directory, and the exit status of the last command run.
- [theta-async](https://github.com/jesec/zsh_theme_theta-async) - Async version of [theta](https://github.com/eendroroy/theta). Includes vcs status information.
- [theta](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
- [theto](https://github.com/heyvito/theto-zsh-theme) - Simplistic theme.  Needs [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
- [thetraveler](https://github.com/bassopenguin/thetraveler) - Inspired by theunraveler, uses symbols to display `git` status.
- [thm](https://github.com/thm-unix/thm-zshtheme) - Includes decorators for virtualenv, current directory and `git` status.
- [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - A minimal version of the [spaceship](https://github.com/denysdovhan/spaceship-prompt) theme.
- [tho](https://github.com/codingtho/tho-zsh-theme) - Includes decorators for `git` status & current directory.
- [thygod](https://github.com/Thy-GoD/thy-god-zsh-theme) - Based off [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) and [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes a `git` status decorator and changes prompt to a red cross when a command fails.
- [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - Seasoning for shells. Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme), and [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
- [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - Simple theme with `git` status decorations.
- [toledo](https://github.com/mmatongo/toledo) - Quick minimalist theme with `git` status decorations. Works with `zsh`, `bash`, `dash` and `yash`.
- [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - Includes time and `git` status decorators.
- [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds.
- [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
- [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
- [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
- [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
- [tron](https://github.com/iDoTron/tron-zsh-theme) - Includes `git` status, working directory, time, user@host and return status of last command decorations.
- [troopert](https://github.com/TrooperT/Troopert-theme/) - Includes decorators for `git` status, last return code if non-zero, full pwd and a configurable display of `$RPROMPT`.
- [tsotra](https://github.com/nylo-andry/zsh-themes) - Minimalist theme, includes decorators for `git` status, k8s context, and `rvm` status.
- [turs](https://github.com/eikendev/turs) - Fast, minimal [Purs](https://github.com/xcambar/purs)-inspired prompt.
- [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) theme, adds powerline font enhancements.
- [twilight](https://github.com/Henryws/twilight-prompt) - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
- [type0](https://github.com/MikereDD/type0_zsh-theme) - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) by yarisgutierrez. Includes `git` decorations.
- [typewritten](https://github.com/reobin/typewritten) - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
- [ubunly](https://github.com/alejandromume/ubunly-zsh-theme) - Mimics the Kali Linux console. Note - this theme also rebinds a lot of keys and sets a bunch of ZSH options that themes should leave alone.
- [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - Mimics the default Debian/Ubuntu `bash` prompt.
- [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - Mimics the default Ubuntu prompt, but with `git` decorations.
- [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
- [ultima](https://github.com/egorlem/ultima.zsh-theme) - Minimalist, includes `git` status and current directory decorators.
- [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme with decorators for `git` status, vim mode indicator and shortened path.
- [ultimator](https://github.com/Ultimator14/ultimator-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874)-like theme. Includes decorators for current directory, `user@host`, python virtualenv, background jobs, last command exit status, and `git` status information. Requires [zsh-git-prompt](https://github.com/Ultimator14/zsh-git-prompt) plugin and Nerdfonts.
- [ulyssesys](https://github.com/UlyssesZh/ulyssesys) - Has decorators for full path to current directory, exit code of last command and `git` status.
- [unicorn](https://github.com/juliuscaesar/unicorn) - Includes decorators for root status, virtualenv, nvm, rvm, current directory, the time, current directory and emoji `git` information. Inspired by [wild cherry](https://github.com/mashaal/wild-cherry).
- [unit-1](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
- [userandnode](https://github.com/timhilton/userandnode) - A clean theme with decorators for username, node version, current directory, and `git` info.
- [valuca](https://github.com/keyaedisa/Valuca) - Variant of [ducula](https://github.com/janjoswig/Ducula). Includes decorators for background job status, username, hostname, virtualenv, current directory, last command's exit code, `git` information and the current time.
- [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
- [vehemence](https://github.com/H1N1-dev/vehemence-zsh) - Includes decorators for `pwd`, `user@host`, `tty`, time, last command exit code and `git` status.
- [velvet](https://github.com/dor133/velvet-zsh-theme) - Includes decorators for `git` status, username, current directory, exit status of last command, and the time.
- [vercel](https://github.com/vercel/zsh-theme) - Minimalist theme with `git` status decorations.
- [vertepommes](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
- [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from [mgutz](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/mgutz.zsh-theme). Looks great when using with a [Solarized](https://github.com/altercation/solarized) color scheme.
- [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - Inspired by VS Code's [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
- [voidy](https://github.com/rwejdling/voidy) - Borrows elements from [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) themes and adds the active [aws-vault](https://github.com/99designs/aws-vault) profile to the right side of the prompt.
- [vszambon-ocean](https://github.com/vzambon/vszambon_ocean-zsh-theme) - Includes decorators for current directory, `git` status, a day/night icon, whether or not it is running inside a `docker` container and the date and time.
- [vtex](https://github.com/charleseduardome/oh-my-zsh-vtex) - Includes decorators for `git` status, current directory, vtex account and vtex workspace.
- [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
- [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks.
- [wang-iterm](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
- [warm-colours](https://github.com/BastionAtackDev/Warm-Colours.zsh-theme/) - Includes decorators for user@host, current directory and datetime.
- [warmblood](https://github.com/D42H5/warmblood) - Based on [darkblood](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/darkblood.zsh-theme). Includes decorators for `git` information, user@hostname and the current directory.
- [whale](https://github.com/whalesea520/whale-zsh-theme) - Fast reimplementation of the whale theme.
- [whales](https://github.com/lbergelson/zsh_whales_theme) - Includes decorators for `git` status, java version, last command return status, and directory.
- [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
- [windows](https://github.com/juliavallina/windows-zsh-theme/) - Inspired by the Windows Command Prompt. Includes a decorator for the current directory.
- [winline](https://github.com/khuei/winline) - Async version of Greg Hurrell's [prompt](https://github.com/wincent/wincent/blob/master/aspects/dotfiles/files/.zshrc). Includes decorators for `git` status, duration of last command, current directory, nested shells, root status.
- [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme) - A simple theme for Python users. Includes virtualenv and `git` status decorators.
- [work-line](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
- [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - Includes `git` status decorations, working directory, exit status of last command and current `virtualenv`.
- [wormwood](https://github.com/ann-kilzer/annkilzer.zsh-theme) - Includes decorators for last command exit status, current directory and `git` status.
- [x](https://github.com/tharindu899/x-theme) - Includes customizable banners
- [xandermute](https://github.com/SoYoureAWaffleMan/xandermute-oh-my-zsh-theme/) - Minimalist theme with `git` and current directory decorations.
- [xavi](https://github.com/onthedock/xavi.zsh-theme) - Modified version of the [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme with emoji decorations for `git` status and current directory.
- [xbira](https://github.com/ITAxReal/xbira) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), includes decorators for `git` status, user@hostname, exit status of last command run and the current directory.
- [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - Simple theme with `git` decorations.
- [xm](https://github.com/Shiaoming/xm) - Theme for dark terminals. Has `git` decorations.
- [xor](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
- [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
- [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme) - Fast, simple and streamlined theme. Works best with [tmux](https://github.com/tmux/tmux/wiki) and [vim-airline](https://github.com/vim-airline/vim-airline).
- [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current `git` commit's shortened hash and message.
- [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme.
- [yazpt](https://github.com/jakshin/yazpt) - A clean, fast, good-looking ZSH prompt theme that thoughtfully incorporates Git/Subversion/TFVC status info, integrates with popular plugin managers like Oh My Zsh, and is straightforward to customize and extend.
- [yechen](https://github.com/liyechen/yechen.zsh-theme) - Minimalist theme with `git` status decorations.
- [yeet](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
- [yellow-sea-diamonds](https://github.com/jimratliff/yellow-sea-diamonds-zsh-theme) - Includes decorations for `git` status, current directory, active python virtual environment, and the exit status of the last command run.
- [yindev](https://github.com/menyinch/yindev-zsh-theme) - Variant of `gndx`. Includes decorations for `git` status and current directory.
- [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
- [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
- [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
- [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
- [ysr](https://github.com/raykle/ysr-zsh-theme) - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme). Includes `git` status decorations.
- [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
- [yuyuko](https://github.com/hylwxqwq/yuyuko.zsh-theme) - Fork of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), inspired by [yuyuko.vim](https://github.com/hylwxqwq/yuyuko.vim).
- [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
- [yz50](https://github.com/lacanlale/yz50-zsh) - Colorful, based off of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) themes. Includes `git` status decorations.
- [z4rr3t](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) theme.
- [zap-robbyrussell](https://github.com/devadathanmb/zap-robbyrussell) - The OMZ robbyrussell theme, patched to add compatibility with [zap](https://www.zapzsh.com/).
- [zcmder](https://github.com/bwpge/zcmder) - inspired by [Cmder](https://cmder.app/) with decorators for `git` information, current directory and root status.
- [zcraft](https://github.com/cpea2506/zcraft) - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
- [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
- [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) - Zelda-inspired theme. Includes `git` status decorations.
- [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
- [zemoji](https://github.com/therzka/zemoji) - Based on [wild-cherry]( https://github.com/mashaal/wild-cherry/tree/master/zsh). Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
- [zen](https://github.com/cybardev/zen.zsh) - A minimalist theme for `*NIX` systems. Includes decorators for execution time of last command run, curreent directory and vcs status information.
- [zenith](https://github.com/waki285/Zenith) - Minimalist. Includes decorators for username, current directory and `git` status.
- [zero (arlimus)](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
- [zero (shirozuki)](https://github.com/shirozuki/zero-zsh-theme) - Minimalistic prompt with decorators for `git` status, current directory, exit status and time to execute of last command run.
- [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - Works best on dark backgrounds, includes `git` status decorations.
- [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - Works better on dark brackgrounds.
- [zest](https://github.com/hash-bang/zsh-theme-zest) - A functional theme for ZSH. Influenced by [zsh2000](https://github.com/consolemaverick/zsh2000), [agnoster](https://gist.github.com/agnoster/3712874) and [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) themes.
- [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows decorations for username, `git` status information, machine name, the current working directory and success/fail status of last command.
- [zhiyin](https://github.com/AmyangXYZ/zhiyin-zsh-theme) - Includes decorators for user @ host, current working directory and `git` status information.
- [zido](https://github.com/SidonieBouthors/zido-zsh-theme) - Includes decorators for `git` status and current directory.
- [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous prompt inspired by [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) and [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) that's easily extensible and extremely configurable. It supports async segments using [zsh-async](https://github.com/mafredri/zsh-async).
- [zish](https://github.com/RubixDev/zish/) - Based on the `fish` shell's default look.
- [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
- [zodiac](https://github.com/adamalsen/zsh-zodiac) - Includes an emoji for the animal corresponding to the current year.
- [zoo](https://github.com/salamantos/zoo_sh) - Casual theme with animal emoji. Includes decorators for current directory, time and `git` status.
- [zp](https://github.com/Karitham/zp) - Fast prompt, written in `zig`. Includes `git` status and current directory decorators.
- [zprompts](https://github.com/z-shell/zprompts) - Themes (prompts) that use original `zsh` theming subsystem.
- [zqt](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) theme.
- [zsh1999](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
- [zsh2000](https://github.com/consolemaverick/zsh2000) - Theme which resembles Powerline and includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
- [zsh313](https://github.com/amirali313/zsh313-theme) - Minimal theme with `git` status decorations.
- [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade! Includes `git` status decorations.
- [zshify](https://github.com/nrjdalal/zshify) - A minimalistic, one command installation to customize your prompt. Requires [npx](https://docs.npmjs.com/getting-started/installing-npm-packages-locally).
- [zshiggy](https://github.com/malouro/zshiggy) - Includes decorators for `git` status, `node.js` version.
- [zshpower](https://github.com/snakypy/zshpower) - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
- [zshred](https://github.com/redxtech/zshred) - Shows current directory, `git` decorations, exit status of last command and time.
- [zskai](https://github.com/dinizgab/zskai-theme) - Simple theme based on Monokai. Includes decorators for user@hostname, time, `git` status and current working directory.
- [zunder](https://github.com/Warbacon/zunder-prompt) - Simple and fast ZSH prompt based on [gitstatus](https://github.com/romkatv/gitstatus).
- [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
- [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), designed to disclose information contextually, with a powerline aesthetic.
- [zzshell](https://github.com/thezzisu/zzshell) - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

- [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
- [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
- [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - Another Powerline-compatible font.
- [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
- [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
- [Iosevka](https://github.com/be5invis/Iosevka) - Coders' typeface, built from code. Highly customizable.
- [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
- [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
- [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
- [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

I recommend [zgenom](https://github.com/jandamm/zgenom) if you don't already have a preferred ZSH framework. It adds minimal overhead during shell session startup because it generates a load script only when you change your plugin list, and that load script is sourced during startup instead of being recalculated every time.

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

Zgen is not being actively maintained. I recommend that you switch to the [Zgenom](https://github.com/jandamm/zgenom) fork, which is.

### [Zgenom](https://github.com/jandamm/zgenom)

Most of these plugins can be installed by adding `zgenom load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgenom load` calls in.

Zgenom will automatically clone the plugin repositories for you when you do a `zgenom save`.

### [zplug](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

### [zpm](https://github.com/zpm-zsh/zpm)

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins and Themes

I've documented some recommendations for writing new plugin and themes [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins_and_Themes.md).

There is also a more detailed [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

- [argcomplete](https://github.com/kislyuk/argcomplete) - Generates tab completions for programs using Python's `argparse` module.
- [crazy-complete](https://github.com/crazy-complete/crazy-complete) - Every program should have autocompletion in the shell to enhance user experience and productivity. crazy-complete helps solve this task by generating robust and reliable autocompletion scripts.
- [manpage-completion-generator](https://github.com/umlx5h/zsh-manpage-completion-generator) - Generats ZSH completions from man pages. Requires [create_manpage_completions.py](https://github.com/fish-shell/fish-shell/blob/master/share/tools/create_manpage_completions.py) which is installed by the fish shell
- [oh-plugin](https://github.com/mbergo/oh-plugin) - Helps you install plugins for [oh-my-zsh](https://ohmyz.sh) by typing `oh-plugin install repository_address`.
- [shell-color-prompt-tool](https://github.com/kyletimmermans/shell-color-prompt-tool) - Helps you create a custom prompt for `ZSH` or `bash`.
- [shellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
- [shtab](https://github.com/iterative/shtab) - Automatically generate shell tab completion scripts for Python CLI apps, supports `zsh`, `bash` and `tcsh`.
- [zsh-ai-completions](https://github.com/iloveitaly/zsh-ai-completions) - AI-generated ZSH completions
- [zsh-bench](https://github.com/romkatv/zsh-bench) - A benchmark for interactive ZSH. It measures user-visible latency of interactive `zsh`: input lag, command lag, etc.
- [zshdb](https://github.com/rocky/zshdb) - A ZSH debugger.
- [zshelldoc](https://github.com/zdharma-continuum/zshelldoc) - Doxygen for shell scripts. Parses ZSH and Bash scripts, outputs Asciidoc document with function lists, call trees, lists of exported variables, and more.
- [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH.

### Other Useful Lists

- [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment.
- [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources.
- [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

- The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.

- [Mastering ZSH](https://github.com/rothgar/mastering-zsh) is a great tutorial that builds on the basics to show you advanced ZSH usage, customizations, and practical examples.

## Thanks

Many thanks to all the contributors over the years. The list wouldn't be nearly as complete without all your help.

<a href="https://github.com/unixorn/awesome-zsh-plugins/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=unixorn/awesome-zsh-plugins" />
</a>

Made with [contributors-img](https://contributors-img.web.app).
