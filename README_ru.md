<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Hat.sh для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/hat.svg)](https://ci-apps.yunohost.org/ci/apps/hat/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/hat.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/hat.maintain.svg)

[![Установите Hat.sh с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hat)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Hat.sh быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Hat.sh is a web app that provides secure local file encryption in the browser. It's fast, secure, and uses modern cryptographic algorithms with chunked AEAD stream encryption/decryption.


**Поставляемая версия:** 2.3.6~ynh4

**Демо-версия:** <https://hat.sh>

## Снимки экрана

![Снимок экрана Hat.sh](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <hat.sh>
- Официальная документация администратора: <https://hat.sh/about/>
- Репозиторий кода главной ветки приложения: <https://github.com/sh-dv/hat.sh>
- Магазин YunoHost: <https://apps.yunohost.org/app/hat>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/hat_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/hat_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
или
sudo yunohost app upgrade hat -u https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
