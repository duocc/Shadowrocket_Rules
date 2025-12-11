## iOS Shadowrocket规则



这里是一系列好用的Shadowrocket规则，针对 [Shadowrocket](https://liguangming.com/Shadowrocket) 开发，支持广告过滤。规则定义了哪些网站可以直连，哪些必须走代理，规则是一个纯文本文件，无法提供魔法上网功能。使用 Python 按照一定的规则和模板定期自动生成，并且使用开源的力量，集众人之力逐渐完善。


**本规则具有以下特点：**

- 黑名单由最新版 [GFWList](https://github.com/gfwlist/gfwlist) 自动转换；
- 加入 [Greatfire Analyzer](https://github.com/Loyalsoldier/cn-blocked-domain) 检测到的屏蔽域名；
- 自动转换最新版本的 `EasyList`, `Eaylist China`, `Peter Lowe 广告和隐私跟踪域名`，`乘风规则` 为 SR 规则，全面去除广告且去除重复；
- 包括自定义的广告过滤规则，针对 iOS 端的网页广告、App 广告和视频广告；
- 提供多个规则文件供大家自由选择或者自由切换使用；
- 专门针对 ShadowRocket 开发，可以保证与 SR 的兼容性；

## 鸣谢

- 感谢 [@h2y](https://github.com/h2y) 及所有给予 [Shadowrocket-ADBlock-Rules](https://github.com/h2y/Shadowrocket-ADBlock-Rules) 无私帮助的社区开发者们；
- 感谢懒人规则的建立和维护者们；
- 感谢 [@hfdem](https://github.com/hfdem) 给予我的帮助、肯定与支持！  

### 本项目引用
- [gfwlist](https://github.com/gfwlist/gfwlist)  
- [Greatfire Analyzer](https://github.com/Loyalsoldier/cn-blocked-domain)
- [乘风广告过滤规则](https://github.com/xinggsf/Adblock-Plus-Rule)
- [EasyList China](https://adblockplus.org/)
- [Peter Lowe 广告和隐私跟踪域名](https://pgl.yoyo.org/)
- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
- [LOWERTOP/Shadowrocket](https://github.com/LOWERTOP/Shadowrocket)

