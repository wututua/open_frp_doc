# 安全提示

本文的初衷是防止您产生下图情况

![leak\_service](https://docs.openfrp.net/docs/assests/leak\_after.png)

## 安全准则 <a href="#an-quan-zhun-ze" id="an-quan-zhun-ze"></a>

* 对于暴露在网络上的任何东西，密码一定要足够强
* 保持谦逊是美德，也是保护您不被人攻击的隐身咒
* 如果您知道一个东西以漏洞闻名，那就为它多加防护
* 如果没有特殊需求，使用最新版程序通常都是一个好选择
* 尤其是当您使用诸如 WordPress 这类历史悠久的项目时，您遇到陈年老代码带来漏洞的可能性将急速升高
* 请务必打开各个程序自带的更新检测，并总在第一时间进行更新

## 对于HTTP(S)隧道的安全提示 <a href="#dui-yu-https-sui-dao-de-an-quan-ti-shi" id="dui-yu-https-sui-dao-de-an-quan-ti-shi"></a>

首先，HTTP 是一个明文传输的协议，对于保证 HTTP 传输安全且不被篡改的最优先事项应当是升级为 HTTPS 并且采用可信的证书

#### [添加鉴权](https://docs.openfrp.net/#/docs/security?id=%e6%b7%bb%e5%8a%a0%e9%89%b4%e6%9d%83) <a href="#tian-jia-jian-quan" id="tian-jia-jian-quan"></a>

> 对 HTTP 协议添加鉴权所起到的保护作用微乎其微 但仍然可以像英国政府一样「让人相信您受到了保护」 -by SakuraFrp Help document

为了保护您的页面不被直接窥视，通过 Basic Auth 添加一个鉴权会是一个低成本的解决方案

Basic Auth 的配置方式大同小异，下面是常见web server的相关文档链接：

* [Nginx](https://docs.nginx.com/nginx/admin-guide/security-controls/configuring-http-basic-authentication/)
* [Apache](https://www.digitalocean.com/community/tutorials/how-to-set-up-password-authentication-with-apache-on-ubuntu-16-04)
* [Caddy](https://caddyserver.com/docs/caddyfile/directives/basicauth)

## 远程桌面安全提示 <a href="#yuan-cheng-zhuo-mian-an-quan-ti-shi" id="yuan-cheng-zhuo-mian-an-quan-ti-shi"></a>

映射远程桌面通常会带来出人意料的风险，因为巨硬的漏洞总是很多

如果您需要映射远程桌面，我们强烈建议您启用 Windows Update 来避免批量 0day 利用使得您的电脑遭到攻击，出现 Wanna-cry 的悲剧

**系统更新是您的朋友，不是敌人。** 如果说有一个东西总是能在暴露的风险中拯救您，那一定是阻断药……啊不，系统更新。

系统更新可能会迟到，但是只要到达，它总是能为守护您的电脑奉上您需要的力量。

如果您因为一些理由关闭了系统更新，请不要以任何形式把自己暴露在网络中。to the concepts that matter most to them.
