# Apple Logo · 动态渲染

基于 Canvas 的 Apple Logo 粒子动态渲染演示页面。

## 预览

```bash
cd /path/to/repo
python3 -m http.server 8765 --bind 0.0.0.0
```

浏览器访问 `http://localhost:8765/`。若使用 Remote SSH，请在 Cursor **Ports** 面板转发 8765 端口。

也可直接打开 `index.html`（部分浏览器对本地 `file://` 有限制，建议使用本地服务器）。

## 功能

- 粒子从屏幕四周飞入并组装成 Logo 轮廓
- 组装完成后的呼吸光晕效果
- 鼠标扰动粒子；点击后散开并重新组装
- 自适应高分屏与窗口缩放

## 技术

- 纯 HTML / CSS / JavaScript，无构建依赖
- SVG 路径采样 + Canvas 粒子物理动画

## 许可

仅供学习与演示使用。Apple 及相关标识为 Apple Inc. 的商标。
