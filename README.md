# Victory Icon Theme

Victory Icon Theme: A Gtk Icon Theme for Linux. Currently in testing, it's fairly complete but there may be icons missing every now and then. Created primarly for XFCE, but should work okay on Gnome, LXQT/LXDE, Budgie, Mint, etc. If anyone finds missing icons on any of the latter Desktop Environments, please let me know.

## Install

To install the icon pack, you can simply clone it:

In the terminal you can:

```bash
$ cd ~/.icons/
$ git clone https://github.com/newhoa/victory-icon-theme.git
```

or

``sudo git clone https://github.com/newhoa/victory-icon-theme.git /usr/share/icons``

or

```bash
$ git clone https://github.com/newhoa/victory-icon-theme.git
$ sudo cp -r victory-icon-theme /usr/share/icons
```

the first series of commands  will:

- clone the repo as your user,
-  and put it in your `~/.icons` folder so that you user can use it, 

while the second and third example will:

- copy it to the `/usr/share/icons` directory allowing all users on the machine to use it. 

After cloning, open the appearance manager for your DE/WM to select the theme:

- Budgie:
- Cinnamon: `Preferences -> Themes -> Other settings -> Icons`
- LXDE/LXQT: `lxappearance`
- Gnome 3: `gnome-tweak-tool`
- Mate: `mate-appearance-properties -> Customize -> Icons`
- Unity: `unity-tweak-tool`
- XFCE: `xfce4-appearance-settings`


## Preview

![Mime Icons](https://i.imgur.com/U1jPRDp.png "Mime Icons")

![Compact List Icons](https://i.imgur.com/QvU5LAv.png "Compact/Detailed List Icons")

![Settings Icons](https://i.imgur.com/7iBiQeg.png "Settings Icons")

![Whisker Menu Icons](https://i.imgur.com/k7LjPX5.png "Whisker Menu Icons")

