<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 MiniDLNA

[![集成程度](https://dash.yunohost.org/integration/minidlna.svg)](https://dash.yunohost.org/appci/app/minidlna) ![工作状态](https://ci-apps.yunohost.org/ci/badges/minidlna.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/minidlna.maintain.svg)

[![使用 YunoHost 安装 MiniDLNA](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=minidlna)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 MiniDLNA。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

MiniDLNA is a lightweight [DLNA](https://fr.wikipedia.org/wiki/Digital_Living_Network_Alliance) server.
It allows to easily share multimedia files with any compatible devices present on the LAN.
MiniDLNA does not have a graphical interface, but does not require any special configuration.

## YunoHost specific features

* Use shared Multimedia Directories
* Linked to transmission, Nextcloud and all other app which use Multimedia Directories.


**分发版本：** 1.3.0~ynh1
## 文档与资源

- 官方应用网站： <http://minidlna.sourceforge.net>
- YunoHost 商店： <https://apps.yunohost.org/app/minidlna>
- 报告 bug： <https://github.com/YunoHost-Apps/minidlna_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
或
sudo yunohost app upgrade minidlna -u https://github.com/YunoHost-Apps/minidlna_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
