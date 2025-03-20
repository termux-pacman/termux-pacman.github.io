[Termux-Pacman](https://github.com/termux-pacman) is an organization dedicated to maintaining Termux packages in the pacman format, developing their own packages, and developing publicly available tools for working with pacman.

### Basic Repos
- **main** - basic packages.
  ```conf
  [main]
  Server = https://service.termux-pacman.dev/main/$arch
  ```
- **x11** - graphics packages.
  ```conf
  [x11]
  Server = https://service.termux-pacman.dev/x11/$arch
  ```
- **root** - packages that need root.
  ```conf
  [root]
  Server = https://service.termux-pacman.dev/root/$arch
  ```
- **tur** - termux user repository.
  ```conf
  [tur]
  Server = https://service.termux-pacman.dev/tur/$arch
  ```
- **gpkg** - glibc packages for Termux.
  ```conf
  [gpkg]
  Server = https://service.termux-pacman.dev/gpkg/$arch
  ```
