Termux-Pacman is an informal organization dedicated to various projects primarily aimed at Termux.

## Main projects
- ### Pacman packages
  Termux-Pacman presents Termux packages in pacman format (i.e., for the pacman package manager). To achieve this, Termux-Pacman independently and autonomously builds packages from mirrored Git repositories synced with the root repositories. Termux-Pacman developers also configure and maintain packages and builders in the root repositories to ensure that packages can be built seamlessly by Termux-Pacman.<br>
  **Repositories:**
  - [github.com/termux-pacman/termux-packages](https://github.com/termux-pacman/termux-packages)
  - [github.com/termux-pacman/tur](https://github.com/termux-pacman/tur)
- ### Glibc packages
  This project allows you to build glibc packages (programs, binaries, libraries, etc.) that will run in the native Android kernel shell, without the need for virtualization. Termux-Pacman builds these packages and presents them.<br>
  **Repositories:**
  - [github.com/termux-pacman/glibc-packages](https://github.com/termux-pacman/glibc-packages)
  - [github.com/termux/glibc-packages](https://github.com/termux/glibc-packages) (don't worry, apt user. Termux also builds and presents them)

## How to get started
You have two options to install pacman in Termux:
 1. Change bootstrap (recommended).<br>
 If you want to fully utilize pacman, you'll need to change your bootstartp. Please note that changing your bootstartp will erase your settings and installed packages in the bootstrap, meaning you'll have to reconfigure your system and shell (**NOTE:** data in your home directory won't be affected by changing the bootstrap). Here's a link to instructions on how to do this - [wiki.termux.com/wiki/Switching_package_manager](https://wiki.termux.com/wiki/Switching_package_manager).
 2. Install pacman via apt.<br>
 If you just need pacman or its tools, but don't need full functionality (like installing packages), you can simply install pacman via apt:
 ```
 apt install pacman
 ```
 Please note that in this format you will receive a pacman with limited functionality.
