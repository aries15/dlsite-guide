# DLsite使用指南

1. 个人经验
2. 未成年人不建议浏览

## 访问

曾经只有dns污染，能用hosts解决。从2021年2月左右开始升级为SNI RST，~~hosts无效不用试了~~；幸好IP没被封。不知从什么时候开始，又只有dns污染了，那hosts就可用了。

DL官方提供了一个加速器：https://dlbooster.com/

我个人用 <https://github.com/macronut/ghostcp>。免费，且是直连，如果运气好CDN没问题，下载速度会非常快。**实测香港的CloudFront非常好**，而台湾的直连就不太行。

下载Release，解压，修改`default.conf`为以下内容：

```
ecs=111.0.0.0
method=w-md5
server=8.8.8.8:53
dlsite.com
.dlsite.com
img.dlsite.jp
```

再运行start_service.bat或者install_service.bat即可。

当然，普通梯子也是可以的。

## 使用

首先推荐看WH“WH黑企鹅”大佬的文章：

* [超详细图解DLsite基本使用方法](https://www.weibo.com/ttarticle/p/show?id=2309404304814015141577)
* [DLsite进阶版使用教程](https://www.weibo.com/ttarticle/p/show?id=2309404265719100494880)
* [DLsite常见问题汇总](https://krpengin.wordpress.com/2020/05/16/dlsitefaq/)

网站界面有一些中文，但有时仍需借助翻译，推荐Chrome系浏览器。

一般游戏最多-50%，但我也见过-90%的。经常有再-15%或-18%的优惠券，漫画有-20%的；不过有时要满2000日元才能用，有时要至少买两项才能用。我只会在打大折且有优惠券时才买，即便如此还是很贵。

账号-购买点数 <del>有支持支付宝的“魔法集市”。最低额度1000日元，汇率比百度出来的高一点，人工客服是存在的，某些节日会做活动加量10%</del>。购买、复制兑换码后去“输入兑换码”。点数有效期一年；只要使用或者获得，有效期就会刷新。另外淘宝有一些代充服务，价格比魔法集市低一点，当然理论上安全性就差一点，反正我不用。

<ins>2024年，魔法集市破产了。我的损失可以忽略，也就一点可以抵扣钱的点数，而有的人购买了实物，钱财两空了。</ins>这算是给大家敲了警钟。可能平常习以为常的东西，并不那么理所当然。而且现在暂时不直接支持Visa了；不过DLPay的Paypal还是能用Visa的。如果参加工作了，可以考虑申请工商银行星座Visa信用卡，它是免年费的，价格比支付宝充值便宜一点点。

账号-我的评价(short-review) 可以打星，购买后90天内打星会返还10%的点数。但用了优惠券一般就没有返点；且这个10%是用非点数支付的10%，若全用点数购买就没有返点。

“评论”是需要审核的，曾经只能用日文，现在也允许中文了，完成后额外获得至多100点，一般就50点。

~~个人主页首页左侧栏下面有个农场游戏，每天一次有几率得点数（基本都是得1点）；是ajax。~~

部分游戏需要转区（尤其是WolfMaker的），解压可用360压缩的“压缩包语言”功能，运行可用Locale Emulator，路径一定要是纯英文。有的游戏不能自由调整大小，可用ResizeEnableRunner。

中文游戏列表：https://ch.dlsite.com/matome/155241

汉化工具：https://trs.mtool.app/release.php 支持各种RPG和VisualNovel游戏的翻译+修改，可能稍微有一点使用门槛，推荐去B站看教程视频。

## Steam

一小部分游戏上了Steam。一般来说Steam上的原价就等于DLsite上-50%了（但也有例外的），而且Steam还能再打折，还能靠SteamDB查看历史最低价。因此我个人优先在Steam上买。

虽然DLsite是Steam的发行商，但发行了的游戏却少得可怜。偶有作者自己发行的。有的游戏还锁区。

主要还是靠以下几个发行商，且基本还会汉化：

* <https://store.steampowered.com/publisher/Kagura>
* <https://store.steampowered.com/publisher/otakuplan>
* <https://store.steampowered.com/publisher/Saikey>
* <https://store.steampowered.com/publisher/BOKI/>
* <https://store.steampowered.com/publisher/072Project> 大量游戏锁区，在SteamDB可以看到
* ~~<https://store.steampowered.com/publisher/wasabiE>~~ 全锁区了……
* ~~<https://store.steampowered.com/search/?publisher=Paradise%20Project>~~ 原有的游戏都下架了
* <https://steamgalgame.com/> 收集了一些汉化补丁

## 关于“爱心分享”网站

互联网和软件的性质决定了盗版的传播是无可避免的。

先玩盗版，再给喜欢的作品补票，（个人认为）已经是这个圈子道德最高的一层了。不会真的有人盲买吧。\
如果有经济能力，确实是喜欢的作品，又打折，且有合适的购买渠道（比如dmm就不对其他国家开放，想买都买不了），那买补票正版是一件很自然的事。\
但是曾经很多游戏没有汉化，不得不先找盗版资源。

资源站可能面临的问题：

1. 没有收录想要的游戏。
2. 链接过期了。其中“飞猫云”网盘，链接发布后一段时间内可以免费下，再之后就必须开会员才能下。
3. 网站倒闭了。
4. 网速慢。

许多搜出来的资源站要求开通会员；网盘也要开会员，否则限速可能只有几十KB/s。\
一般来说，互联网的鄙视链是：正版 > 免费盗版 > 收费盗版。\
但客观来说，如果想要的资源刚好那个网站有，又不想再费时间了，充个便宜的也算正常，毕竟时间就是金钱。

我只能提醒：**不要忽略网站倒闭的可能**。以及倒闭后，贴吧里某些恶意评论发的*回家*链接，往往是**交钱后就拉黑了**，能骗一个是一个。

## RPG Maker的*声音*

* BGM 背景音乐
* BGS 背景音效，如恐怖地方的风声
* BGV 喘气声
* ME 在它播放的时候，一切BGM和BGS都要停止，等它播放完毕之后再继续淡入播放。如战斗胜利
* SE 上下选择菜单时的音效，技能音效。有的游戏包括人物语音
