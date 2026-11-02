# Beijing Farewell Diary · 北京告别日记（插画升级版）

这是完整静态网站。保留了之前的离职倒计时、可编辑日历、任务打勾、三天详细旅行攻略（景点票价/预约/官网/高德地图）、照片日记、心愿清单、烟花、导出/导入备份等功能。这一版新增6张原创插画，以及拆分出的手帐贴纸装饰。

## 最简单的使用方法

1. 下载 ZIP，右键「全部解压缩」。
2. 打开解压后的 `index.html`。该站点的 CSS、JavaScript、图片均为本地文件，无需服务器联网加载。
3. 上传到 GitHub Pages 时，**把 `index.html`、`styles.css`、`app.js`、`favicon.svg`、`assets/` 整个文件夹上传至仓库根目录**。
4. 在 GitHub Settings → Pages → Deploy from a branch → main → /(root) 保存。

不要仅上传 `index.html` 而漏掉 `assets/` 文件夹。

## 你截图里6张按时间下载的 PNG 与新路径的关系

| Windows 下载名结尾 | 内容 | 网站文件 |
|---|---|---|
| `-1.png`（02_19_...） | 原创网站封面 | `assets/cover.webp` |
| `-2.png`（02_20_...） | Day 1 地坛—国子监—景山 | `assets/day1.webp` |
| `-3.png`（02_22_...） | Day 2 钓鱼台—五塔寺—颐和园 | `assets/day2.webp` |
| `-4.png`（02_23_...） | Day 3 奥森与打包 | `assets/day3.webp` |
| `-5.png`（02_25_...） | 手帐贴纸合集 | `assets/stickers.webp`，另有裁好的贴纸 |
| `-6.png`（02_26_...） | 北京秋日天际线横幅 | `assets/panorama.webp` |

**你不用再重命名或重新上传之前下载的PNG**。这些资源已全部打包并做了适合网页的 WebP 压缩。想换成自己原始 PNG 时，可保持路径一致调整文件名和 HTML/CSS 的资源引用。

## 数据保存与隐私

- 任务、日记、照片与心愿存放在浏览器本地 `localStorage`，**不会自动同步到其他设备**。
- 别把 JSON 备份、私人照片、客户资料、工作 SOP 上传到公开 GitHub 仓库。
- 网站内的公开行程范例、景点票价、预约规则是以 2026-10-30 为信息基准，出游前应再次核对官方公告。
- 可以在底部导出完整 JSON 备份；换电脑时在另一台设备上导入。

## 文件结构

```
index.html
styles.css
app.js
favicon.svg
assets/
  cover.webp
  day1.webp
  day2.webp
  day3.webp
  stickers.webp
  panorama.webp
  sticker-leaf.webp
  sticker-gate.webp
  sticker-bicycle.webp
  sticker-mug.webp
  sticker-fireworks.webp
  sticker-suitcase.webp
  sticker-ticket.webp
  sticker-list.webp
  sticker-pin.webp
  sticker-lastdays.webp
```

2026年11月插画限定版 · A soft goodbye, a beautiful beginning.
