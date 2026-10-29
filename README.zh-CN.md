# cduyzh Mac 工具集

[English](README.md) | [简体中文](README.zh-CN.md)

一个简洁的双语 Mac 原生工具集合，由 cduyzh 开发。访问 **[apps.cduyzh.top](https://apps.cduyzh.top/)** 浏览各款应用。

## 工具介绍

| 应用 | 功能 | 项目地址 |
| --- | --- | --- |
| SnapScreen（极速截屏） | 截图、长截图和屏幕录制 | [GitHub](https://github.com/cduyzh/SnapScreen) |
| iTrans（极译 AI） | 菜单栏翻译，曾用名 TransBar | [GitHub](https://github.com/cduyzh/TransBar) |
| ProcessLens（进程监视器） | 监测进程、CPU 和内存 | [GitHub](https://github.com/cduyzh/ProcessLens) |
| DiskSweep（磁盘清理大师） | 查找大文件和重复文件 | [GitHub](https://github.com/cduyzh/DiskSweep) |
| MenuBarTidy（菜单栏管家） | 整理菜单栏图标 | [GitHub](https://github.com/cduyzh/MenuBarTidy) |
| WallpaperLoop（动态壁纸） | 设置视频和图片壁纸 | [GitHub](https://github.com/cduyzh/WallpaperLoop) |
| MediaSaver（媒体收藏家） | 收藏视频并制作 Live Photo 和 GIF | [GitHub](https://github.com/cduyzh/MediaSaver) |
| TouchFlow（触控流） | 触控板手势和窗口操作 | 项目资料整理中 |

## 本地运行

这是无需构建或运行时依赖的静态网站。直接在浏览器打开 `index.html`，或使用任意静态 HTTP 服务器运行。首页默认显示英文，`zh.html` 为简体中文版；旧英文地址 `en.html` 会跳转至首页。

应用简介和链接分别维护在两种语言的 HTML 页面中，图标位于 `assets/icons/`，共享样式位于 `styles.css`。页面包含 canonical、双向语言标记和 JSON-LD；`sitemap.xml` 与 `robots.txt` 使用预定的线上地址。搜索引擎收录取决于部署情况和后续抓取。

作者：[cduyzh](https://www.cduyzh.top/)。
