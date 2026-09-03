---
layout: page
title: Mirrors
permalink: /mirrors/
---

The Termux-Pacman organization presents two primary mirrors and has officially recognized three mirrors.  
<br>
To configure mirrors in the pacman package manager, manually edit the [mirrorlist](https://github.com/termux/termux-packages/blob/master/packages/pacman/mirrorlist) file located at `${PREFIX}/etc/pacman.d/mirrorlist`. Note that pacman processes this list sequentially from top to bottom, selecting the first mirror that responds without an error.

## Primary mirrors

### [service.termux-pacman.dev](https://service.termux-pacman.dev)
- Owner: [Termux-Pacman](https://github.com/termux-pacman)
- Location: United States 🇺🇸
- Powered by [AWS](https://aws.amazon.com/what-is-cloud-computing)
- Supported protocols: `http` and `https`.
  ```sh
  Server = https://service.termux-pacman.dev/$repo/$arch
  ```

### [sync.termux-pacman.dev](https://sync.termux-pacman.dev)
- Owner: [Termux-Pacman](https://github.com/termux-pacman)
- Location: United States 🇺🇸
- Powered by [OVHcloud](https://us.ovhcloud.com/)
- Supported protocols: `http`, `https` and `rsync`.
  ```sh
  Server = https://sync.termux-pacman.dev/$repo/$arch
  ```

## Mirrors in Germany 🇩🇪

### [ftp.agdsn.de/termux-pacman](https://ftp.agdsn.de/termux-pacman)
- Owner: [AG DSN](https://github.com/agdsn)
- Supported protocols: `http`, `https` and `rsync`.
  ```sh
  Server = https://ftp.agdsn.de/termux-pacman/$repo/$arch
  ```

## Mirrors in United States 🇺🇸

### [mirror.clarkson.edu/termux-pacman](https://mirror.clarkson.edu/termux-pacman)
- Owner: [Clarkson Open Source Institute](https://github.com/COSI-Lab)
- Supported protocols: `http`, `https` and `rsync`.
  ```sh
  Server = https://mirror.clarkson.edu/termux-pacman/$repo/$arch
  ```

## Mirrors in Vietnam 🇻🇳

### [mirror.meowsmp.net/termux-pacman](https://mirror.meowsmp.net/termux-pacman)
- Owner: [MeowIce](https://github.com/MeowIce)
- Supported protocols: `http`, `https` and `rsync`.
  ```sh
  Server = https://mirror.meowsmp.net/termux-pacman/$repo/$arch
  ```
