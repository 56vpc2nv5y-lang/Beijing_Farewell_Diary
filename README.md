# Beijing Farewell Diary · 最新图标整合版（2026-11-02）

**这是完整版、可直接部署 GitHub Pages 的网站。** 包含之前全部插画和贴纸，以及新版原创图标。保留11月2日已经修复的“自动定位北京时间今天”逻辑；不会主动清空浏览器里旧的任务、日记和照片。

## 本次更新

- 首页导航左上角的原来 `B.` 小标记改成原创的“天坛 + 金色银杏 + 手帐本”插画。
- 浏览器标签页 favicon：`favicon.ico`、`favicon-32.png`、`favicon-48.png`。
- iPhone/iPad 添加到主屏幕：`apple-touch-icon.png`。
- Android/Chrome 添加到主屏幕：`manifest.webmanifest` 和 `assets/icons/` 下的 192/512 及 maskable 图标。
- 完整原图 `icon-source.png` 可用于日后再次设计；新增的 `favicon.svg` 为配套的简化矢量版。
- 保留原站点日历、任务、离职倒计时、北京三日赏秋攻略、门票与路线、照片日记、愿望和烟花。

## 怎么使用

1. 下载 ZIP 后**先全部解压**。双击解压后的 `index.html`（建议 Chrome / Edge）。
2. 发布 GitHub Pages：将 ZIP 中的 `index.html`、`styles.css`、`app.js`、`manifest.webmanifest`、图标文件和整个 `assets` 文件夹上传到 GitHub 仓库根目录。
3. 仓库 Settings → Pages → Deploy from a branch → `main` → `/(root)`。
4. 如果部署后仍看到旧图标，按 **Ctrl+F5** 强制刷新或在隐私窗口打开。手机桌面上已经保存的旧快捷方式通常需要删掉并重新“添加到主屏幕”。

**说明：** 在本地 `file://` 直接打开时，网页正常使用，浏览器标签图标和顶部图标会显示；手机桌面快捷方式和 manifest 的完整支持通常需要通过 HTTPS（如 GitHub Pages）访问。

## 数据与隐私

- 日记、照片和打勾状态存储在浏览器的 `localStorage`，不同设备不自动同步。
- 为避免丢失资料，请定期点击网页的 **导出完整备份**。更新同一个 GitHub Pages URL 不应清空旧数据；换域名、浏览器、无痕模式或清理网站数据则无法自动继承。
- 不要把个人照片、私人日记备份或公司 SOP 上传到公开 GitHub 仓库。
- 这版**没有引入服务工作线程（Service Worker）**，避免手机浏览器缓存旧版网站；离线双击使用可用，但完整的 PWA 离线安装功能未承诺。
