### What multimedia files are shared?

MiniDLNA is sharing the folder `/home/yunohost.multimedia/share`, which is common to each user in `/home/$USER/Multimedia/Share`.
[More information about multimedia files here.](https://github.com/YunoHost-Apps/yunohost.multimedia)

If [Transmission](https://github.com/YunoHost-Apps/transmission_ynh) is installed, the downloaded media will be available in DLNA.

### How to view and play media files shared by miniDLNA?

To view and play media files, all you need is a compatible client DLNA/UPNP.

The majority of set-top boxes provided by ISPs are DLNA compatible, simply look for sources of external media.
This is also true for the latest generation game consoles connected to internet.

Some TV and Blu-ray player are also DLNA compatible.

In any case, it is generally sufficient to seek external sources, USB etc., to find the DLNA server, displayed under the name **YunoHost DLNA**.

There are a multitude of DLNA client for all platforms, including the following [not exhaustive list](https://en.wikipedia.org/wiki/List_of_UPnP_AV_media_servers_and_clients#UPnP_AV_clients).
In general, a DLNA client does not require any special configuration to access the media sharing.
