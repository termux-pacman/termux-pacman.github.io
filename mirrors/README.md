---
layout: page
title: Mirrors
permalink: /mirrors/
---

This is a list of official mirrors for the pacman package manager in Termux.

### Service by [Termux-Pacman](https://github.com/termux-pacman)
- Link: [service.termux-pacman.dev](https://service.termux-pacman.dev)
- Rsync address: [sync.termux-pacman.dev/termux-pacman](rsync://sync.termux-pacman.dev/termux-pacman/)
- Location: United States 🇺🇸
- IPv4/IPv6 support: both
- Pacman configuration code for connection:
  ```sh
  Server = https://service.termux-pacman.dev/$repo/$arch  
  ```

### Mirror by [MeowIce](https://github.com/MeowIce)
- Link: [mirror.meowsmp.net/termux-pacman](https://mirror.meowsmp.net/termux-pacman)
- Rsync address: [rsync.meowsmp.net/termux-pacman](rsync://rsync.meowsmp.net/termux-pacman/)
- Location: Vietnam 🇻🇳
- IPv4/IPv6 support: both
- Pacman configuration code for connection:
  ```sh
  Server = https://mirror.meowsmp.net/termux-pacman/$repo/$arch
  ```

### Mirror by [AG DSN](https://github.com/agdsn)
- Link: [ftp.agdsn.de/termux-pacman](https://ftp.agdsn.de/termux-pacman)
- Rsync address: [ftp.agdsn.de/termux-pacman](rsync://ftp.agdsn.de/termux-pacman/)
- Location: Germany 🇩🇪
- IPv4/IPv6 support: both
- Pacman configuration code for connection:
  ```sh
  Server = https://ftp.agdsn.de/termux-pacman/$repo/$arch
  ```
