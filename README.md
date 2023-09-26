**Termux Pacman** is an organization dedicated to maintaining Termux packages in the pacman format, developing their own packages, and developing publicly available tools for working with pacman.

## Basic Repos:
### main
```bash
[main]
Server = https://service.termux-pacman.dev/main/$arch
```
Basic packages.

### x11
```bash
[x11]
Server = https://service.termux-pacman.dev/x11/$arch
```
Graphics packages.

### root
```bash
[root]
Server = https://service.termux-pacman.dev/root/$arch
```
Packages that need root.

### tur
```bash
[tur]
Server = https://service.termux-pacman.dev/tur/$arch
```
Termux user repository.

### gpkg
```bash
[gpkg]
Server = https://service.termux-pacman.dev/gpkg/$arch
```
Glibc packages for Termux.
