# 戴肥肥桌宠 DaiFeiFei

一只住在 Windows 和 Mac 桌面上的灰白胖猫，戴着绿围巾。免费，不联网。

- 眼睛和脑袋跟着你的鼠标，会呼吸、眨眼、摇尾巴
- 把鼠标在它头上来回摸，它会眯起眼睛打呼噜、冒爱心
- 你在任何地方滚鼠标滚轮（看网页、看代码），它就在猫抓棒上磨爪子
- 把它拖到屏幕左边或右边边上放下，它就藏在边外探头往里看
- 一会儿没人理它，它会自己打哈欠、舔爪子洗脸、打盹点头
- 看视频、打游戏、放幻灯片全屏时它会躲起来，退出全屏就回到原处（只有 Windows 版有）
- 可以换衣服：头、脸、脖子、尾巴四个部位，有围巾、领结、铃铛项圈、小圆帽、蝴蝶结、小皇冠、圆眼镜、单片眼镜、丝带、条纹尾套，可以混搭，下次打开还记得
- 可以拖到任何地方，右键或托盘图标里可以换衣服、调 7 档大小、开机自启、退出

## 下载和运行

到 [Releases](../../releases) 下载最新版本。

### Windows

1. 下载 `DaiFeiFei-<版本>-win-x64.zip`
2. 解压到任意文件夹，双击 `DaiFeiFei.exe`
3. 第一次打开时 Windows 可能提示“Windows 已保护你的电脑”（程序没有签名），点“更多信息”再点“仍要运行”

卸载就是退出后删掉文件夹，设置在 `%APPDATA%\DaiFeiFei`，也可以一起删掉。

### Mac

1. 下载 `DaiFeiFei-<版本>-mac-arm64.dmg`。只支持 Apple 芯片（M1 及以后）的 Mac，Intel 芯片的 Mac 用不了
2. 打开 dmg，把 DaiFeiFei 拖进“应用程序”
3. 第一次打开时 macOS 会提示无法验证开发者（程序没有签名）：先关掉提示，到“系统设置 → 隐私与安全性”最下面点“仍要打开”。如果提示“已损坏”，在终端运行 `xattr -cr /Applications/DaiFeiFei.app` 再打开
4. 想让它磨爪子，要在“系统设置 → 隐私与安全性 → 辅助功能”里打开 DaiFeiFei（它要靠这个知道你在滚滚轮），然后重新打开它

猫的图标在屏幕顶部的菜单栏里，不在 Dock 里。Mac 版没有全屏时躲起来。卸载就是退出后把 DaiFeiFei 从“应用程序”删掉，设置在 `~/Library/Application Support/DaiFeiFei`，也可以一起删掉。

猫跑到屏幕外找不到了？从托盘（Mac 上是菜单栏）图标退出，再打开它就会回来。

## 条款

免费使用，可以原样转发；不得出售，不得修改后再发布。“戴肥肥”的名字和形象保留所有权利。完整条款见 zip 或 dmg 里的 `使用条款.txt`，第三方组件的许可见 `licenses` 文件夹。

源码不公开。

## 致谢

灵感来自桌面宠物 [Comnyang](https://www.comnyang.com/en)。本项目与 Comnyang 及其作者没有任何关系，不包含 Comnyang 的任何代码或素材。

---

**DaiFeiFei** is a free, offline desktop pet for Windows and Mac: a chubby grey-and-white cat in a green scarf. It follows your cursor, purrs when you stroke its head, scratches a post while you scroll, and yawns, washes or dozes when left alone. Dress it up from the right-click menu with ten pieces of clothing across head, face, neck and tail. Download the zip (Windows) or the dmg (Mac with Apple silicon only) from Releases. The Mac app is unsigned: allow it under System Settings → Privacy & Security, and grant it Accessibility there for the scratching. Inspired by Comnyang; not affiliated with it and contains none of its code or assets. All rights to the DaiFeiFei character reserved.
