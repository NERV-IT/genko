# Genko

Pacman repository of NERV Linux

# How to use It?

Copy `nerv-mirrorlist` to `/etc/pacman.d/nerv-mirrorlist` and then add the lines below to
`/etc/pacman.conf` or anywhere you stuff with

```
[extension]
SigLevel = Optional TrustedOnly
Include = /etc/pacman.d/nerv-mirrorlist

[public]
SigLevel = Optional TrustedOnly
Include = /etc/pacman.d/nerv-mirrorlist
```
