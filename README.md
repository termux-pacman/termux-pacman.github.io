[Termux-Pacman](https://github.com/termux-pacman) is an organization dedicated to maintaining Termux packages in the pacman format, developing their own packages, and developing publicly available tools for working with pacman.

## Basic Repos:
### main - basic packages
```bash
[main]
Server = https://service.termux-pacman.dev/main/$arch
```

### x11 - graphics packages
```bash
[x11]
Server = https://service.termux-pacman.dev/x11/$arch
```

### root - packages that need root
```bash
[root]
Server = https://service.termux-pacman.dev/root/$arch
```

### tur - termux user repository
```bash
[tur]
Server = https://service.termux-pacman.dev/tur/$arch
```

### gpkg - glibc packages for Termux
```bash
[gpkg]
Server = https://service.termux-pacman.dev/gpkg/$arch
```
