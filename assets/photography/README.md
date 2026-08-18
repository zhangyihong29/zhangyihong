# Photography Upload Guide

这个文件夹用于存放 `visual-archive.html` 页面里的摄影作品图片。

## 推荐流程

1. 把照片放到这个文件夹。
2. 使用简洁英文文件名，例如 `photo-01.jpg`、`xiamen-2026-01.jpg`。
3. 在 `visual-archive.html` 的 `masonry` 区域复制一段 `photo-card` 模板。
4. 把图片路径改成 `assets/photography/你的文件名.jpg`。
5. 修改照片标题、时间和地点。
6. 提交后等待 GitHub Pages 自动刷新。

## 卡片模板

```html
<article class="photo-card glass-panel">
  <img src="assets/photography/photo-01.jpg" alt="这里写照片说明" loading="lazy">
  <div class="photo-meta">
    <h2>照片标题</h2>
    <dl>
      <div><dt>Time</dt><dd>2026.08</dd></div>
      <div><dt>Place</dt><dd>Xiamen, China</dd></div>
    </dl>
  </div>
</article>
```
