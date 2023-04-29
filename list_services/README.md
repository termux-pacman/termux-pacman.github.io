# List of package services
Here is a list of official pacman package services.

<!--## Service [service.termux-pacman.dev](https://service.termux-pacman.dev/)-->
## Service s3.amazonaws.com/termux-pacman.us

<!--
repo name | link | architecture support
--- | --- | ---
main | https://service.termux-pacman.dev/main | all
x11 | https://service.termux-pacman.dev/x11 | all
root | https://service.termux-pacman.dev/root | all
tur | https://service.termux-pacman.dev/tur | all
tur-continuous | https://service.termux-pacman.dev/tur-continuous | all
tur-multilib | https://service.termux-pacman.dev/tur-multilib | all
-->

repo name | link | architecture support
--- | --- | ---
main | https://s3.amazonaws.com/termux-pacman.us/main | all
x11 | https://s3.amazonaws.com/termux-pacman.us/x11 | all
root | https://s3.amazonaws.com/termux-pacman.us/root | all
tur | https://s3.amazonaws.com/termux-pacman.us/tur | all
tur-continuous | https://s3.amazonaws.com/termux-pacman.us/tur-continuous | all
tur-multilib | https://s3.amazonaws.com/termux-pacman.us/tur-multilib | all
gpkg-dev | https://s3.amazonaws.com/termux-pacman.us/gpkg-dev | all

**Connection code**
```bash
[main]
Server = https://s3.amazonaws.com/termux-pacman.us/main/$arch

[x11]
Server = https://s3.amazonaws.com/termux-pacman.us/x11/$arch

[root]
Server = https://s3.amazonaws.com/termux-pacman.us/root/$arch

[tur]
Server = https://s3.amazonaws.com/termux-pacman.us/tur/$arch

[tur-continuous]
Server = https://s3.amazonaws.com/termux-pacman.us/tur-continuous/$arch

[tur-multilib]
Server = https://s3.amazonaws.com/termux-pacman.us/tur-multilib/$arch

[gpkg-dev]
Server = https://s3.amazonaws.com/termux-pacman.us/gpkg-dev/$arch
```

**Infonormation:**
- android version support: 7+
- storage: AWS bucket S3
- region: US
- supports: [@termux-pacman](https://github.com/termux-pacman)
