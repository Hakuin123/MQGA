# MAKE QQ GREAT AGAIN!

欢迎，这里是MQGA研究院[^1]。“让QQ再次伟大！”

[^1]: 此虚拟架空设定仅存在于此GitHub仓库，请不要在其他[白熊工作室](http://www.HK256.top)相关话题下提起。

QQ最新 & 8.9.58 状态：![状态：default](https://github.com/Hakuin123/MQGA/actions/workflows/default.yml/badge.svg)

MQGA修补包下载次数：![download](https://img.shields.io/github/downloads/Hakuin123/MQGA/total?logo=github)

## “为什么追我？”“我要MQGA！”

### QQ 最新版/8.9.58
请在[Releases](https://github.com/Hakuin123/MQGA/releases)下载已打包完成的最新版或8.9.58版本QQ。

### 修补自定义QQ版本
<details><summary>点击这里展开教程</summary>
<p>

1. [登录GitHub](https://github.com/signin)，然后[Fork](https://github.com/Hakuin123/MQGA/fork)此仓库
2. 在**你自己fork后的仓库**（带有你自己的用户名）页面顶部点击`Actions`
3. （点开`All workflows`后）点击`Custom`
4. 点击蓝色`#DDF4FF`横幅`This workflow has a workflow_dispatch event trigger.`右边的`Run workflow`
5. 在弹出的窗口内填写下列内容：
  - **自定义版本号**  输入你所自定义的QQ版本（仅作名称标识作用，是否正确填写对于实际修补无影响）
  - **指定下载链接**  输入QQ/TIM安装包直链
  - **模块版本通道**  选择使用正式版（default）还是测试版（CI）的模块
6. 填写完成后点击绿色`#1F883D`的`Run workflow`并刷新页面，等待新增的工作流`Custom`的图标由黄色`#DBAB0A`变为绿色`#1F883D`，点开这个~~刚冒出来的花里胡哨变色的~~`Custom`
7. 在`Artifacts`找到修补完成的.apk文件，点击以下载（未登录状态下无法下载）

> 若Actions执行失败（状态为红色`#D1242F`），请自行检查输入的链接是否为直链，也就是说输入的链接在浏览器打开后能够自动下载安装包。可百度自行获取直链。

</p>
</details>

> 免责声明：本仓库仅提供服务整合，QQ安装包及模块均由第三方提供，如在使用中出现问题，本仓库不对此负任何责任。下载本仓库提供的资源即表示同意上述声明。

## 我们做了什么

我们借助[LSPatch](https://github.com/LSPosed/LSPatch)的“便携模式”修补QQ，并在其中嵌入以下好用的开源模块：

- [QAuxiliary](https://github.com/cinit/QAuxiliary)
- [XAutoDaily](https://github.com/LuckyPray/XAutoDaily)
- [TSBattery](https://github.com/fankes/TSBattery)
- [QQ瘦身（QQCleaner）](https://github.com/KitsunePie/QQCleaner)

（如果发现有更多好玩好用的模块，欢迎[发Issue推荐给我们](https://github.com/Hakuin123/MQGA/issues/new)。）

## 计划实现的功能

- [x] 借助GitHub Actions修补QQ #1
- [x] 修补时自动下载最新版本QQ（使用固定连接） #2
- [ ] 当模块更新时自动重新修补
- [ ] 当QQ更新时自动重新修补
- [ ] 重修补后邮件通知使用者
- [x] Releases版本号迭代
- [ ] 


## 推荐的QQ版本

### [QQ NT（当前最新版）](https://im.qq.com/index/#downloadAnchor)
最新版QQ基于[Election](https://www.electronjs.org/zh/)重写，性能得到大幅提升

### [QQ 8.9.58(补包2)](https://downv6.qq.com/qqweb/QQ_1/android_apk/Android_8.9.58_64_HB2.apk)
最后一个不基于QQ NT的版本

### [QQ 8.8.50](https://dldir1.qq.com/qqfile/qq/expcenter/1458/28d2b3f249db11ec819ad00d4e61d76c/qq_8.8.50.6735_rb4227cab_v2324_release.apk)
最后一个不是3A大作（未内置虚幻引擎4，无超级QQ秀）的版本

### [TIM（当前最新版）](https://office.qq.com/download.html)
极为简洁的版本，底包基于QQ 8.3.9

### [TIM 3.4.8]()
无云控，邮箱入口不会被移除

## 更好地食用

配合GitHub镜像站/加速下载站更香。

另请参阅：https://github.com/librarycloud/list
