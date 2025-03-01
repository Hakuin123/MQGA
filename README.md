# MAKE QQ GREAT AGAIN!

## 这个项目是做什么的

~~**“让QQ再次伟大！”**~~

本项目使用 [LSPatch](https://github.com/LSPosed/LSPatch) 和 [GitHub Action](https://github.com/features/actions) 自动化修补 QQ Android，并在其中嵌入以下 Xposed/LSPosed 模块：

- [QAuxiliary](https://github.com/cinit/QAuxiliary)
- [XAutoDaily](https://github.com/LuckyPray/XAutoDaily)
- [TSBattery](https://github.com/fankes/TSBattery)
- [QQ瘦身（QQCleaner）](https://github.com/KitsunePie/QQCleaner)

（如果发现有更多好玩好用的模块，欢迎[提交 Issue 推荐给我们](https://github.com/Hakuin123/MQGA/issues/new)。）

## 获取方式

> [!CAUTION]
> 近期 QQ 官方加大了对模块 Hook 检测的力度，使用模块可能导致您的账号被**异常下线**、**限制社交功能**乃至**一定程度的封禁**，请**自行**判断您是否要使用模块。

### 下载经过修补的 QQ Android 最新版 / 8.9.58
请在 [Releases](https://github.com/Hakuin123/MQGA/releases) 下载已修补完成的最新版或 8.9.58 版本QQ。最新Release 构建状态：![状态：default](https://github.com/Hakuin123/MQGA/actions/workflows/default.yml/badge.svg) 

> [!TIP]
> 想要在每次修补完成时获得通知？
> 1. [登录 GitHub 账户](https://github.com/signin)
> 2. 在本项目项目页面上方找到`Watch`（眼睛图标）并点击
> 3. 选择`Custom`
> 4. 勾选`Releases`并点击`Apply`以应用
> 完成！接下来每当有新的 [Release](https://github.com/Hakuin123/MQGA/releases) 发布时，您将收到来自 GitHub 的提醒！该方法适用于任意 GitHub 项目

### 修补自定义 QQ Android 版本（单次）
<details><summary>点击这里展开教程</summary>
<p>

1. [登录 GitHub 账户](https://github.com/signin)，然后 [Fork](https://github.com/Hakuin123/MQGA/fork) 此仓库
2. 在**你自己 fork 完成的仓库**（带有你自己的用户名）页面顶部点击`Actions`
3. （点开`All workflows`后）点击`Custom`
4. 点击蓝色`#DDF4FF`横幅`This workflow has a workflow_dispatch event trigger.`右边的`Run workflow`
5. 在弹出的窗口内填写下列内容：
  - **自定义版本号**  输入你所自定义的 QQ Android 版本（仅作名称标识作用，是否正确填写对于实际修补无影响）
  - **指定下载链接**  输入 QQ/TIM Android 安装包直链
  - **模块版本通道**  选择使用正式版（default）还是测试版（CI）的模块
6. 填写完成后点击绿色`#1F883D`的`Run workflow`并刷新页面，等待新增的工作流`Custom`的图标由黄色`#DBAB0A`变为绿色`#1F883D`，点开这个~~刚冒出来的花里胡哨变色的~~`Custom`
7. 在`Artifacts`找到修补完成的`.apk`文件，点击以下载（未登录状态下无法下载）

> 若Actions执行失败（状态为红色`#D1242F`），请自行检查输入的安装包链接是否为直链，也就是说输入的链接在浏览器打开后能够自动下载安装包。可百度或在QQ官网自行获取直链。

</p>
</details>

> 免责声明：本项目仅提供服务整合，QQ 安装包及模块均由第三方提供，如在使用中出现问题，本项目不对此负任何责任。使用/下载本项目或本项目提供的资源即表示同意上述声明。


## 计划实现的功能

- [x] 借助 GitHub Actions 修补QQ #1
- [x] 修补时自动下载最新版本 QQ（使用固定连接） #2
- [x] ~~当 QQ / 模块更新时自动重新修补~~ 固定每周检查更新并重新修补


## 推荐的 QQ Android 版本

> 以下版本无论是否使用模块均可获得相对较好的体验，欢迎尝试

### [QQ NT（当前最新版）](https://im.qq.com/index/#downloadAnchor)
最新版 QQ 基于 [Election](https://www.electronjs.org/zh/) 重构，同时更改了聊天消息存储结构，性能得到大幅提升，若未尝试过 8.9.63 及以上版本则极力推荐尝试

### [QQ 8.9.58.11175](https://downv6.qq.com/qqweb/QQ_1/android_apk/Android_8.9.58_64_HB2.apk)
最后一个**不**基于 QQ_NT 的版本

### [QQ 8.8.50.10650](https://downv6.qq.com/qqweb/QQ_1/android_apk/Android_8.9.50.10650_537155547_64.apk)
最后一个不是 3A 大作（未内置虚幻引擎 4，无超级 QQ 秀）的版本

### [TIM NT（当前最新版）](https://office.qq.com/download.html)
极为简洁的 QQ 官方修改版，4.0.0 后底包基于 QQ 9.0.95（QQ NT 版本）

### [TIM 3.4.8](https://downv6.qq.com/qqweb/QQ_1/android_apk/tim_3.4.8.3108_537129495_64.apk)
（相对没那么推荐）底包基于 QQ 8.3.9 ，邮箱入口不会被云控移除，日历功能也保留（但有反馈说无法登录）

## 更好地食用

配合 GitHub 镜像站/加速下载站食用更香。
