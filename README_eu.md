<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Hat.sh YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/hat.svg)](https://ci-apps.yunohost.org/ci/apps/hat/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/hat.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/hat.maintain.svg)

[![Instalatu Hat.sh YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hat)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Hat.sh YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Hat.sh is a web app that provides secure local file encryption in the browser. It's fast, secure, and uses modern cryptographic algorithms with chunked AEAD stream encryption/decryption.


**Paketatutako bertsioa:** 2.3.6~ynh4

**Demoa:** <https://hat.sh>

## Pantaila-argazkiak

![Hat.sh(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <hat.sh>
- Administratzaileen dokumentazio ofiziala: <https://hat.sh/about/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/sh-dv/hat.sh>
- YunoHost Denda: <https://apps.yunohost.org/app/hat>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/hat_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/hat_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
edo
sudo yunohost app upgrade hat -u https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
