# MiniDLNA pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/minidlna.svg)](https://ci-apps.yunohost.org/jenkins/job/minidlna%20%28Community%29/lastBuild/consoleFull)  
[![Installer MiniDLNA avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=minidlna)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer MiniDLNA rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé

MiniDLNA est un simple serveur multimédia, dont le but est d'être entièrement compatible avec les clients DLNA/UPnP-AV.

**Version embarquée:** Versions des dépôts Debian. Actuellement 1.1.2 et 1.1.6

## Captures d'écran

## Configuration

Editez le fichier `/etc/minidlna.conf` pour ajuster la configuration de MiniDLNA.

## Documentation

 * Documentation YunoHost: https://yunohost.org/#/app_minidlna

## Fonctionnalités spécifiques à YunoHost

* Utilise les répertoires multimédia partagés.
* Lié à transmission, nextcloud et toute autre application qui utilise les répertoires multimédia.

#### Support multi-utilisateurs

Non applicable.

#### Architectures supportées.

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/minidlna%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/minidlna%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/minidlna%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/minidlna%20(Community)%20(%7EARM%7E)/)

## Limitations

## Informations additionnelles

## Liens

 * Reporter un bug: https://github.com/YunoHost-Apps/minidlna_ynh/issues
 * Site de MiniDLNA: http://minidlna.sourceforge.net/
 * Site de YunoHost: https://yunohost.org/

---

Informations à l'intention des développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --verbose
ou
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --verbose
```
