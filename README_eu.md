<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# PrivTracker YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/privtracker)](https://ci-apps.yunohost.org/ci/apps/privtracker/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/privtracker)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/privtracker)

[![Instalatu PrivTracker YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privtracker)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek PrivTracker YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

PrivTracker allows you to share torrent files only with your friends and nobody else. Unlike public trackers, it shares peers only within a group using the same announce URL. It really works like a private tracker, but can be generated with one click of a button.


**Paketatutako bertsioa:** 1.1.5~ynh1

**Demoa:** <https://demo.example.com>

## Pantaila-argazkiak

![PrivTracker(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://privtracker.com/>
- Erabiltzaileen dokumentazio ofiziala: <https://privtracker.com/>
- Administratzaileen dokumentazio ofiziala: <https://yunohost.org/packaging_apps>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/meehow/privtracker>
- YunoHost Denda: <https://apps.yunohost.org/app/privtracker>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/privtracker_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing --debug
edo
sudo yunohost app upgrade privtracker -u https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
