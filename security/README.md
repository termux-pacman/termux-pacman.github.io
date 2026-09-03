---
layout: page
title: Security Policy
permalink: /security/
---

## Supported Versions

The Termux-Pacman organization provides and maintains infrastructure, packages, and projects for [Termux](https://termux.dev/en/) and other similar Linux systems. For verification purposes, Termux-Pacman signs and publicly presents all signatures in its infrastructure.  
<br>
**NOTE:** not all packages are signed in the `main`, `x11` and `root` repositories.

## Limitations

The Termux-Pacman organization deals with vulnerability issues in the following cases:
 - If a vulnerability has been found in the Termux-Pacman infrastructure.
 - If a vulnerability has been found in utilities/tools/packages that are entirely developed and maintained by Termux-Pacman.
 - If a package from the **mirrored Git repositories** has not been updated to fix the vulnerability.

The Termux-Pacman organization cannot be fully responsible for fixing the vulnerability of packages located in mirrored Git repositories, since the second organizations that own the root Git repositories are responsible for fully maintaining packages from mirrored Git repositories.  
<br>
As of today, the Termux-Pacman organization has the following mirrored Git repositories:
 - [github.com/termux-pacman/termux-packages](https://github.com/termux-pacman/termux-packages)  
   This Git repository provides packages for the `main`, `x11` and `root` repositories.  
   The root Git repository - [github.com/termux/termux-packages](https://github.com/termux/termux-packages).
 - [github.com/termux-pacman/tur](https://github.com/termux-pacman/tur)  
   This Git repository provides packages for the `tur`, `tur-continuous` and `tur-multilib` repositories.  
   The root Git repository - [github.com/termux-user-repository/tur](https://github.com/termux-user-repository/tur).

## Reporting a Vulnerability

To report a vulnerability, you must send an email to [pacman@termux.dev](mailto:pacman@termux.dev) with the following information:
 - Subject must begin with the text `[Reporting Vulnerability]`.
 - Provide proof or detailed information about the vulnerability.

Without this, the email may not be seen immediately or be ignored. Once submitted, your email will be reviewed to confirm the vulnerability. If a vulnerability has been confirmed, then steps will be taken to fix the vulnerability.
