# ClawdCut Animation

小 Clawd 在 Mac 桌面上打开剪辑软件 ClawdCut，跳进去亲手剪片子的手绘风卡通动画。

- 纯前端：SVG + [GSAP](https://gsap.com/) 时间轴，音效与 BGM 由 Web Audio 实时合成
- 剧情：戳图标 → 跳进软件摔成饼 → 拽片段、剪刀剪辑、弹飞无聊片段、拍入转场 → 调色调过头亮瞎眼、戴墨镜救场 → 导出卡在 99%，一记飞踢搞定

## 运行

```bash
python3 -m http.server 8000
```

然后打开 http://localhost:8000/index.html ，点击开始播放。

快捷键：`空格` 播放/暂停，`←/→` 前后跳 1 秒，`R` 重播，`M` 静音。
