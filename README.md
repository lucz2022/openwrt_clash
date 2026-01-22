[English](https://github.com/P3TERX/Actions-OpenWrt) | **中文**

# Actions-OpenWrt

使用 GitHub Actions 构建 OpenWrt 的模板

## 使用方法

* 点击 [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) 按钮创建一个新的仓库。
* 使用 [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) 源码生成 `.config` 文件。（你可以通过工作流文件中的环境变量来更改源码。）
* 将 `.config` 文件推送到 GitHub 仓库。
* 在 Actions 页面选择 `Build OpenWrt`。
* 点击 `Run workflow` 按钮。
* 构建完成后，点击 Actions 页面右上角的 `Artifacts` 按钮下载固件。

## 提示

* 生成 `.config` 文件和构建 OpenWrt 固件可能需要很长时间。因此，在创建仓库构建自己的固件之前，你可以先通过在 [GitHub 中搜索 `Actions-Openwrt](https://www.google.com/search?q=%5Bhttps://github.com/search%3Fq%3DActions-openwrt%5D(https://github.com/search%3Fq%3DActions-openwrt))` 来查看是否已有其他人构建了满足你需求的固件。
* 在你的仓库简介中添加一些已构建固件的元信息（如固件架构和已安装的软件包），这将节省他人的时间。

## 致谢

* [Microsoft Azure](https://azure.microsoft.com)
* [GitHub Actions](https://github.com/features/actions)
* [OpenWrt](https://github.com/openwrt/openwrt)
* [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
* [Mikubill/transfer](https://github.com/Mikubill/transfer)
* [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
* [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
* [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
* [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## 许可证

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © **[P3TERX](https://p3terx.com)**
