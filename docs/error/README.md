---
description: 这里我们只看您出错的最后一行
---

# 常见错误

## 节点过载 <a href="#jie-dian-guo-zai" id="jie-dian-guo-zai"></a>

### i/o deadline reached <a href="#io-deadline-reached" id="io-deadline-reached"></a>

很可能您使用的节点已过载，建议去[状态检测](https://openfrpstatus.zyghit.cn/)页面查询，并更换节点

## 在国内使用HTTP(S)隧道 <a href="#zai-guo-nei-shi-yong-https-sui-dao" id="zai-guo-nei-shi-yong-https-sui-dao"></a>

如果出现下图的情况，这表明您可能使用了国内节点穿透了HTTP(S)隧道，将隧道换为海外节点即可

![](../../.gitbook/assets/https\_china.png)

## 服务未开启 <a href="#fu-wu-wei-kai-qi" id="fu-wu-wei-kai-qi"></a>

如果您出现下图的错误

![](../../.gitbook/assets/no\_target.png)

则表明您的本地服务未开启/没有程序正在监听此端口/连接到本地服务时被拒绝

尝试重新开启需要穿透的服务

您可以参考下图来逐一排查原因

![](../../.gitbook/assets/no\_target\_error\_resolve.png)

## 其他错误 <a href="#qi-ta-cuo-wu" id="qi-ta-cuo-wu"></a>

参考下图

![any\_error\_resolve\_method\_img](https://docs.openfrp.net/docs/assests/some\_error\_resolve\_method.png)
