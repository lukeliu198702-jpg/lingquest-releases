# 灵兽奇语 · 安卓安装包

这里发布灵兽奇语 Android 客户端安装包、版本说明和更新清单。应用源码保留在私有仓库。

## 下载与安装

- [下载最新 APK](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest/download/LingQuest-latest.apk)
- [最新版本说明](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest)
- [更新清单](https://github.com/lukeliu198702-jpg/lingquest-releases/releases/latest/download/update.json)

用安卓平板或手机浏览器打开下载链接，下载后打开 APK，按系统提示允许该来源安装并确认。支持 Android 8.0 及以上；已安装同签名旧版时直接覆盖安装，保留本机档案，请勿先卸载。

0.7.0 起在“设置 → 检查更新”中自动读取本仓库最新版本，无需配置地址。0.6.0 及更早版本首次需下载安装新版 APK；后续从应用内检查更新。设备需能访问 GitHub。

## 当前版本 0.7.0

- “神兽”页可更换神兽和改名，保留成长值、积分、背包和学习进度。
- 绘本书内全部英文，修复长标题与插图越界，适配平板和手机。
- 内置 GitHub 更新渠道，保留离线 Emma 英音、绘本解谜、探险、复习和商城。

这是内部测试版。99 项安卓测试、39 项内容与发布检查通过；仍需在目标平板验证真实显示、音频与覆盖安装。

APK SHA256：`50e36a6f48cd4853abedd3cb4fa80bae5198a401b1496c743b61302b879659dc`。

## 更新约定

每次 Release 同时包含不可变版本 APK、相同字节的 `LingQuest-latest.apk`、`update.json` 与 `SHA256SUMS.txt`。清单指向具体版本的 APK，客户端验证字节数、SHA256、包名、版本和签名后交给系统确认安装。学习和神兽档案保存在本机。
