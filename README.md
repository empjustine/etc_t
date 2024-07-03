## locale

Configure machine to use pt_BR.UTF-8 locale.

```sh
#!/bin/sh
localectl set-locale LANG=pt_BR.UTF-8
localectl set-keymap br
localectl set-x11-keymap br pc105 abnt2

timedatectl set-local-rtc 0
timedatectl set-timezone 'America/Sao_Paulo'
timedatectl set-ntp 1
```
