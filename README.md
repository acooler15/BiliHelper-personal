<p align="center"><img width="300px" src="https://i.loli.net/2018/04/20/5ad97bd395912.jpeg"></p>

<div align="center"> 

[![](https://img.shields.io/badge/Author-Lkeme-blueviolet "作者")](https://github.com/lkeme/ )
![](https://img.shields.io/badge/dynamic/json?label=GitHub%20Followers&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dgithub%26queryKey%3Dlkeme&labelColor=282c34&color=181717&logo=github&longCache=true "关注数量")
![](https://img.shields.io/github/stars/lkeme/BiliHelper-personal.svg?style=plastic&logo=appveyor "Star数量")
![](https://img.shields.io/github/forks/lkeme/BiliHelper-personal.svg?style=plastic&logo=stackshare "Fork数量")
![](https://img.shields.io/github/contributors/lkeme/BiliHelper-personal "贡献者")

</div>

<p align="center">

<img src="https://img.shields.io/badge/Version-0.9.0.210517-orange.svg?longCache=true&style=for-the-badge">
<img src="https://img.shields.io/badge/PHP-7.3+-green.svg?longCache=true&style=for-the-badge">
<img src="https://img.shields.io/badge/Composer-latest-blueviolet.svg?longCache=true&style=for-the-badge">
<img src="https://img.shields.io/badge/License-mit-blue.svg?longCache=true&style=for-the-badge">

</p>

## 公告通知

```notice
---- 免费的东西总是得不到人的珍惜。
---- 只有花大价钱去买到的东西，才会令人信任。
```

## 功能组件

> 以下任务都是按设定周期自动执行，`true`为正常使用，`false`为暂停使用或抛弃。

| plugin          | status | version  | description                                 |
|-----------------|--------|----------|---------------------------------------------|
| CheckUpdate     | true   | 21.05.17 | 程序检查更新                                |
| Login           | true   | 21.05.17 | 账号登录、刷新、维持                        |
| Schedule        | true   | 21.05.17 | 控制插件运行周期                            |
| MainSite        | true   | 21.05.17 | 投币、观看、分享视频 (速升6级不是梦)        |
| DailyBag        | true   | 21.05.17 | 双端领取日常/周常礼包                       |
| ManGa           | true   | 21.05.17 | 漫画签到、分享                              |
| ActivityLottery | true   | 21.05.17 | 主站活动九宫格抽奖                          |
| Competition     | true   | 21.05.17 | 游戏赛事竞猜                                |
| DoubleHeart     | true   | 21.05.17 | 双端心跳 (姥爷直播经验)                     |
| DailyTask       | true   | 21.05.17 | 直播每日任务(签到、观看)                    |
| Barrage         | true   | 21.05.17 | 保持活跃弹幕                                |
| Silver2Coin     | true   | 21.05.17 | 银瓜子兑换硬币                              |
| Judge           | true   | 21.05.17 | 风纪委员投票                                |
| GiftSend        | true   | 21.05.17 | 礼物赠送、维持每日勋章亲密度                |
| GroupSignIn     | true   | 21.05.17 | 友爱社签到                                  |
| GiftHeart       | true   | 21.05.17 | 日常心跳每日礼包礼物                        |
| SmallHeart      | true   | 21.05.17 | 直播挂机，每日24个小心心                    |
| MaterialObject  | true   | 21.05.17 | 直播金色宝箱实物抽奖                        |
| AloneTcpClient  | true   | 21.05.17 | 作者的独立直播监控                          |
| ZoneTcpClient   | true   | 21.05.17 | 官方的分区直播监控                          |
| StormRaffle     | true   | 21.05.17 | 直播节奏风暴抽奖、亿元                      |
| GiftRaffle      | true   | 21.05.17 | 直播礼物抽奖                                |
| PkRaffle        | true   | 21.05.17 | 直播大乱斗抽奖                              |
| GuardRaffle     | true   | 21.05.17 | 直播大航海抽奖                              |
| AnchorRaffle    | true   | 21.05.17 | 直播天选时刻抽奖                            |
| GiftRaffle      | true   | 21.05.17 | 直播礼物抽奖                                |
| AwardRecord     | true   | 21.05.17 | 最新的中奖纪录通知                          |
| Forward         | true   | 21.05.17 | 主站动态抽奖转发                            |
| CapsuleLottery  | true   | 21.05.17 | 直播扭蛋活动抽奖                            |
| PolishTheMedal  | true   | 21.05.17 | 每日自动点亮灰色勋章                        |
| CapsuleLottery  | true   | 21.05.17 | 直播扭蛋活动抽奖                            |
| VipPrivilege    | true   | 21.05.17 | 每月领取年度大会员特权(B币券、会员购优惠券) |
| BpConsumption   | true   | 21.05.17 | 每月消费使用年度大会员特权的B币券           |
| Statistics      | true   | 21.05.17 | 全局抽奖结果统计                            |
| Silver          | false  | 21.03.27 | 直播银瓜子自动开启宝箱                      |

## 交流反馈

> Group: [55308141](https://jq.qq.com/?_wv=1027&k=5AIDaJg) | **请不要来问如何使用， 文档齐全， 仅用于BUG提交反馈**

## 相关文档

> 有疑问一定要先看看文档或Issue里是否存在相同的问题，再考虑其他渠道咨询。

* [使用文档 / DOC.md](./DOC.md)
* [更新日志 / CHANGELOG.md](./CHANGELOG.md)
* [配置文档 / WIKI.md](https://github.com/lkeme/BiliHelper-personal/wiki/%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6%E8%AF%A6%E8%A7%A3)
* [常见问题 / WIKI.md](https://github.com/lkeme/BiliHelper-personal/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

## 打赏支持

> 如果觉得本项目好用，对你有所帮助，欢迎打赏支持。

![](https://i.loli.net/2019/07/13/5d2963e5cc1eb22973.png)

## 运行效果

> 不代表当前版本，以当前最新版本运行结果为准

![](https://i.loli.net/2019/07/13/5d296961a4bae41364.png)

## 项目相关

* [BilibiliHelper](https://github.com/metowolf/BilibiliHelper)
* [BiliHelper](https://github.com/lkeme/BiliHelper)
* [Github](https://github.com/)

## License 许可证

BiliHelper is under the MIT license.

本项目基于 MIT 协议发布，并增加了 SATA 协议。

当你使用了使用 SATA 的开源软件或文档的时候，在遵守基础许可证的前提下，你必须马不停蹄地给你所使用的开源项目 “点赞” ，比如在 GitHub 上
star，然后你必须感谢这个帮助了你的开源项目的作者，作者信息可以在许可证头部的版权声明部分找到。

本项目的所有代码文件、配置项，除另有说明外，均基于上述介绍的协议发布，具体请看分支下的 LICENSE。

此处的文字仅用于说明，条款以 LICENSE 文件中的内容为准。
