

[![Integration level](https://dash.yunohost.org/integration/plume.svg)](https://dash.yunohost.org/appci/app/plume)  
[![Install Plume with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=plume)

> *This package allow you to install plume quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database. 

**Shipped version:** 0.2.0

**Warning:** The package can take **15 to 30 minutes** to complete depending on your system configuration. **Don't intrupt the installation process while installing.**

## Important points to read before installing the app
1. **Plume** is still in **pre-release** stage and undergoing heavy development, so there can be **bugs**.
1. **Plume** require a dedicated **root domain**, eg. plume.domain.tld
1. **Plume** require a valid **certificate** installed on the domain. Yunohost can **install Letsencrypt certificate** on the domain from **admin web-interface** or through **command-line**.
1. This package is **multi-instance** that means you can run **multiple Plume instances** on a **single server**.
1. There is **No LDAP** support for Plume yet.
1. **Admin username** and **password** will be sent to the **email address** of the admin.

## License

License AGPL-3.0-only

## Demo

* [List of instances](https://joinplu.me/#instances)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://docs.joinplu.me/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

There is **No LDAP** support for Plume yet
But the app can be used by multiple users

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/plume%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/plume/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/plume%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/plume/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/plume%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/plume/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**  
https://yunohost.org/packaging_apps
## Links

 * Report a bug: https://github.com/YunoHost-Apps/plume_ynh/issues
 * App website: https://joinplu.me/
 * App Github: https://github.com/Plume-org/Plume
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
or
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```
