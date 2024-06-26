<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# MiniDLNA pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/minidlna.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/minidlna.maintain.svg)

[![Installer MiniDLNA avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minidlna)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer MiniDLNA rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

MiniDLNA est un serveur [DLNA](https://fr.wikipedia.org/wiki/Digital_Living_Network_Alliance) ultra léger.
Il permet de partager très simplement les fichiers multimédias avec tout les appareils compatibles présent sur le réseau local.
Minidlna ne dispose pas d'une interface graphique, mais ne nécessite pas de configuration particulière.

## Fonctionnalités spécifiques à YunoHost

* Utilise les répertoires multimédia partagés.
* Lié à transmission, Nextcloud et toute autre application qui utilise les répertoires multimédia.


**Version incluse :** 1.3.0~ynh1
## Documentations et ressources

- Site officiel de l’app : <http://minidlna.sourceforge.net>
- YunoHost Store : <https://apps.yunohost.org/app/minidlna>
- Signaler un bug : <https://github.com/YunoHost-Apps/minidlna_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
ou
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
