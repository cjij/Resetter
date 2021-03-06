# Resetter v1.1.2-stable
![alt tag](https://github.com/gaining/Resetter/blob/master/Resetter/resetter-screenshot.png)

It is an application built with python and pyqt that will help to reset an Ubuntu, Linux-Mint, and some other distros to stock, without having to manually re-install by using a live usb/cd/dvd image. For the list of supported distros, please see the *Officially supported distros* section.

# How to install
Download the deb files found [here](https://github.com/gaining/Resetter/releases/latest) then on the terminal, run the following commands:

1. `sudo apt install gdebi`
2. `sudo gdebi add-apt-key_1.0-0.5_all.deb`
3. `sudo gdebi resetter_1.1.2-stable_all.deb`

# How does it work?
- Typical case of auto apps reset <br/>
installed programs list - updated manifest = non-default programs <br/>
updated manifest - installed programs list = MPIAs <br/>
reset = (Installed programs list - non-default programs) + MPIAs <br/>
There are other reset features, see features list.

# Status
- version 1.1.2 adds support for Ubuntu 17.10. I'm not sure if it's because ubuntu 17.10 is filled with bugs or it's a "Feature" by design but many QT apps that worked on earlier version were broken in this release.
- The software is stable. Feedback will be greatly appreciated.
- Working Project: Resetter-cli, a version of resetter that runs terminally due to be released this early November.
- Please check the [changelog](https://github.com/gaining/Resetter/blob/master/changelog) for more details.

# To Do
- Official video tutorial on YouTube
- Debian Jessie, Sketh support
- Make Resetter multilingual. (Will need help of volunteer translators)
- Make an app-image or flatpack as there are many reasons why Resetter needs to be portable.

# Bug reports
- If you find a bug or problem please create an issue on github.
- If you do not have a github account do not hesitate to contact me and send your bug report to gaining7@outlook.com.

# Options comparison

MPIA means missing pre-installed apps

<center>

| Features List                          | Option 1: Automatic Reset | Option 2: Custom Reset |
|----------------------------------------|:-------------------------:|:----------------------:|
| Auto remove apps for reset             |             ✓             |            ✓           |
| Choose which apps to remove for reset  |             ✗             |            ✓           |
| Remove old kernels                     |             ✗             |            ✓           |
| Choose to only delete user             |             ✗             |            ✓           |
| Delete users and home directories      |             ✓             |            ✓           |
| Choose which user to delete            |             ✗             |            ✓           |
| Create default backup user             |             ✓             |            ✓           |
| Create custom backup user              |             ✗             |            ✓           |
| Auto install MPIAs                     |             ✓             |            ✓           |
| Choose which MPIAs to install          |             ✗             |            ✓           |
| remove non-default users               |             ✓             |            ✓           |
| dependent package view                 |             ✗             |            ✓           |
| remove snap packages                   |             ✓             |            ✓           |


</center>

# Other features:
- Easy install: Basically, you will be able to build your own list of apps that you'd like to mass install after a reset or fresh install. It can also be used anytime to install a package. If you saved a backup file using the save feature prior to your reset or fresh install, you will be able to restore the apps from that list if they're available to install.

- Easy PPA: With this feature, you can search launchpad.net for PPAs containing apps directly from resetter and install it into your system. It will also grab the ppa's key automatically. This eliminates the need of using a terminal to add ppas from launchpad making distros more user friendly.

- Source Editor: It is a normal editor that can disable, enable, or remove ppas from a user's system but what makes this different from other source editors is that you can search for the ppa that you want to edit.

# Officially supported distros [64-bit]

- Linux Mint 17.3+
- Ubuntu 14.04+
- Elementary OS 0.4+
- Linux Deepin 15.4+

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8FET8RGU2ZKQ8)

# Contact
- If you wish to contact me about anything else reach me via gaining7@outlook.com.

# Donate
Please show your support by donating Resetter has helped you.
If you'd like your name to be on the donors list, I can arrange for that as well.

# Donors List
- Mez Pahlan - $10
