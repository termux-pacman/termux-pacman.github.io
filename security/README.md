---
layout: page
title: Security Policy
permalink: /security/
---

## Supported Versions

The Termux-Pacman organization provides packages that work in [Termux](https://termux.dev/en/), as well as signatures for packages that are built with the latest version of `gpg`.  
**NOTE:** not all packages are signed in the `main`, `x11` and `root` repositories.

## Limitations

The Termux-Pacman organization deals with vulnerability issues in the following cases:
 - If a vulnerability has been found in our services or mirrors. 
 - If a vulnerability has been found in package signatures.
 - If a vulnerability has been found in our own package.
 - If a package has not been updated in which the vulnerability of the package is fixed.

The Termux-Pacman organization does not deal with issues of fixing the vulnerability in packages that are in the **git repo mirror**. At the moment it is the following repos:
 - main
 - x11
 - root
 - tur
 - tur-continuous
 - tur-multilib

**NOTE:** if a vulnerability is reported about a package that is in the *git repo mirror*, then that information will be passed on to the team that manages that repo and also to the author (or organization) of the package.

## Reporting a Vulnerability

To report a vulnerability, you must send an email to [pacman@termux.dev](mailto:pacman@termux.dev) with the following information:
 - Subject must begin with the text `[Reporting Vulnerability]`.
 - Provide proof or detailed information about the vulnerability.

Without this, the email may not be seen immediately or be ignored. Once submitted, your email will be reviewed to confirm the vulnerability. If a vulnerability has been confirmed, then steps will be taken to fix the vulnerability.
