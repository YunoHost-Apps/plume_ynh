# Plume pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume) ![](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)  
[![Installer Plume avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Plume rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database. 

**Version incluse :** 0.6.0~ynh2

**Démo :** https://joinplu.me/#instances

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

**Warning:** The package can take **15 to 30 minutes** to complete depending on your system configuration. **Don't intrupt the installation process while installing.**

## Important points to read before installing
1. **Plume** is still in **pre-release** stage and undergoing heavy development, so there can be **bugs**.
1. **Plume** require a dedicated **root domain**, eg. plume.domain.tld
1. **Plume** require a valid **certificate** installed on the domain. Yunohost can **install Letsencrypt certificate** on the domain from **admin web-interface** or through **command-line**.
1. This package is **multi-instance** that means you can run **multiple Plume instances** on a **single server**.

#### Multi-user support

LDAP is activated but HTTP auth is not supported
## Documentations et ressources

* Site officiel de l'app : https://joinplu.me/
* Documentation officielle de l'admin : https://docs.joinplu.me/
* Dépôt de code officiel de l'app : https://github.com/Plume-org/Plume
* Documentation YunoHost pour cette app : https://yunohost.org/app_plume
* Signaler un bug : https://github.com/YunoHost-Apps/plume_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
ou
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps