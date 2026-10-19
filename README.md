# 灵兽奇语 · 安卓安装包

这里发布灵兽奇语 Android 客户端安装包、版本说明和更新清单。应用源码保留在私有仓库。

## 下载与安装

- [下载最新 APK](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest/download/LingQuest-latest.apk)
- [最新版本说明](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest)
- [更新清单](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest/download/update.json)

用安卓平板或手机浏览器打开下载链接，下载后打开 APK，按系统提示允许该来源安装并确认。支持 Android 8.0 及以上；已安装同签名旧版时直接覆盖安装，保留本机档案，请勿先卸载。

0.7.0 起在“设置 → 检查更新”中自动读取本仓库最新版本，无需配置地址。0.6.0 及更早版本首次需下载安装新版 APK；之后从应用内检查更新。设备需能访问 GitHub。

## 0.9.0 英文小屋与新绘本

- Guardian Shop / My Bag 全英文，分 Furniture、Food、Equipment，共 16 种商品。
- “神兽”→“进入小屋 · 用英语摆家具”：英语语音为主，核对识别句子后确认摆放，输入与拼词备用。
- 可以说 Put the table in the middle.、Put the chair next to the table.，也可移动、放到桌上/桌下、放窗边或移除家具。
- 英语识别模型随包内置，离线使用；第一次需允许麦克风并等待模型准备。原始录音不保存或上传。
- 四种食物真实消耗库存，五件装备可穿戴/取下；保留点击神兽摸头、喂食和选择式英文对话。
- 新增 The Little Prince: A Reading Companion：六页全英文独立导读、六张原创插画、Emma 朗读与四道谜题，制作 Friendship Card。
- 新书首次交付奖励 30 积分 / 20 成长值，重读不重复领奖；原有神兽、积分、库存和学习进度保留。

这是内部测试版。《小王子》当前为简短导读和独立阅读活动，不是完整原著或译本。语音仅用于小屋家具指令，聊天仍为选择式。121 项安卓测试、48 项内容检查通过；六条合成录音通过开发机实际模型识别，真实 MatePad 麦克风、孩子发音与安装仍需实机确认。

0.9.0 APK 约 147 MB，SHA256：`2f67a05067b191033364ad9e7533757d5d9c4abea60f0751c9296d8c9ad929da`。

## 更新约定

0.9.0 起每次 Release 包含 `LingQuest-latest.apk`、`update.json` 与 `SHA256SUMS.txt`，同一 APK 提供最新下载和固定版本下载，无需重复上传。清单指向具体版本的 APK，客户端验证字节数、SHA256、包名、版本和签名后交给系统确认安装。学习和神兽档案保存在本机。
