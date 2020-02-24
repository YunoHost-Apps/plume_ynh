# Plume app for Yunohost

[![Integration level](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume)  
[![Install Plume with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=plume)

> *This package allow you to install Plume quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database. 

**Shipped version:** 0.4.0-alpha-4

**Warning:** The package can take **15 to 30 minutes** to complete depending on your system configuration. **Don't intrupt the installation process while installing.**

## Important points to read before installing
1. **Plume** is still in **pre-release** stage and undergoing heavy development, so there can be **bugs**.
1. **Plume** require a dedicated **root domain**, eg. plume.domain.tld
1. **Plume** require a valid **certificate** installed on the domain. Yunohost can **install Letsencrypt certificate** on the domain from **admin web-interface** or through **command-line**.
1. This package is **multi-instance** that means you can run **multiple Plume instances** on a **single server**.
1. There is **No LDAP** support for Plume yet.

## Screenshots

![plume-screenshot1](https://user-images.githubusercontent.com/30271971/52232065-d6d83600-28bb-11e9-9a0a-b4b139c2eb25.png)

## Demo

* [List of instances](https://joinplu.me/#instances)

## Documentation

 * Official documentation: https://docs.joinplu.me/

## YunoHost specific features

#### Multi-users support

There is **No LDAP** support for Plume yet but the app can be used by multiple users

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/plume%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/plume/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/plume%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/plume/)

## Limitations

* No known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/plume_ynh/issues
 * App website: https://joinplu.me/
 * Upstream app repository: https://github.com/Plume-org/Plume
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
or
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```
