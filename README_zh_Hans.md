<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Mollysocket

[![集成程度](https://apps.yunohost.org/badge/integration/mollysocket)](https://ci-apps.yunohost.org/ci/apps/mollysocket/)
![工作状态](https://apps.yunohost.org/badge/state/mollysocket)
![维护状态](https://apps.yunohost.org/badge/maintained/mollysocket)

[![使用 YunoHost 安装 Mollysocket](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mollysocket)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Mollysocket。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

MollySocket allows getting signal notifications via UnifiedPush. It works like a linked device, which doesn't have an encryption key, connected to the Signal server. Everytime it receives an encrypted event, it notifies your mobile via UnifiedPush.


**分发版本：** 1.5.5~ynh1
## 文档与资源

- 官方应用网站： <https://molly.im/>
- 官方管理文档： <https://github.com/mollyim/mollysocket/blob/main/README.md>
- 上游应用代码库： <https://github.com/mollyim/mollysocket>
- YunoHost 商店： <https://apps.yunohost.org/app/mollysocket>
- 报告 bug： <https://github.com/YunoHost-Apps/mollysocket_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
或
sudo yunohost app upgrade mollysocket -u https://github.com/YunoHost-Apps/mollysocket_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
