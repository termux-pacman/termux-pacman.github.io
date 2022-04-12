# termux-pacman
Welcome to the official website of the termux-pacman organization. This organization maintains the pacman package manager and its services for termux.  

## Main Links:
- [groups](/groups)


## List of services:
### [main](https://s3.amazonaws.com/termux-main.pacman/index.html)
```bash
[main]
Server = https://s3.amazonaws.com/termux-main.pacman/$arch
```
Basic packages - [_repo_](https://github.com/termux-pacman/termux-packages)

### [x11](https://s3.amazonaws.com/termux-x11.pacman/index.html)
```bash
[x11]
Server = https://s3.amazonaws.com/termux-x11.pacman/$arch
```
Graphics packages - [_repo_](https://github.com/termux-desktop/x11-packages)
  
### [root](https://s3.amazonaws.com/termux-root.pacman/index.html)
```bash
[root]
Server = https://s3.amazonaws.com/termux-root.pacman/$arch
```
Packages that need root - [_repo_](https://github.com/termux-pacman/termux-root-packages)
