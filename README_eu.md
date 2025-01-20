<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Mollysocket YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/mollysocket)](https://ci-apps.yunohost.org/ci/apps/mollysocket/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/mollysocket)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/mollysocket)

[![Instalatu Mollysocket YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mollysocket)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Mollysocket YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

MollySocket allows getting signal notifications via UnifiedPush. It works like a linked device, which doesn't have an encryption key, connected to the Signal server. Everytime it receives an encrypted event, it notifies your mobile via UnifiedPush.


**Paketatutako bertsioa:** 1.6.0~ynh1
## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://molly.im/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/mollyim/mollysocket/blob/main/README.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/mollyim/mollysocket>
- YunoHost Denda: <https://apps.yunohost.org/app/mollysocket>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/mollysocket_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
edo
sudo yunohost app upgrade mollysocket -u https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
