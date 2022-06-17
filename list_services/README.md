# List of package services
Here is a list of official pacman package services.

## Service s3.amazonaws.com/termux-*.pacman

repo name | link | architecture support
--- | --- | ---
main | https://s3.amazonaws.com/termux-main.pacman | all
x11 | https://s3.amazonaws.com/termux-x11.pacman | all
root | https://s3.amazonaws.com/termux-root.pacman | all

**Connection code**  
```
[main]
Server = https://s3.amazonaws.com/termux-main.pacman/$arch

[x11]
Server = https://s3.amazonaws.com/termux-x11.pacman/$arch

[root]
Server = https://s3.amazonaws.com/termux-root.pacman/$arch
```
**Infonormation:**  
- [package repository](https://github.com/termux-pacman/termux-packages)
- android version support: 7+
- storage: AWS bucket S3
- the db update happens on: GitHub actions
- supports: [@termux-pacman](https://github.com/termux-pacman)
- by: [@Maxython](https://github.com/Maxython)
