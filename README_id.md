<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Hat.sh untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/hat.svg)](https://ci-apps.yunohost.org/ci/apps/hat/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/hat.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/hat.maintain.svg)

[![Pasang Hat.sh dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hat)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Hat.sh secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Hat.sh is a web app that provides secure local file encryption in the browser. It's fast, secure, and uses modern cryptographic algorithms with chunked AEAD stream encryption/decryption.


**Versi terkirim:** 2.3.6~ynh4

**Demo:** <https://hat.sh>

## Tangkapan Layar

![Tangkapan Layar pada Hat.sh](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <hat.sh>
- Dokumentasi admin resmi: <https://hat.sh/about/>
- Depot kode aplikasi hulu: <https://github.com/sh-dv/hat.sh>
- Gudang YunoHost: <https://apps.yunohost.org/app/hat>
- Laporkan bug: <https://github.com/YunoHost-Apps/hat_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/hat_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
atau
sudo yunohost app upgrade hat -u https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
