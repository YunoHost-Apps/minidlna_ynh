Serveur DLNA pour YunoHost
==================

[Yunohost project](https://yunohost.org/#/)

Serveur DLNA très léger pour partager simplement les fichiers multimédia avec l'ensemble des appareils compatibles sur le réseau local.

http://minidlna.sourceforge.net/

Le script installe les paquets *i965-va-driver*, *i965-va-driver*, *libavcodec56*, *libavformat56*, *libavresample2*, *libavutil54*, *libexif12* *libflac8* *libgsm1* *libid3tag0* *libmp3lame0* *libogg0* *libopenjpeg5 *libopus0* *liborc-0.4-0* *libschroedinger-1.0-0* *libspeex1* *libtheora0* *libva1* *libvdpau1* *libvorbis0a* *libvorbisenc2* *libx264-142* *libxvidcore4* *va-driver-all* *vdpau-va-driver*.

[Documentation minidlna](https://yunohost.org/#/app_minidlna_fr) pour Yunohost.

**Mise à jour du package:**  
sudo yunohost app upgrade -u https://github.com/YunoHost-Apps/minidlna_ynh

**Multi-utilisateur:** Pas de gestion des utilisateurs, les partages sont accessible librement.
