# 灵兽奇语 · 安卓安装包

这里发布灵兽奇语 Android 客户端安装包、版本说明和更新清单。应用源码保留在私有仓库。

## 下载与安装

- [下载最新 APK](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest/download/LingQuest-latest.apk)
- [最新版本说明](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest)
- [更新清单](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest/download/update.json)

用安卓平板或手机浏览器打开下载链接，下载后打开 APK，按系统提示允许该来源安装并确认。支持 Android 8.0 及以上；已安装同签名旧版时直接覆盖安装，保留本机档案，请勿先卸载。

0.7.0 起在“设置 → 检查更新”中自动读取本仓库最新版本，无需配置地址。0.6.0 及更早版本首次需下载安装新版 APK；之后从应用内检查更新。设备需能访问 GitHub。

## 0.8.0 新增神兽互动

- 在首页或“神兽”页点击神兽，摸摸头，喂食或聊聊天。
- 喂食消耗背包中的一份甜苹果；没有食物时可在同页用积分兑换。
- 心情、食物、探险三组选择式英文情景对话，支持连续回应、中文帮助、回看和朗读。
- 15 段新 Emma 离线语音；摸头和对话不增加积分或成长值。
- 保留神兽更换、全英文绘本、探险、复习、商城与原存档。

这是内部测试版和选择式对话，暂不支持自由输入聊天或语音识别。106 项安卓测试、42 项内容和媒体检查通过；真实平板显示、音频和覆盖更新仍需实机确认。

0.8.0 APK SHA256：`3bed824005fc463e55b1af4bfaa7b712a9a56eec9482a13f5c4e8ff87cf9f7cc`。

## 更新约定

每次 Release 同时包含不可变版本 APK、相同字节的 `LingQuest-latest.apk`、`update.json` 与 `SHA256SUMS.txt`。清单指向具体版本的 APK，客户端验证字节数、SHA256、包名、版本和签名后交给系统确认安装。学习和神兽档案保存在本机。
