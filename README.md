# Victory Icon Theme

Victory Icon Theme: An Icon Theme for Linux. While this icon theme is slowly becoming a fairly complete icon theme, there are sure to be some icons missing here and there. Created primarly for XFCE though it should work okay on Gnome, LXQT/LXDE, Solus, Mint, etc. If anyone finds missing icons on any of the latter Desktop Environments, please let me know. Installation instructions are below the theme preview.

[Preview](#preview) | [Installation](#install) | [Uninstallation](#uninstall) | [Contribute, Donate, Paypal, Liberapay & Patreon](#contributedonate)


<a name="preview"></a>

## Preview

![Mime Icons](https://i.imgur.com/nx1Mx3q.png "Mime Icons")

![Compact List Icons](https://i.imgur.com/QvU5LAv.png "Compact/Detailed List Icons")

![Settings Icons](https://i.imgur.com/7iBiQeg.png "Settings Icons")

![Whisker Menu Icons](https://i.imgur.com/k7LjPX5.png "Whisker Menu Icons")


<a name="install"></a>

## Install

**Method 1**

[Download the theme as an archive](https://github.com/newhoa/victory-icon-theme/archive/master.zip) and extract it to your `/home/yourusername/.icons/` folder.

**Method 2**

Using the terminal, you can clone the repository to your themes folder using either of these commands:

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

- copy it to the `/usr/share/icons` directory as administrator allowing all users on the machine to use it.

**Method 3**

As distro-specific packages are created, I will add them here:

* [Arch AUR](https://aur.archlinux.org/packages/victory-icon-theme-git/)

**Configure and Apply the theme**

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


<a name="contributedonate"></a>

## Contribute or Donate

If anyone would like to contribute, please feel free to let me know where icons are missing, file a bug report if you have any problems, or even help out with an icon or two if you'd like. I really don't have much interest in App icons, so if anyone would like to submit some matching icons to go along with the theme that would be nice. Darker panel icons for light panels is something I'd like to see in the future but am not working on right now, so if anyone wants to do that it would be helpful.

I have created a [Patreon page here](https://www.patreon.com/newhoa) for anyone interested in showing support via Patreon. I will try to post updates, previews, etc there.

For those not interested in using Patreon, I've also started a [Liberapay page here](https://liberapay.com/newhoa/).

If you prefer to donate via Paypal, my paypal is `newhoa.donate` (AT) `linuxmail.org` or simply [donate via paypal here](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=newhoa%2edonate%40linuxmail%2eorg&lc=US&item_name=newhoa&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

I don't know if people are interested in showing monetary support, but I like to contribute to those whose work I find value in and hopefully people who find value in my work or think that what I do is worth a few dollars might do the same. I've worked for many years and hundreds of hours on this theme. I've enjoyed every second of it and it has been an incredible learning experience. I'll continue to do it because I enjoy it and it's my way to give something to the FOSS community that I love, admire, and am indebted to. I would greatly appreciate help in any form and thank anyone who feels inclined to do so. Thank you all for your support.
