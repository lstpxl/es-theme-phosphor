# Green Phosphor CRT Theme

![Screenshot](_inc/screenshots/systems.png)

`es-theme-phosphor`

Specially tuned for a 640×480 screen and the **Anbernic RG353V** running [dArkOS](https://github.com/christianhaitian/dArkOS).

## Deploy, Update, and Copy

Upload the theme using `rsync`

```bash
rsync -av --exclude='.git' \
    ~/Projects/themes/es-theme-phosphor/ \
    ark@192.168.100.86:/roms/themes/es-theme-phosphor/
```

or using `scp`

```bash
scp -r ~/Projects/themes/es-theme-phosphor ark@192.168.100.86:/roms/themes
```

or update the main file after edit

```bash
scp -r ~/Projects/themes/es-theme-phosphor/theme.xml \
    ark@192.168.100.86:/roms/themes/es-theme-phosphor
```

## Fonts Used

- Flexi_IBM_VGA_True.ttf
- SF Pixelate.ttf

## Syntax Docs

[Batocera EmulationStation Themes Documentation](https://github.com/batocera-linux/batocera-emulationstation/blob/master/THEMES.md)
