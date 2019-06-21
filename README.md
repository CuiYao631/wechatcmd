# wechatcmd  [![star this repo](http://github-svg-buttons.herokuapp.com/star.svg?user=hawklithm&repo=wechatcmd&style=flat&background=1081C1)](http://github.com/hawklithm/wechatcmd) [![fork this repo](http://github-svg-buttons.herokuapp.com/fork.svg?user=hawklithm&repo=wechatcmd&style=flat&background=1081C1)](http://github.com/hawklithm/wechatcmd/fork) ![Build](https://camo.githubusercontent.com/46cb8b3469febc6cdb6fbaea2ef1517c396004e7/68747470733a2f2f7472617669732d63692e6f72672f736a77686974776f7274682f676f6c6561726e2e706e673f6272616e63683d6d6173746572)

<span style="color:red;">项目整体架构过于混乱，开始重构，重构项目见 [hawklithm/anychatcmd](https://github.com/hawklithm/anychatcmd) ，目标是不仅支持微信，欢迎交流</span> 


----------------------------------

公司出于安全性考虑不允许安装pc版wechat，网页版在使用上并不令人满意，在一番调研之后决定采用 
[liushuchun/wechatcmd](https://github.com/liushuchun/wechatcmd)
，在阅读了源码并了解到原作者已放弃继续开发，遂决定fork一份之后在此基础上继续进行开发，完善其功能

*本代码主要在MAC OS上进行开发测试，针对linux系统的兼容主要基于ubuntu进行考虑的，如果在实际使用中存在什么问题欢迎提出，暂不考虑windows*

目前已完善点：

- [x] termui版本升级到3.0.0，接口兼容问题修复
- [x] 群聊天中发言人显示
- [x] 用户多端登陆时，通过其他端发出的消息的同步
- [x] 切换当前聊天窗口时，历史聊天记录的恢复
- [x] 干掉了红包提醒(逻辑存在bug，误提醒，让人很烦躁，所以删掉了)

**注：本程序目的为日常使用替代pc端微信，所以不会开发自动回复或者聊天机器人抑或是群发之类的功能**


操作方式：

| 按键 | 说明 |
| --- | --- |
| Ctrl+n | 下一个聊天 |
| Ctrl+p | 上一个聊天 |
| Ctrl+j | 下一条聊天记录 |
| Ctrl+k | 上一条聊天记录 |
| Ctrl+w | 展示选中的聊天信息的详情；如果是图片则打开图片，如果是外链则打开外链 |
| Ctrl+c | 退出 |
| Ctrl+a | 开启/关闭消息提醒 |

开发计划：

- [x] 实现微信登陆(原版已实现)
- [x] 实现微信认证(原版已实现)
- [x] 实现拉取用户信息(原版已实现)
- [x] 同步消息
- [x] 自动更新消息
- [x] 聊天
- [x] 群聊
- [x] 支持图片显示
- [x] 支持emoji表情
- [x] 解析分享消息
- [x] 解析公众号消息
- [x] 支持表情包
- [x] 消息提醒
- [ ] 界面优化(用户列表和当前会话分拆，支持群成员展示)

由于整体框架的原因，以下特性计划在代码重构之后再完成了:

- [ ] 本地表情包发送(发图片)
- [ ] 自动保存消息到本地
- [ ] vim式操作

代码重构后计划增加的特性:

- [ ] 支持即刻网页版账号登陆(因为本人喜欢刷即刻)
- [ ] 支持Boss直聘网页版及一些自动化功能(纯工作需要.....)

