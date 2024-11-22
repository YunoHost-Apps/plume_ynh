<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Plume для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/plume.svg)](https://ci-apps.yunohost.org/ci/apps/plume/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/plume.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/plume.maintain.svg)

[![Установите Plume с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plume)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Plume быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Federated blogging engine, based on ActivityPub. It uses the Rocket framework, and Diesel to interact with the database.


**Поставляемая версия:** 0.7.2~ynh2

**Демо-версия:** <https://joinplu.me/#instances>

## Снимки экрана

![Снимок экрана Plume](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://joinplu.me/>
- Официальная документация администратора: <https://docs.joinplu.me/>
- Репозиторий кода главной ветки приложения: <https://github.com/Plume-org/Plume>
- Магазин YunoHost: <https://apps.yunohost.org/app/plume>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/plume_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/plume_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
или
sudo yunohost app upgrade plume -u https://github.com/YunoHost-Apps/plume_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
