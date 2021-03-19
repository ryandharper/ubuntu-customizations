# ubuntu-customizations

My Ubuntu 20.04.2 LTS customizations - mostly a note to myself of what I've done so I can replicate it easily if needs be. Assumes minimal Ubuntu LTS 20.04.2 install.

## Theme & Feel

### Gnome/GDM Theme

<https://github.com/vinceliuice/WhiteSur-gtk-theme/>

```bash
sudo ./install.sh -i ubuntu -g
```

### Gnome Tweak Tool

```bash
sudo add-apt-repository universe
sudo apt install gnome-tweak-tool
```

### Extensions

<https://extensions.gnome.org/extension/358/activities-configurator/> - Use this to set Ubuntu icon for activities bar (Pictures/icons/activites-ubuntu.svg), set panel colour to Black

<https://extensions.gnome.org/extension/15/alternatetab/> - thumbnail & application icon

<https://extensions.gnome.org/extension/1465/desktop-icons/>

<https://extensions.gnome.org/extension/907/files-menu/>

<https://extensions.gnome.org/extension/708/panel-osd/> - 99.5% horizontal position

- Enable Tilix dropdown once installed

### Icons

<https://github.com/vinceliuice/WhiteSur-icon-theme>

## Packages

```
sudo apt-get install firefox tilix gnome-calendar libreoffice-gnome libreoffice qdirstat vagrant 
virtualbox qemu qemu-kvm libvirt-clients libvirt-daemon-system bridge-utils virt-manager python3-pip python3-venv
```

## Non standard Packages

<https://code.visualstudio.com/docs/setup/linux>
<https://code.visualstudio.com/docs/editor/settings-sync>
<https://www.spotify.com/us/download/linux/>
<https://store.steampowered.com/about/>
<https://discord.com/download>
<https://docs.docker.com/engine/install/ubuntu/>

## Peripherals
<https://github.com/Kurgol/keychron/blob/master/k2.md>
<https://github.com/medusalix/xow>
<https://github.com/BradyBrenot/huestacean>
Soundblaster X G6 - Check bin/setmic for bash script to be added to profile

## Pyenv

```
python3 -m pip install --user virtualenv
python3 -m venv env
```

## RVM 

https://rvm.io/rvm/install

```bash
rvm install 3.0.0
rvm use 3.0.0 --default
```

## ~/.bashrc
<https://github.com/Bash-it/bash-it>


```bash
cp -pr .bash_it/themes/ryan ~/.bash_it/themes/
```
```bash
.bashrc >> ~/.bashrc
```
