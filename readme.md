# **Ubuntu 22.0.04.4 Developer Editions**

> _This document is for developer who want to go beyound the normal ubuntu experience!!_

- [**Ubuntu 22.0.04.4 Developer Editions**](#ubuntu-220044-developer-editions)
  - [First Things First](#first-things-first)
  - [Tweaks \& Extension Manager](#tweaks--extension-manager)
  - [Folder Structures For Customization](#folder-structures-for-customization)
  - [Download Icons, Themes, Fonts](#download-icons-themes-fonts)
          - [.fonts](#fonts)
          - [.icons](#icons)
          - [.themes](#themes)
  - [Download Extensions](#download-extensions)
  - [Install nvm](#install-nvm)
  - [Install Docker](#install-docker)
  - [Install flatpak](#install-flatpak)
  - [Useful flathub packages](#useful-flathub-packages)
  - [Other cli tool](#other-cli-tool)

## First Things First

> Make sure the os is **UpToDate**. Use the following bash command.

```bash
sudo apt update && sudo apt upgrade
```

[[Go To Top](#ubuntu-220044-developer-editions)]

## Tweaks & Extension Manager

In order to change the look of the **_ubuntu_**; you will need to install two app from the snap store.

> Install **_Tweaks_** & **_Extension Manager_** app from snap store.

GNOME **_Tweaks_** allows adjusting advanced GNOME options. It can install and manage themes and extensions, change power settings, manage startup applications, and enable desktop icons among other settings.

**_Extension Manager_** is a utility for browsing and installing GNOME Shell Extensions.

[[Go To Top](#ubuntu-220044-developer-editions)]

## Folder Structures For Customization

**.themes**, **.icons** & **.fonts** folder are needed for customization.

```plaintext

|--root
    |--.fonts
    |--.icons
    |--.themes

```

[[Go To Top](#ubuntu-220044-developer-editions)]

## Download Icons, Themes, Fonts

> Here my favorites icons, themes & fonts. You can also download from their official [gnome-look.org](https://www.gnome-look.org/browse/) web page.

###### .fonts

- [Download Poppins Fonts](https://github.com/sawissac/ubuntu-22.0.04.4-dev-editions/blob/main/fonts/poppins.tar.xz)
- [Download Firacode Fonts](https://github.com/sawissac/ubuntu-22.0.04.4-dev-editions/blob/main/fonts/firacode.tar.xz)

###### .icons

- [Download Kora Icons](https://github.com/sawissac/ubuntu-22.0.04.4-dev-editions/blob/main/icons/kora.tar.xz)
- [Download Bibata Cursor Icons](https://github.com/sawissac/ubuntu-22.0.04.4-dev-editions/blob/main/icons/Bibata-Modern-Ice.tar.xz)

###### .themes

- [Download Nordic Darker Application Theme](https://github.com/sawissac/ubuntu-22.0.04.4-dev-editions/blob/main/themes/Nordic-darker.tar.xz)
- [Download Marble Blue Dark Shell Theme](https://github.com/sawissac/ubuntu-22.0.04.4-dev-editions/blob/main/themes/Marble-blue-dark.tar.xz)

[[Go To Top](#ubuntu-220044-developer-editions)]

## Download Extensions

> First you will need to open the Extensions Manager App. Here my recommended extensions lists.

- Blur my Shell @aunetx
- Caffeine @patapon.info
- Clipboard Indicator @tudmotu.com
- Customize Clock on Lock Screen @pratap.fastmail.fm
- Dash to Dock @micxgx.gmail.com
- Emoji Copy @felipeftn
- Gnome 4x UI Improvements @itstime.tech
- Impatience @gfxmonk.net
- Just Perfection @just-perfection
- OpenWeather @jenslody.de
- Panel corners @aunetx
- Rounded Window Corners @yilozt
- Search Light @Icedman
- User Themes @gnome-shell
- Vitals @CoreCoding.com
- WinTile @nowsci.com

[[Go To Top](#ubuntu-220044-developer-editions)]

## Install nvm

> Go read this document [here](https://medium.com/devops-technical-notes-and-manuals/how-to-install-docker-on-ubuntu-22-04-b771fe57f3d2)

## Install Docker

> Go read this document [here](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04)

## Install flatpak

> Go read this document [here](https://flatpak.org/setup/Ubuntu)

## Useful flathub packages

- flatseal
- chrome
- inkscape
- discord
- obsidian
- vlc
- gimp

## Other cli tool

- htop
- radeontop
