# The concept of monorepo in termux-pacman
More recently, [@thunder-coding](https://github.com/thunder-coding) suggested making the monorepo concept in termux-packages (https://github.com/termux/termux-packages/issues/9915). Development has already begun and if all goes well, packages from x11-packages and from termux-root-packages will be moved to termux-packages. This means that these repositories will no longer be active and will be archived.  

Due to this decision, the following action will be taken in termux-pacman:  
- The x11-packages and termux-root-packages repositories will have package auto-update completely disabled.  They will also be archived.
- The termux-packages repository will temporarily disable auto-updating of packages in order to adjust the structure of package compilation and hosting.

*by: @Maxython*  
*2022-04-18*  
