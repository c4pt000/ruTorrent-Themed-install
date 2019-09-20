for quickbox see:
https://github.com/c4pt000/quickbox-debian

# ** rutorrent themed


## orig rtinst @ https://github.com/arakasi72/rtinst

### Note: Now installs Lets Encrypt SSL certificates

#### 30 Second Guide

Ubuntu and Debian Seedbox Installation



Download and run setup (if logged in directly as root, do not need to use sudo)

	sudo bash -c "$(wget --no-check-certificate -qO - https://raw.githubusercontent.com/c4pt000/rtinst/master/rtsetup)"

and then to run the main script, ([check the options you can use](https://github.com/arakasi72/rtinst/wiki/Guide#21-main-script-options)):

	sudo rtinst


* [flatui-dark theme] <p align="center"><img src="https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/FlatUI_Dark.png" width="800"></p>


* [changing theme] <p align="center"><img src="https://raw.githubusercontent.com/wiki/Novik/ruTorrent/images/PluginTheme/theme13.png" width="600"></p>



## Source
**The main purpose of this repo is to list the 3rd-party ruTorrent themes, I'm not going to always keep them up-to-date so here are the source links (in case you'd want a newer version) :**
 
* [Agent34](https://code.google.com/p/agent34/)
 
* [Agent46](https://code.google.com/p/agent46/)
 
* [OblivionBlue](https://github.com/InAnimaTe/rutorrent-themes/tree/master/OblivionBlue)

* [FlatUI themes](https://github.com/exetico/FlatUI)

* [MaterialDesign](https://github.com/tomcdj71/ruTorrent-MaterialDesign)

* [club-QuickBox](https://github.com/QuickBox/club-QuickBox)

## Requirements
 
* [ruTorrent](https://github.com/Novik/ruTorrent)
* [Plugin: Theme](https://github.com/Novik/ruTorrent/wiki/PluginTheme)
* subversion: `apt-get install subversion`

## Installation
 
**Agent34** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/agent34.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/Agent34
```
 
**Agent46** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/agent46.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/Agent46
```
 
**OblivionBlue** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/oblivionblue.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/OblivionBlue
```
 
**MaterialDesign** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/materialdesign.jpg)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/MaterialDesign
```
 
**FlatUI_Dark** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/FlatUI_Dark.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/FlatUI_Dark
```
 
**FlatUI_Light** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/FlatUI_Light.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/FlatUI_Light
```
 
**FlatUI_Material** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/FlatUI_Material.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/FlatUI_Material
```
 
**club-QuickBox** [(screenshot)](https://raw.githubusercontent.com/ArtyumX/ruTorrent-Themes/master/club-QuickBox.png)
```
$ cd /var/www/rutorrent/plugins/theme/themes
$ svn co https://github.com/ArtyumX/ruTorrent-Themes/trunk/club-QuickBox
```

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>



It takes about 10 minutes to run, depending on your server setup. After you have run the script and everything is working, I suggest a reboot, the script does not automate this reboot, you need to do it manually using the reboot command.

[A detailed installation guide](https://github.com/arakasi72/rtinst/wiki/Installing-rtinst)

[A detailed user guide](https://github.com/arakasi72/rtinst/wiki/Guide)

**IMPORTANT: NOTE THE NEW SSH PORT AND MAKE SURE YOU CAN SSH INTO YOUR SERVER BEFORE CLOSING THE EXISTING SESSION**


Current release has been tested with clean installs of: 

	Ubuntu 16
	Ubuntu 17
	Ubuntu 18
	Ubuntu 19
	Debian 9 "Stretch"
	Debian 10 "Buster"

Services that will be installed and configured are

	1. vsftpd - ftp server
	2. libtorrent/rtorrent
	3. rutorrent
	4. Nginx (webserver)
	5. autodl-irssi
	6. webmin (optional see section 3.7 in main guide)


[rtinst installation guide](https://github.com/arakasi72/rtinst/wiki/Installing-rtinst)

[Additional information on all the features](https://github.com/arakasi72/rtinst/wiki/Guide)

For older unssuported OS [Older OS Installation Guide](https://github.com/arakasi72/rtinst/wiki/Installing-on-Older-OS). These include:
	
	Ubuntu 12 (old release)
	Ubuntu 13 (old release)
	Ubuntu 14 (old release)
	Ubuntu 15 (old release)
	Debian 7 "Wheezy" (old release)
	Debian 8 "Jessie" (old release)

To see latest updates to the script go to [Change Log](https://github.com/arakasi72/rtinst/wiki/Change-Log)

-------------------------------------------------------------------------

 Copyright (c) 2015 arakasi72 (https://github.com/arakasi72)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: 

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. 

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

 --> Licensed under the MIT license: http://www.opensource.org/licenses/mit-license.php


