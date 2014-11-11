Privoxy
=======

Privoxy 配置文件


这是一份我自己使用的 Privoxy 配置文件库，包括以下文件：

1. config - 配置文件
2. user.action 
3. user.filter
4. easy* 系列文件

其中 easy* 列表根据[脚本](http://andrwe.org/scripting/bash/privoxy-blocklist)自动生成，[具体列表](https://easylist.adblockplus.org/en/)请根据自己情况补充或删减，user.action 与 user.filter 用于个人定制一些规则。

## openSUSE 下用法

将 README.md 以外的文件下载拷贝到 _/etc/privoxy/_ 或 _/var/lib/privoxy/etc/_ 目录下即可。

## 关于规则的说明

规则是很隐私的东西，譬如我过滤有道词典的广告，就说明我经常用有道词典（百度是特例，纯拿来练手去广告），于是推送到 Github 的行为，就像是暴露狂所为。这也是 AdblockPlus 这类工具的好处，通用，不暴露个人隐私，但因此它也就有了缺点，一是规则太多，每访问一个网址，都要过一遍所有规则，可能影响速度，另外，个人用的网站，它不可能都照顾到。这也是我最终决定放弃 Adblock 类的工具，转用 Privoxy 的原因之一。
