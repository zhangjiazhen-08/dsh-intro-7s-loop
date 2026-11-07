# dsh-intro-7s-loop

给 [dsh-cinematic-wallpaper](https://github.com/zus12873/dsh-cinematic-wallpaper) 做的自定义开场视频：先播 [dsh-startup-screen](https://github.com/6shenhonghong9/dsh-startup-screen) 的启动动画（黑幕、标识、过曝、档案底板、授权、揭幕），再接大脸的 7 秒开场（光丝、线框、面部扫描、闭眼、睁眼），播完回到大脸常驻壁纸。

Custom intro videos for the DSH plugin `dsh-cinematic-wallpaper`: the startup-screen animation followed by the 7-second cinematic intro, then the big-face session wallpaper stays on.

## 文件 / Files

- `dsh-combo-intro.mp4`：startup-screen + 大脸 7 秒开场（拼接版），约 27 秒。

> 视频文件较大，由作者手动上传到本仓库；如仓库里暂时没有，请稍后再看。

## 需要 / Requirements

- DSH `>= 0.1.5-rc.1`（web profile）
- 已安装 `dsh-cinematic-wallpaper`（[安装方法](https://github.com/zus12873/dsh-cinematic-wallpaper#install)）

## 用法 / Usage

1. 把想用的 mp4 放进 `~/.dsh/dsh-cinematic-wallpaper/media/`。
2. 打开 DSH 的 **设置 → 插件 → Intro & background**。
3. 只把 **Intro** 选成这个文件；**Background 别动**，保持默认的大脸循环。
4. 下次打开 DSH 就会播这个开场。点一下或按任意键可以跳过。

## 说明 / Notes

- 开场播完后，常驻桌面还是默认的大脸壁纸（头发摆动的循环）。
- startup-screen 那段取自它仓库里的预览动图（720×500），放大到 1080p 后会比大脸那段软一点。
- 7 秒开场后半段（睁眼、虹膜泛绿、推近）是原插件用代码实时画的，这里用插件自带的静帧素材（plate + 闭眼贴片）重建了一个近似版本，不是原视频。

## 致谢 / Credits

- [dsh-startup-screen](https://github.com/6shenhonghong9/dsh-startup-screen) by 6shenhonghong9（MIT）
- [dsh-cinematic-wallpaper](https://github.com/zus12873/dsh-cinematic-wallpaper) by zus12873（MIT）
