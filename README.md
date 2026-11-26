# 长夜邮差 · The Long Night Post

一款在小星球上行走的第三人称叙事探索游戏。长夜季来临前，发条邮差“嘀嗒”要把最后几封信送到小星球上，每送到一封，那颗星的邮灯就会亮起来。

故事、角色、星球、模型和配乐全部是原创的。这一版用 Unity 6 + HDRP 重做了画面，目前可以玩第一站“发条屿”和第二站“风车星”，其余几站还在移植。

## 下载

到 [Releases](https://github.com/Air-Sage/long-night-post-play/releases/latest) 下载 `LongNightPost-mac.zip`，解压得到 `LongNightPost.app`。

**第一次打开**：这个程序没有苹果的开发者签名和公证，第一次双击会弹出“Apple 无法验证‘LongNightPost’是否包含……恶意软件”，这是正常的，按下面做一次就好：

1. 在提示框里点“完成”（别点“移到废纸篓”）。
2. 打开“系统设置 → 隐私与安全性”，往下滚到“安全性”一栏，会看到“已阻止‘LongNightPost’以保护你的 Mac”，点旁边的“仍要打开”。
3. 输入开机密码（或按触控 ID），在再弹出的框里点“仍要打开”。

之后就能正常双击了。“仍要打开”只在被拦下后的一段时间里出现，没看到就先再双击一次程序。macOS 14 及更早的系统也可以在 Finder 里按住 Control 点按程序，选“打开”。熟悉终端的话，也可以输入 `xattr -dr com.apple.quarantine `（末尾有空格），把 `LongNightPost.app` 拖进终端窗口再回车。

**配置**：macOS 12 或更新，Apple 芯片和 Intel 都能运行，建议 M1 或更新的 Mac。游戏会根据显卡负载自动调整渲染分辨率来保持流畅；如果还是卡，暂停后按 G 换成“低”画质。

## 操作

| 按键 | 作用 |
| --- | --- |
| W A S D / 方向键 | 移动 |
| 鼠标 | 转视角 |
| Shift | 快跑 |
| 空格 | 跳 |
| E | 互动 / 推进对话 |
| Esc | 暂停（R 重来本站，1 / 2 去往第一 / 第二站，L 切换中英文，G 切换画质，Q 退出） |
| Q（按住） | 送完信之后启程去下一站 |
| F2 | 切换到材质与光影展台（看模型用），再按一次回到游戏 |

也支持手柄。

## 素材

模型和材质由 Blender 脚本生成；扫描贴图来自 [Poly Haven](https://polyhaven.com)（CC0）；界面文字用的是 macOS 自带字体；音乐和音效由程序合成。

---

**English**: a third-person story game about a wind-up postman delivering the last letters across tiny planets before the long night. Download `LongNightPost-mac.zip` from Releases and unzip it. The app is not signed or notarized by Apple, so the first launch says Apple could not verify it. Click Done, open System Settings → Privacy & Security, scroll to Security and click Open Anyway next to LongNightPost, then confirm with your password and click Open Anyway again. (On macOS 14 and older, Control-click → Open also works.) Requires macOS 12+; Apple silicon recommended. Stops 1 and 2 are playable in this version (Esc, then 1 or 2 to jump to a stop).

这个仓库只存放打包好的安装包，由脚本自动发布。
