# Tanju

Fil Necati Linux projesinin amatör dağıtım deposu.


# Pacman üzerinde nasıl kullanırım?

`fnl-mirrorlist` dosyasını `/etc/pacman.d/fnl-mirrorlist` konumuna yerleştirdikten sonra
`pacman.conf` dosyasına aşağıdaki satırları eklemeniz yeterli olacaktır.

```
[canan]
SigLevel = Optional TrustedOnly
Include = /etc/pacman.d/fnl-mirrorlist

[remzi]
SigLevel = Optional TrustedOnly
Include = /etc/pacman.d/fnl-mirrorlist
```
