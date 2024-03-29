### Quels fichiers multimédias sont partagés ?

Minidlna partage le dossier `/home/yunohost.multimedia/share`, qui est commun à chaque utilisateur dans le dossier `/home/$USER/Multimedia/Share`.

[Plus d'informations sur les dossiers multimedia ici.](https://github.com/YunoHost-Apps/yunohost.multimedia)

Si [Transmission](https://github.com/YunoHost-Apps/transmission_ynh) est installé, les médias téléchargés seront disponible en DLNA.

### Comment consulter et lire les fichiers multimédias partagés par miniDLNA?

Pour voir et lire les fichiers multimédias, il suffit de disposer d'un client compatible DLNA/UPNP.

La majorité des décodeurs TV fourni par les FAI sont compatible DLNA, il suffit de chercher les sources de médias externe.
C'est le cas également pour les consoles de jeux dernière génération connectée à internet.

Certaines TV et lecteur Blu-ray sont également compatibles DLNA.

Dans tout les cas, il suffit en général d'aller chercher les sources externes, USB etc., pour trouver le serveur DLNA, affiché sous le nom **Yunohost DLNA**.

Il existe une multitude de client DLNA pour toutes les plateformes, dont voici une [liste non exhaustive](https://en.wikipedia.org/wiki/List_of_UPnP_AV_media_servers_and_clients#UPnP_AV_clients).
De manière générale, un client DLNA ne nécessite pas de configuration particulière pour accéder au partage de fichiers multimédias.
