# Talos

Talos 是 macOS 上的编程 agent。这个仓库只放安装包和自动更新用的文件，源码不在这里。

## 安装

从 [Releases](https://github.com/shqingda/talos-releases/releases/latest) 下载 Apple Silicon 的 DMG，把 Talos.app 拖进「应用程序」。

安装包采用 ad hoc 签名，尚未公证。首次打开若被拦截，可在「系统设置 → 隐私与安全性」中允许。

装好以后，Talos 会自己检查并安装更新，也可以在菜单「Talos → 检查更新」里手动检查。每个版本的 `SHA256SUMS` 可用来核对下载的文件。
