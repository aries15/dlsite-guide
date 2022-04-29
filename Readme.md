# DLsite使用指南

原本是写在知乎上的，曾经被人举报删了一次回答，现在居然整个问题都被举报没了。

## 访问

曾经只有dns污染，能用hosts解决。从2021年2月左右开始升级为SNI RST，hosts无效不用试了；幸好IP没被封。

我推荐用 <https://github.com/macronut/ghostcp>。免费，且是直连，如果运气好CDN没问题，下载速度会非常快。

下载Release，解压，修改`default.conf`为以下内容：

```
ecs=111.0.0.0
method=w-md5
server=8.8.8.8:53
dlsite.com
.dlsite.com
img.dlsite.jp
```

再运行start_service.bat或者install_service.bat即可。另外如果你之前用过Hosts，要把相关条目删了，否则这软件就无法生效。

当然，普通梯子也是可以的。

## 使用

首先推荐看WH“WH黑企鹅”大佬的文章：

* [超详细图解DLsite基本使用方法](https://www.weibo.com/ttarticle/p/show?id=2309404304814015141577)
* [DLsite进阶版使用教程](https://www.weibo.com/ttarticle/p/show?id=2309404265719100494880)
* [DLsite常见问题汇总](https://krpengin.wordpress.com/2020/05/16/dlsitefaq/)

网站界面有一些中文，但有时仍需借助翻译，推荐Chrome系浏览器。

一般游戏最多-50%，但我也见过-90%的。经常有再-15%或-18%的优惠券，漫画有-20%的；不过有时要满2000日元才能用，有时要至少买两项才能用。我只会在打大折且有优惠券时才买，即便如此还是很贵。

账号-购买点数 有支持支付宝的“魔法集市”。最低额度1000日元，汇率比百度出来的高一点，人工客服是存在的，双11做过活动。购买、复制兑换码后去“输入兑换码”。点数有效期一年；只要使用或者获得，有效期就会刷新。另外淘宝有一些代充服务，价格比魔法集市低一点，当然理论上安全性就差一点，反正我不用。

账号-我的评价(short-review) 可以打星，购买后90天内打星会返还10%的点数。但用了优惠券一般就没有返点；且这个10%是用非点数支付的10%，若全用点数购买就没有返点。

“评论”是需要审核的，曾经只能用日文，现在也允许中文了，完成后额外获得至多100点，一般就50点。

个人主页首页左侧栏下面有个农场游戏，每天一次有几率得点数（基本都是得1点）；是ajax。

部分游戏需要转区（尤其是WolfMaker的），解压可用360压缩的“压缩包语言”功能，运行可用Locale Emulator。有的游戏不能自由调整大小，可用ResizeEnableRunner。

英文站和台湾站没有研究过，只知道数据不通用。

中文游戏列表：https://ch.dlsite.com/matome/155241

## Steam

一小部分游戏上了Steam。一般来说Steam上的原价就等于DLsite上-50%了（但也有例外的），而且Steam还能再打折，还能靠SteamDB查看历史最低价。因此我个人优先在Steam上买。

虽然DLsite是Steam的发行商，但发行了的游戏却少得可怜。偶有作者自己发行的。有的游戏还锁区。

主要还是靠以下几个发行商，且基本还会汉化：

* <https://store.steampowered.com/publisher/Kagura>
* <https://store.steampowered.com/publisher/otakuplan>
* ~~<https://store.steampowered.com/publisher/wasabiE>~~ 全锁区了……
* ~~<https://store.steampowered.com/search/?publisher=Paradise%20Project>~~ 原有的游戏都下架了
