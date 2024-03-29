<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Plume pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)

[![Installer Plume avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Plume rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Version incluse :** 0.7.2~ynh2

**Démo :** <https://joinplu.me/#instances>

## Captures d’écran

![Capture d’écran de Plume](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://joinplu.me/>
- Documentation officielle de l’admin : <https://docs.joinplu.me/>
- Dépôt de code officiel de l’app : <https://github.com/Plume-org/Plume>
- YunoHost Store : <https://apps.yunohost.org/app/plume>
- Signaler un bug : <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
ou
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
