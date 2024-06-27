<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Plume YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/plume.svg)](https://ci-apps.yunohost.org/ci/apps/plume/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)

[![Instalatu Plume YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Plume YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Paketatutako bertsioa:** 0.7.2~ynh2

**Demoa:** <https://joinplu.me/#instances>

## Pantaila-argazkiak

![Plume(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://joinplu.me/>
- Administratzaileen dokumentazio ofiziala: <https://docs.joinplu.me/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Plume-org/Plume>
- YunoHost Denda: <https://apps.yunohost.org/app/plume>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
edo
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
