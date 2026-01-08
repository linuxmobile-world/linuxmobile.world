---
layout: post
title: Community update for Nokia N9
date: 2026-01-07 20:28 +0300
---

This is page for Nokia N9 community update.

Community update includes following fixes and QOL features:
- Updated timezone database
- Chrony daemon for syncing time (you wont have to scroll all the way from 2011 when entering date🙂)
- TLS Fix
- FrogFind search engine for browser
- Fix for connectivity test
- Hacker package manager:
    - No notice when installing 3rdparty packages
    - All packages are installed with AEGIS_FIXED_ORIGIN=com.nokia.maemo

To install this update you need the following:
- [N9RepoMirror](http://apt.linuxmobile.world/MeeGo/apt-repo/pool/main/n9repomirror_0.7.5_armel.deb)
- Developer mode active (you can enable it after install N9RepoMirror)
- [Hacked apt and dpkg](http://apt.linuxmobile.world/MeeGo/apt-repo/pool/main/hack-installer_1.0.10_armel.deb)
- [WunderWungiel repository](http://apt.linuxmobile.world/MeeGo/apt-repo/repo-installer_0.0.6_armel.deb)
- [Octo repository](http://apt.linuxmobile.world/MeeGo/octo/repoinstaller.deb)

Currently the following region codes are supported: 009, 001. You can help support your model - reach out to [t.me/mrvn4](https://t.me/mrvn4). 

# Installation

0. After installing Octo repository, you may get notification about "Device Update" - do NOT click it yet, because you need patched installer to install it (community update will install it)

1. Enter `devel-su` in terminal app, type in default password `rootme`

2. Type in the following command: `apt-get update`

3. Run `aegis-apt-get install mp-harmattan-YOUR_DEVICE_CODE-pr`, e.g. `aegis-apt-get install mp-harmattan-009-pr`

4. Now you have community update installed!