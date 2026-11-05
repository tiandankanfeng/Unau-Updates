# Unau

少一点寻找，多一点专注。

Unau 是一个 macOS 窗口工具，可以跨屏浏览窗口，按工作整理集合。

## 下载与更新

从 [Releases](https://github.com/tiandankanfeng/Unau-Updates/releases) 下载 Universal DMG。Apple Silicon 和 Intel 使用同一个安装包。目标系统为 macOS 13 及以上，Intel 实机和旧版 macOS 尚待验收。

目前仍是 beta。安装包采用临时签名，尚未经过 Apple 公证，首次打开可能需要在「系统设置 › 隐私与安全性」中允许。辅助功能用于切换窗口，屏幕录制仅用于预览，可按需允许。

退出 Unau 后打开 DMG，将 `Unau.app` 拖入 Applications。与 `SHA256SUMS.txt` 同目录时，可运行 `shasum -a 256 -c SHA256SUMS.txt` 核对下载。

beta.1 需要手动安装一次 beta.2。从 beta.2 开始，可以在应用内检查更新、预览更新内容，再决定是否下载和安装。不会自动检查或弹窗催促。设置中可选择中文、英文或日语，默认中文。

保留一个已验证的旧版安装包，需要恢复时退出 Unau，再替换完整应用；收藏的窗口集合和系统权限不会随应用版本回退。

这个仓库只提供安装包、发布说明和签名更新源，源码保存在独立的私有仓库中。应用许可随安装包提供。

如果你喜欢我的作品，欢迎[了解 Komoribe 的创作](https://sponsor.komoribe.ink/)。支持随心，使用和分享也是支持。
