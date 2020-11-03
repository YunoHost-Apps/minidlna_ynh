# MiniDLNA for YunoHost

[![Integration level](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna) ![](https://ci-apps.yunohost.org/ci/badges/minidlna.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/minidlna.maintain.svg)  
[![Install MiniDLNA with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=minidlna)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install MiniDLNA quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

MiniDLNA is a simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients.

**Shipped version:** Debian repositories versions. Currently 1.2.1

## Screenshots

## Demo

No demo available.

## Configuration

Edit the file `/etc/minidlna.conf` to adjust the configuration of MiniDLNA.

## Documentation

 * YunoHost documentation: https://yunohost.org/#/app_minidlna

## YunoHost specific features

* Use shared Multimedia Directories
* Linked to transmission, Nextcloud and all other app which use Multimedia Directories.

#### Multi-users support

Not relevant.

#### Supported architectures

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/minidlna%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/minidlna/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/minidlna%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/minidlna/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/minidlna_ynh/issues
 * MiniDLNA website: http://minidlna.sourceforge.net/
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
or
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
```
