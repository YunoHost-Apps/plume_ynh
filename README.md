# Plume for YunoHost

[![Integration level](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume) ![](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)  
[![Install Plume with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

> *This package allows you to install Plume quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database. 

**Shipped version:** 0.6.0

**Warning:** The package can take **15 to 30 minutes** to complete depending on your system configuration. **Don't intrupt the installation process while installing.**

## Important points to read before installing
1. **Plume** is still in **pre-release** stage and undergoing heavy development, so there can be **bugs**.
1. **Plume** require a dedicated **root domain**, eg. plume.domain.tld
1. **Plume** require a valid **certificate** installed on the domain. Yunohost can **install Letsencrypt certificate** on the domain from **admin web-interface** or through **command-line**.
1. This package is **multi-instance** that means you can run **multiple Plume instances** on a **single server**.

## Screenshots

![plume-screenshot1](https://user-images.githubusercontent.com/30271971/52232065-d6d83600-28bb-11e9-9a0a-b4b139c2eb25.png)

## Demo

* [List of instances](https://joinplu.me/#instances)

## Documentation

 * Official documentation: https://docs.joinplu.me/

## YunoHost specific features

#### Multi-user support

LDAP is activated but HTTP auth is not supported

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/plume.svg)](https://ci-apps.yunohost.org/ci/apps/plume/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/plume.svg)](https://ci-apps-arm.yunohost.org/ci/apps/plume/)

## Limitations

* No known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/plume_ynh/issues
 * App website: https://joinplu.me/
 * Upstream app repository: https://github.com/Plume-org/Plume
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
or
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```
