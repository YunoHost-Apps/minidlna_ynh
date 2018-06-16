# MiniDLNA for YunoHost

[![Integration level](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna)  
[![Install MiniDLNA with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=minidlna)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install MiniDLNA quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

MiniDLNA is a simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients.

**Shipped version:** Debian repositories versions. Currently 1.1.2 and 1.1.6

## Screenshots

## Demo

No demo available.

## Configuration

Edit the file `/etc/minidlna.conf` to adjust the configuration of MiniDLNA.

## Documentation

 * YunoHost documentation: https://yunohost.org/#/app_minidlna

## YunoHost specific features

* Use shared Multimedia Directories
* Linked to transmission, nextcloud and all other app which use Multimedia Directories.

#### Multi-users support

Not relevant.

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/minidlna%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/minidlna%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/minidlna%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/minidlna%20(Community)%20(%7EARM%7E)/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/minidlna_ynh/issues
 * MiniDLNA website: http://minidlna.sourceforge.net/
 * YunoHost website: https://yunohost.org/

---

Developers infos
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --verbose
or
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --verbose
```
