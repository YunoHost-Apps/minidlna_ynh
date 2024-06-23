<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# MiniDLNA YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/minidlna.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/minidlna.maintain.svg)

[![Instalatu MiniDLNA YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minidlna)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek MiniDLNA YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

MiniDLNA is a lightweight [DLNA](https://fr.wikipedia.org/wiki/Digital_Living_Network_Alliance) server.
It allows to easily share multimedia files with any compatible devices present on the LAN.
MiniDLNA does not have a graphical interface, but does not require any special configuration.

## YunoHost specific features

* Use shared Multimedia Directories
* Linked to transmission, Nextcloud and all other app which use Multimedia Directories.


**Paketatutako bertsioa:** 1.3.0~ynh1
## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://minidlna.sourceforge.net>
- YunoHost Denda: <https://apps.yunohost.org/app/minidlna>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/minidlna_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
edo
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
