# 嘎嘎AI视频提取 · Mac 分享版

[下载最新版完整安装包](https://github.com/xugaga123/gaga-ai-video-extractor-downloads/releases/latest)

## 选择下载

- **M 系列 Mac（M1及更新芯片）**：下载最新版完整 ZIP，已含 Node.js、FFmpeg 和本地助手，无需额外准备环境；需要 macOS13.5+ 和 Chrome。
- **Intel 老款 Mac**：使用 [v0.8.1 轻量包](https://github.com/xugaga123/gaga-ai-video-extractor-downloads/releases/tag/v0.8.1)，按其手册安装 Node.js 与 FFmpeg。

## 完整包使用

1. 完整解压 ZIP，双击「安装.command」。助手和运行环境会配置到本应用目录，并设置登录电脑后自动启动，不修改电脑已有环境。
2. 按提示在 Chrome 扩展程序页开启开发者模式，加载安装脚本打开的 extension 文件夹。
3. 填写提供给你的邀请码，设置自己的转写 API；需要 AI 整理时填写自己的 AI API。
4. 先测试连接，再用一条短视频提取、整理和保存。

这是脚本安装并手动加载 Chrome 扩展的方式。暂未做开发者签名或苹果公证；macOS 首次可能要求在「隐私与安全性」中允许打开，程序不能代替使用者确认。失败请保留窗口中的报错。

AI 规则支持下拉切换、编辑和新增，保存在自己的浏览器中。可保存到 Obsidian、飞书或仅插件显示；视频保存位置跟随文稿输出方式。

此仓库只提供安装包与使用说明。下载 Release 中的完整 ZIP 即可，GitHub 自动生成的 Source code 不是安装包。每版附 SHA256，历史安装包保留；当前为手动更新。

第三方许可：完整包使用 Node.js（MIT及附带第三方许可），独立运行的 [FFmpeg](https://ffmpeg.org/)（LGPL2.1或更新）及 LAME（LGPL）。对应许可、FFmpeg/LAME源码与构建方法均在完整ZIP内提供。
