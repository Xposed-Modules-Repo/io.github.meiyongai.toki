# Toki

面向 TikTok 的 LSPosed 模块，让 TikTok 更合你的使用习惯。

[English](README.md) · **简体中文**

[下载 APK](https://github.com/Xposed-Modules-Repo/io.github.meiyongai.toki/releases/latest) · [源码](https://github.com/MeiYongAI/Toki) · [问题反馈](https://github.com/MeiYongAI/Toki/issues/new/choose) · [Telegram 群组](https://t.me/toki_lsposed)

本仓库是 `io.github.meiyongai.toki` 的模块分发仓库。
源码、开发文档和问题反馈统一在 [MeiYongAI/Toki](https://github.com/MeiYongAI/Toki) 维护。
这里的 Releases 分发与源码仓库相同的已签名 APK。

## 使用条件

- Android 9 及以上。
- 支持 **libxposed API 102** 的 LSPosed。
- 官方 TikTok **47.1.4**、**47.0.3** 或 **46.8.3**。
- 模块作用域：`com.zhiliaoapp.musically` 或 `com.ss.android.ugc.trill`。

不支持第三方修改版 TikTok。请勿使用隐藏应用列表（HMA）向 TikTok 隐藏 Toki。

## 主要功能

信息流过滤、页面布局净化、播放控制与自动连播增强、媒体工具、地区设置、
功能诊断及配置导入导出。采用 Material 3 界面，支持 57 种界面语言。

## 安装与更新

1. 从 [Releases](https://github.com/Xposed-Modules-Repo/io.github.meiyongai.toki/releases/latest) 安装 APK。
2. 在 LSPosed 中启用 Toki，并勾选已安装的 TikTok 作为作用域。
3. 配置 Toki 后，强行停止并重新打开 TikTok。如触发方法查找，等待完成并关闭提示，
   再次强行停止并重新打开 TikTok。

**从 1.0.1 及以上版本更新：** 可以直接覆盖安装最新 APK。

**从 1.0.0 更新：** 1.0.1 起使用新的签名。请先导出 Toki 配置，卸载 Toki，
安装最新 APK 后导入配置，并重新确认激活与作用域。无需卸载 TikTok。

**从 0.x（`com.seepd.toki`）迁移：** 包名已更换，请先停用旧模块再启用新版。
配置不会自动迁移，卸载旧模块前请保留需要的设置。

详见[完整指南](https://github.com/MeiYongAI/Toki/blob/main/README.zh-CN.md)和
[更新日志](https://github.com/MeiYongAI/Toki/blob/main/CHANGELOG.md)。

## 项目信息

本项目使用 AI 生成的代码，可能存在错误。Toki 与 TikTok、字节跳动不存在隶属或背书关系，
按现状提供。请尊重创作者权益并遵守适用法律。
[许可证与第三方声明](https://github.com/MeiYongAI/Toki/blob/main/README.zh-CN.md#许可证)。
