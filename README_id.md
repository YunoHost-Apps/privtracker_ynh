<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# PrivTracker untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/privtracker)](https://ci-apps.yunohost.org/ci/apps/privtracker/)
![Status kerja](https://apps.yunohost.org/badge/state/privtracker)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/privtracker)

[![Pasang PrivTracker dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privtracker)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang PrivTracker secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

PrivTracker allows you to share torrent files only with your friends and nobody else. Unlike public trackers, it shares peers only within a group using the same announce URL. It really works like a private tracker, but can be generated with one click of a button.


**Versi terkirim:** 1.1.5~ynh1

**Demo:** <https://demo.example.com>

## Tangkapan Layar

![Tangkapan Layar pada PrivTracker](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://privtracker.com/>
- Dokumentasi pengguna resmi: <https://privtracker.com/>
- Dokumentasi admin resmi: <https://yunohost.org/packaging_apps>
- Depot kode aplikasi hulu: <https://github.com/meehow/privtracker>
- Gudang YunoHost: <https://apps.yunohost.org/app/privtracker>
- Laporkan bug: <https://github.com/YunoHost-Apps/privtracker_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing --debug
atau
sudo yunohost app upgrade privtracker -u https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
