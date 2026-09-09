# Mr. Krabs Codex Pet

这是一个面向非技术用户的 Codex 宠物安装页。

将本目录作为静态网站发布即可。页面会根据自身网址生成官方客户端可识别的安装链接：

```text
codex://pets/install?name=...&description=...&imageUrl=https://.../spritesheet.webp&spriteVersionNumber=2
```

托管要求：

- 页面和 `spritesheet.webp` 必须使用 HTTPS。
- 精灵图地址必须直接返回图片，不能经过跳转。
- 精灵图响应类型应为 `image/webp`。
- `index.html` 与 `spritesheet.webp` 保持在同一目录。

推荐用 GitHub Pages 发布。访问者打开网页后点击一次大按钮，在 Codex 预览窗口中再点击一次“安装”。
