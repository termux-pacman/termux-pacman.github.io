# List of package services
Here is a list of official pacman package services.

## Service [service.termux-pacman.dev](https://service.termux-pacman.dev/)

repo name | link | architecture support
--- | --- | ---
main | https://service.termux-pacman.dev/main | all
x11 | https://service.termux-pacman.dev/x11 | all
root | https://service.termux-pacman.dev/root | all
tur | https://service.termux-pacman.dev/tur | all
tur-continuous | https://service.termux-pacman.dev/tur-continuous | all
tur-multilib | https://service.termux-pacman.dev/tur-multilib | all

**Connection code**  
```
[main]
Server = https://service.termux-pacman.dev/main/$arch

[x11]
Server = https://service.termux-pacman.dev/x11/$arch

[root]
Server = https://service.termux-pacman.dev/root/$arch

[tur]
Server = https://service.termux-pacman.dev/tur/$arch

[tur-continuous]
Server = https://service.termux-pacman.dev/tur-continuous/$arch

[tur-multilib]
Server = https://service.termux-pacman.dev/tur-multilib/$arch
```
**Infonormation:**  
- android version support: 7+
- storage: AWS bucket S3
- region: US
- supports: [@termux-pacman](https://github.com/termux-pacman)
