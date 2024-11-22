<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Hat.sh

[![集成程度](https://dash.yunohost.org/integration/hat.svg)](https://ci-apps.yunohost.org/ci/apps/hat/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/hat.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/hat.maintain.svg)

[![使用 YunoHost 安装 Hat.sh](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hat)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Hat.sh。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Hat.sh is a web app that provides secure local file encryption in the browser. It's fast, secure, and uses modern cryptographic algorithms with chunked AEAD stream encryption/decryption.


**分发版本：** 2.3.6~ynh4

**演示：** <https://hat.sh>

## 截图

![Hat.sh 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <hat.sh>
- 官方管理文档： <https://hat.sh/about/>
- 上游应用代码库： <https://github.com/sh-dv/hat.sh>
- YunoHost 商店： <https://apps.yunohost.org/app/hat>
- 报告 bug： <https://github.com/YunoHost-Apps/hat_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/hat_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
或
sudo yunohost app upgrade hat -u https://github.com/YunoHost-Apps/hat_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
