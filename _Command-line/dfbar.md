---
layout: wiki
---
* TOC
{:toc}

[![GitHub](https://img.shields.io/badge/GitHub-joknarf%2Flsicon-black?logo=github)](https://github.com/joknarf/lsicon)
[![bash](https://img.shields.io/badge/shell-bash%20|%20zsh%20|%20ksh%20-blue.svg)]()
[![bash](https://img.shields.io/badge/OS-Linux%20|%20macOS%20|%20SunOS%20...-blue.svg)]()
[![Licence](https://img.shields.io/badge/licence-MIT-blue.svg)](https://shields.io/)

# dfbar

Simple df command enhancer in less than 4K (only uses bash/df/awk)

![image](https://github.com/user-attachments/assets/853140c7-4044-4ba3-8d44-4e1f7d396796)

## Prerequisites

* GNU df
  * on BSD/MacOS coreutils package needed
* awk
* bash
* Nerd Font in your Terminal

## Install

You can use a plugin manager, like the famous [thefly](https://github.com/joknarf/thefly)
```
. <(curl https://raw.githubusercontent.com/joknarf/thefly/main/thefly) install
fly add joknarf/dfbar
```
or just clone the repo, and put `dfb` file in dir in your PATH
```
git clone https://github.com/joknarf/dfbar
```

## Usage

The dfbar command `dfb` is used with exactly same options as GNU `df`
```
dfb
dfb -h
...
```
You may want to replace the `df` command with `dfb` using:
```
alias df='dfb'
```

