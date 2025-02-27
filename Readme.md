# Sddm-zelda-theme

A sddm login screen inspired by 1998 anime ["Serial Experiments Lain"](https://myanimelist.net/anime/339/Serial_Experiments_Lain)

**Note-
This is a fork.
Original version can be found [here](https://gitlab.com/mixedCase/sddm-lain-wired-theme)**

This one contains changes that I made for my 1366*786 screen.

# In action :-
You can watch the preview video [here.](https://youtu.be/M-p7cHx4OM0)

# Installation :-
- Make sure you have sddm installed and configured as your default login manager.
- Install the dependencies ```qt5-multimedia``` & ```qt5-quickcontrols``` using your package manager.
- Wav audio codecs are needed to play the sound, make sure you have package(s) that fulfill that installed. 
- Download the [latest release](https://github.com/anglakey/sddm-zelda-theme/releases/latest)
- Decompress the `*.zip` or `*.tar.gz` file or run `git clone https://github.com/anglakey/sddm-zelda-theme`
- Copy all files and directories into `/usr/share/sddm/themes/sddm-zeldatheme/` or open a terminal and run `sudo cp -r sddm-zelda-theme /usr/share/sddm/themes`

### Usage
- You can use KDE Settings to configure SDDM alternativly:
- Open up your configuration file `/etc/sddm.conf` and set `sddm-zelda-theme` as your current theme

```shell
[Theme]
# Current theme name
Current=sddm-zelda-theme
```
- Now you are all set. Enjoy the aesthetic.
