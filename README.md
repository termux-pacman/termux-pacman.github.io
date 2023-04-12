# Main page
Welcome to the official website of the **Termux Pacman** organization. **Termux Pacman** is an organization dedicated to maintaining Termux packages in the pacman format, developing their own packages, and developing publicly available tools for working with pacman.

## Basic Repos:
### main
<!--```bash
[main]
Server = https://service.termux-pacman.dev/main/$arch
```-->
```bash
[main]
Server = https://s3.amazonaws.com/termux-pacman.us/main/$arch
```
Basic packages.

### x11
<!--```bash
[x11]
Server = https://service.termux-pacman.dev/x11/$arch
```-->
```bash
[x11]
Server = https://s3.amazonaws.com/termux-pacman.us/x11/$arch
```
Graphics packages.

### root
<!--```bash
[root]
Server = https://service.termux-pacman.dev/root/$arch
```-->
```bash
[root]
Server = https://s3.amazonaws.com/termux-pacman.us/root/$arch
```
Packages that need root.

### tur
<!--```bash
[tur]
Server = https://service.termux-pacman.dev/tur/$arch
```-->
```bash
[tur]
Server = https://s3.amazonaws.com/termux-pacman.us/tur/$arch
```
Termux user repository.

## Main Links:
- [Services](/list_services)
- [Groups](/list_groups)
- [Donate](/donate)
