<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Plume voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/plume.svg)](https://ci-apps.yunohost.org/ci/apps/plume/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)

[![Plume met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Plume snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Geleverde versie:** 0.7.2~ynh2

**Demo:** <https://joinplu.me/#instances>

## Schermafdrukken

![Schermafdrukken van Plume](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://joinplu.me/>
- Officiele beheerdersdocumentatie: <https://docs.joinplu.me/>
- Upstream app codedepot: <https://github.com/Plume-org/Plume>
- YunoHost-store: <https://apps.yunohost.org/app/plume>
- Meld een bug: <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
of
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
