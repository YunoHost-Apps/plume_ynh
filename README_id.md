<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Plume untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/plume)](https://ci-apps.yunohost.org/ci/apps/plume/)
![Status kerja](https://apps.yunohost.org/badge/state/plume)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/plume)

[![Pasang Plume dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Plume secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Versi terkirim:** 0.7.2~ynh2

**Demo:** <https://joinplu.me/#instances>

## Tangkapan Layar

![Tangkapan Layar pada Plume](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://joinplu.me/>
- Dokumentasi admin resmi: <https://docs.joinplu.me/>
- Depot kode aplikasi hulu: <https://github.com/Plume-org/Plume>
- Gudang YunoHost: <https://apps.yunohost.org/app/plume>
- Laporkan bug: <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
atau
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
