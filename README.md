[Termux-Pacman](https://github.com/termux-pacman) is an organization dedicated to maintaining Termux packages in the pacman format, developing their own packages, and developing publicly available tools for working with pacman.

## Basic Repos
- **main** - basic packages.
  ```sh
  [main]
  Server = https://service.termux-pacman.dev/main/$arch
  ```
- **x11** - graphics packages.
  ```sh
  [x11]
  Server = https://service.termux-pacman.dev/x11/$arch
  ```
- **root** - packages that need root.
  ```sh
  [root]
  Server = https://service.termux-pacman.dev/root/$arch
  ```
- **tur** - termux user repository.
  ```sh
  [tur]
  Server = https://service.termux-pacman.dev/tur/$arch
  ```
- **gpkg** - glibc packages for Termux.
  ```sh
  [gpkg]
  Server = https://service.termux-pacman.dev/gpkg/$arch
  ```
