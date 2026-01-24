---
layout: wiki
---
* TOC
{:toc}

[![GitHub](https://img.shields.io/badge/GitHub-joknarf%2Ftty--keepalive-black?logo=github)](https://github.com/joknarf/tty-keepalive)
[![Shell](https://img.shields.io/badge/shell-bash%20-blue.svg)]()
[![Licence](https://img.shields.io/badge/licence-MIT-blue.svg)](https://shields.io/)


# tty-keepalive

Simulate tty activity in background to prevent stale/disconnected interactive session ($TMOUT / firewall timeout)

## features

* background process to keepalive an interactive shell session (ssh connection)
* send OSC Virtual Bell code to tty at defined interval (silently ignored by terminal emulators)
* exits when tty dies

## usage

```
tty-keepalive [<SECONDS>]
```
in rc file:
```
tty-keepalive [<SECONDS>]
```

default `<SECONDS>`: 120
