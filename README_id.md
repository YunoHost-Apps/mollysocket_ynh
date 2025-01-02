<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Mollysocket untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/mollysocket)](https://ci-apps.yunohost.org/ci/apps/mollysocket/)
![Status kerja](https://apps.yunohost.org/badge/state/mollysocket)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/mollysocket)

[![Pasang Mollysocket dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mollysocket)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Mollysocket secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

MollySocket allows getting signal notifications via UnifiedPush. It works like a linked device, which doesn't have an encryption key, connected to the Signal server. Everytime it receives an encrypted event, it notifies your mobile via UnifiedPush.


**Versi terkirim:** 1.5.5~ynh1
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://molly.im/>
- Dokumentasi admin resmi: <https://github.com/mollyim/mollysocket/blob/main/README.md>
- Depot kode aplikasi hulu: <https://github.com/mollyim/mollysocket>
- Gudang YunoHost: <https://apps.yunohost.org/app/mollysocket>
- Laporkan bug: <https://github.com/YunoHost-Apps/mollysocket_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
atau
sudo yunohost app upgrade mollysocket -u https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
