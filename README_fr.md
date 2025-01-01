<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Mollysocket pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/mollysocket)](https://ci-apps.yunohost.org/ci/apps/mollysocket/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/mollysocket)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/mollysocket)

[![Installer Mollysocket avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mollysocket)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Mollysocket rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

MollySocket permet d'obtenir des notifications Signal via UnifiedPush. Il fonctionne comme un périphérique lié, qui n'a pas de clé de chiffrement, connecté au serveur Signal. Chaque fois qu'il reçoit un événement chiffré, il informe votre téléphone via UnifiedPush.


**Version incluse :** 1.4.1~ynh1
## Documentations et ressources

- Site officiel de l’app : <https://molly.im/>
- Documentation officielle de l’admin : <https://github.com/mollyim/mollysocket/blob/main/README.md>
- Dépôt de code officiel de l’app : <https://github.com/mollyim/mollysocket>
- YunoHost Store : <https://apps.yunohost.org/app/mollysocket>
- Signaler un bug : <https://github.com/YunoHost-Apps/mollysocket_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mollysocket -u https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
