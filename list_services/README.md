# List of package services
Here is a list of official pacman package services.

## Service [termux-pacman.us](https://s3.amazonaws.com/termux-pacman.us/index.html)

repo name | link | architecture support
--- | --- | ---
main | https://s3.amazonaws.com/termux-pacman.us/main | all
x11 | https://s3.amazonaws.com/termux-pacman.us/x11 | all
root | https://s3.amazonaws.com/termux-pacman.us/root | all

**Connection code**  
```
[main]
Server = https://s3.amazonaws.com/termux-pacman.us/main/$arch

[x11]
Server = https://s3.amazonaws.com/termux-pacman.us/x11/$arch

[root]
Server = https://s3.amazonaws.com/termux-pacman.us/root/$arch
```
**Infonormation:**  
- android version support: 7+
- storage: AWS bucket S3
- region: US
- supports: [@termux-pacman](https://github.com/termux-pacman)
