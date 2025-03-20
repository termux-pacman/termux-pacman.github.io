---
layout: page
title: Services and mirrors
permalink: /services/
---

This is a list of services and official mirrors for the pacman package manager in Termux.

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
