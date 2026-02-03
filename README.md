# unsigned-ipa-cn
**常用iOS应用(砸壳)收集**

**Release内容不定期更新**

*本仓库只是针对个人在用的App进行收录, 更多国际化的应用和tweaks可以看[swaggyP36000/TrollStore-IPAs](https://github.com/swaggyP36000/TrollStore-IPAs)这个仓库*


**iOS侧载玩法：** https://taosky.org/story/ios-sideload/

**微信双开教程（自签）：** https://taosky.org/story/ios-dual-wechat/


### 安装方式

1.TrollStore：应该不用特别说明，安装各种应用几乎都没有限制


2.自签（非开发者账户）：便捷方法可以看下[SideStore](https://sidestore.io/)，配置好之后，手机上（通过互联网）即可完成自签和签名刷新。配合 [LiveContainer](https://github.com/khanhduytran0/LiveContainer) 无限制“加载”使用App (可灵活注入插件)


3.证书签名：需要花钱买证书，自行研究，使用feather或轻松签导入使用


### 微信

##### 砸壳、注入净化版本

TrollStore、证书签名可正常推送，自签无法推送

下载地址: [releases/tag/wechat](https://github.com/Taosky/trollstore-ipa-cn/releases/tag/wechat)

##### 普通多开版本

免费自签多开教程: https://taosky.org/story/ios-dual-wechat/

下载地址: [releases/tag/fchat](https://github.com/Taosky/trollstore-ipa-cn/releases/tag/fchat)

##### 无后台推送版本（8.0.66）

TrollStore、证书签名可用，自签会改变BundleID因此不可用（不能推送）

下载地址：[releases/tag/wechat_qy](https://github.com/Taosky/trollstore-ipa-cn/releases/tag/wechat_qy)


### 酷安（去广告）

TrollStore / 证书签名 / LiveContainer 可用，非开发者自签会改变BundleID导致验证失败

下载地址: [releases/tag/coolapk](https://github.com/Taosky/unsigned-ipa-cn/releases/tag/coolapk)


### 豆瓣（去广告）

TrollStore / 证书签名 / LiveContainer 可用，自签会改变BundleID导致验证失败

下载地址: [releases/tag/douban](https://github.com/Taosky/unsigned-ipa-cn/releases/tag/douban)


### 抖音（新增解除登陆限制插件）
下载地址: [releases/tag/aweme](https://github.com/Taosky/unsigned-ipa-cn/releases/tag/aweme)

### Infuse（Pro）

下载地址: [releases/tag/infuse](https://github.com/Taosky/unsigned-ipa-cn/releases/tag/infuse)


### Spotify （EveeSpotify）

如果需要灵动岛点击和Siri正常使用，要自行配置Signtools签名，参见这个[issue](https://github.com/whoeevee/EeveeSpotify/issues/32#issuecomment-2080750016)

https://github.com/whoeevee/EeveeSpotify


### SimplyPiano
钢琴学习（使用中需要注册登陆论坛的账号才能解锁）

下载地址: [releases/tag/simplypiano](https://github.com/Taosky/unsigned-ipa-cn/releases/tag/simplypiano)


### Simple Live
简简单单的看直播

https://github.com/xiaoyaocz/dart_simple_live/releases/


### PiliPala
使用 Flutter 开发的 BiliBili 第三方客户端

https://github.com/guozhigq/pilipala/releases
