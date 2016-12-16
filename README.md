# Victory Icon Theme

Victory Icon Theme: An Icon Theme for Linux. Currently in testing, it's fairly complete but there may be icons missing every now and then. Created primarly for XFCE, but should work okay on Gnome, LXQT/LXDE, Solus, Mint, etc. If anyone finds missing icons on any of the latter Desktop Environments, please let me know. Installation instructions below the theme preview.

[Preview](#preview) | [Installation](#install) | [Uninstallation](#uninstall)


<a name="preview"></a>

## Preview

![Mime Icons](https://i.imgur.com/27199oT.png "Mime Icons")

![Compact List Icons](https://i.imgur.com/QvU5LAv.png "Compact/Detailed List Icons")

![Settings Icons](https://i.imgur.com/7iBiQeg.png "Settings Icons")

![Whisker Menu Icons](https://i.imgur.com/k7LjPX5.png "Whisker Menu Icons")


<a name="install"></a>

## Install

To install the icon pack you can [download the theme as an archive](https://github.com/newhoa/victory-icon-theme/archive/master.zip) and extract it to your `/home/yourusername/.icons/` folder.

Or you can simply clone it in the terminal using either of these commands:

Command 1

```bash
$ git clone https://github.com/newhoa/victory-icon-theme.git ~/.icons/victory-icon-theme/
```

Command 2

```bash
$ sudo git clone https://github.com/newhoa/victory-icon-theme.git /usr/share/icons/victory-icon-theme/
```

Command 1 will:

- clone the repo as your user,
-  and put it in your `~/.icons` folder so that your user can use it, 

Command 2 will:

- copy it to the `/usr/share/icons` directory allowing all users on the machine to use it. 

Once the icon theme is placed in the correct folder, open the appearance manager for your Desktop Environment to select the theme:

- Solus/Budgie: `Side Panel -> Settings Icon (top right) -> General Tab -> Icon Theme`
- Mint/Cinnamon: `Preferences -> Themes -> Other settings -> Icons`
- LXDE/LXQT: `lxappearance`
- Gnome 3: `gnome-tweak-tool`
- Mate: `mate-appearance-properties -> Customize -> Icons`
- Unity: `unity-tweak-tool`
- XFCE: `xfce4-appearance-settings`


<a name="uninstall"></a>

## Uninstall

To uninstall, simply delete the victory-icon-theme folder located in ~/.icons or /usr/share/icons. Or use either of these commands:

Command 1

```bash
$ rm -r ~/.icons/victory-icon-theme/
```

Command 2

```bash
$ sudo rm -r /usr/share/icons/victory-icon-theme/
```

Command 1 will remove the folder from your local user's icon directory. Command 2 will remove the folder, as root, from /usr/share/icons, removing it for all users.

