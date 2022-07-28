---
description: 我们严格按照 隐私策略 执行，并使用最新版本服务端软件。
---

# 给高级用户的提示

## 提示 <a href="#ti-shi" id="ti-shi"></a>

* OpenFrp支持frp官方最新版本以及其他的frp发行版本，您可以前往任意站点下载任意版本的frp客户端(0.18以上版本)。 如果该客户端支持编辑frpc配置文件，则该frp客户端可以使用OpenFrp,使用方法与普通配置文件版本客户端相同！
* **注意：请从您所信任的站点下载非openfrp提供的frpc程序，如frp的官方github的发行版本等，我们不能保证您通过非openfrp下载的frpc程序没有恶意行为！**

## 自定义性 <a href="#zi-ding-yi-xing" id="zi-ding-yi-xing"></a>

可使用直接编辑 `frpc.ini` 的方式自定义，请从隧道列表的「配置文件」项目中复制并修改，只要不修改关键连接参数（`host`, `port`, `token`, `user`, ...），均可正常运行。

## 启动器移植 <a href="#qi-dong-qi-yi-zhi" id="qi-dong-qi-yi-zhi"></a>

如果您想要自己实现GUI图形启动器的话，可以参见我们的[api文档](https://apidoc.openfrp.net/)

**请注意该 API 并非稳定标准，属于内部使用 API，随时可能变更，如果存在相关修改不会进行通知。**

## 兼容性 <a href="#jian-rong-xing" id="jian-rong-xing"></a>

我们的服务兼容 [上游开源版本](https://github.com/fatedier/frp) 的客户端 `0.18.0+` 。

也就是说您可以使用几乎任何现有的 frp 客户端来使用我们的服务，只需根据隧道的「配置文件」手动填写关键连接参数，或直接复制配置文件启动即可

如果您是使用 Windows XP 或 Windows Vista 的极客用户，请使用上游的 [0.28.2 版本](https://github.com/fatedier/frp/releases/tag/v0.28.2) 。

使用任何非本网站分发的最新版客户端，均视为放弃相关支持，由此带来的任何问题请您发扬极客精神自行解决。
