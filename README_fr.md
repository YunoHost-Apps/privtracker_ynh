<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# PrivTracker pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/privtracker)](https://ci-apps.yunohost.org/ci/apps/privtracker/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/privtracker)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/privtracker)

[![Installer PrivTracker avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privtracker)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer PrivTracker rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

PrivTracker vous permet de partager des fichiers torrent uniquement avec vos amis et personne d'autre. Contrairement aux trackers publics, il ne partage les pairs qu'au sein d'un groupe utilisant la même URL d'annonce. Il fonctionne vraiment comme un tracker privé, mais peut être généré en un seul clic.


**Version incluse :** 1.1.5~ynh1

**Démo :** <https://demo.example.com>

## Captures d’écran

![Capture d’écran de PrivTracker](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://privtracker.com/>
- Documentation officielle utilisateur : <https://privtracker.com/>
- Documentation officielle de l’admin : <https://yunohost.org/packaging_apps>
- Dépôt de code officiel de l’app : <https://github.com/meehow/privtracker>
- YunoHost Store : <https://apps.yunohost.org/app/privtracker>
- Signaler un bug : <https://github.com/YunoHost-Apps/privtracker_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing --debug
ou
sudo yunohost app upgrade privtracker -u https://github.com/YunoHost-Apps/privtracker_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
