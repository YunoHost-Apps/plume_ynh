# Plume for Yunohost

[![Integration level](https://dash.yunohost.org/integration/plume.svg)](https://ci-apps.yunohost.org/jenkins/job/plume%20%28Community%29/lastBuild/consoleFull)

[![Install plume with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=plume)
<br>
**Warning:** The package can take **15 to 30 minutes** to complete depending on your system configuration. **Don't intrupt the installation process while installing.**

## Links

- [YunoHost project](https://yunohost.org)
- [Plume Github page](https://github.com/Plume-org/Plume)
- [Demo instance of Plume](https://baptiste.gelez.xyz/)

## Plume
Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


## Important points to read before installing the app
1. **Plume** is still in **pre-release** stage and undergoing heavy development, so there can be **bugs**.
1. **Plume** require a dedicated **root domain**, eg. plume.domain.tld
1. **Plume** require a valid **certificate** installed on the domain. Yunohost can **install Letsencrypt certificate** on the domain from **admin web-interface** or through **command-line**.
1. This package is **multi-instance** that means you can run **multiple Plume instances** on a **single server**.
1. There is **No LDAP** support for Pleroma yet.
1. **Admin username** and **password** will be sent to the **email address** of the admin.
