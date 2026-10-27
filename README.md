# Chuangyou Huyu Official Website

北京创游互娱科技有限公司官方网站。

静态网站，包含公司简介与九款休闲小游戏介绍，适配桌面与手机。

## 文件

- `dist/index.html`：页面结构与文案
- `dist/styles.css`：页面样式
- `dist/assets/`：公司标识与游戏图标

## 本地预览

```sh
python3 -m http.server 8766 --directory dist
```

浏览器访问 http://localhost:8766/ 。也可直接打开 `dist/index.html`。

## 发布

GitHub Pages 部署目录为 `dist/`，只发布静态网站内容。

## 版权

© 2026 北京创游互娱科技有限公司。网站图文、标识及游戏素材保留所有权利。
