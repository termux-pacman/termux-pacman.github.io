---
layout: page
title: Repository mirroring
permalink: /mirroring/
---

If you are interested in creating a mirror of the Termux-Pacman repositories, you can do so using the `rsync` tool via the `sync.termux-pacman.dev` domain:
```bash
# example of mirroring Termux-Pacman repositories
rsync -a --delete rsync://sync.termux-pacman.dev/termux-pacman termux-pacman
```

## Mirroring requirement
It is imperative to mirror database signatures (these are `*.db.sig`, ​​`*.files.sig` and `*.json.sig`) and package signatures if they are present in the repositories.

## Contact
To avoid errors in mirroring and to receive news about the Termux-Pacman repositories, we strongly recommend sending your contact email to us at [pacman@termux.dev](mailto:pacman@termux.dev). You can also notify us about important events in your mirror for better action planning.
