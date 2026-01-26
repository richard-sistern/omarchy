# Omarchy

## Tweaks

- [Screensaver cmd](https://github.com/basecamp/omarchy/blob/master/bin/omarchy-cmd-screensaver)
- [Set the locale](https://wiki.archlinux.org/title/Locale#Setting_the_system_locale)

```shell
tte -i ~/.config/omarchy/branding/screensaver.txt \
  --frame-rate 120 --canvas-width 0 --canvas-height 0 --reuse-canvas --anchor-canvas c --anchor-text c\
  --random-effect --include-effects burn expand highlight matrix pour rain smoke spotlights thunderstorm waves \
  --no-eol --no-restore-cursor &
```
  

## Software

### Terraform

Install in nvim with [:LazyExtras](https://www.lazyvim.org/extras/lang/terraform)

## Troubleshooting

### Networking

- Restart WiFi with `sudo systemctl restart iwd`

## References

- [Omarchy tweaks](https://lobotuerto.com/blog/omarchy-tweaks)
- [Keyboard cheatsheet](https://acrogenesis.com/omarchy-cheat-sheet/)
