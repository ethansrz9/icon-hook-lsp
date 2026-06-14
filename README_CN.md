<p align="right">
  <a href="README.md"><img src="https://img.shields.io/badge/lang-en-blue?style=flat-square" alt="English" /></a>
  <a href="README_CN.md"><img src="https://img.shields.io/badge/lang-%E4%B8%AD%E6%96%87-red?style=flat-square" alt="中文" /></a>
</p>

# Icon Hook LSP

![Android](https://img.shields.io/badge/Android-8%2B-3DDC84)
![LSPosed/Xposed](https://img.shields.io/badge/LSPosed%20%2F%20Xposed-module-555555)
![公开发布](https://img.shields.io/badge/%E5%85%AC%E5%BC%80%E5%8F%91%E5%B8%83-APK-blue)
![许可证](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF%E8%AF%81-All%20Rights%20Reserved-red)

Icon Hook LSP 是一个 Android LSPosed/Xposed 模块，支持用户自定义应用名称和图标的显示替换。

维护者：[長島不加冰.](https://github.com/ethansrz9)

项目主页：<https://github.com/ethansrz9/icon-hook-lsp>

本仓库仅发布公开版本和项目信息。私有开发源代码树、完整构建链、内部实现和适配细节均不在此公开。

## 功能特性

- 为指定应用配置替换显示名称。
- 为指定应用配置替换图标。
- 通过配套应用管理启用和禁用替换规则。
- 在支持的 Android 显示界面上应用替换效果。
- 规则仅保存在设备本地。

## 环境要求

- 已获取 Root 权限的 Android 设备。
- LSPosed 或兼容的 Xposed 运行环境。
- 支持的 Android 版本和 ROM 环境。
- 熟悉 LSPosed/Xposed 模块启用和作用域选择的基本操作。

## 下载

从 GitHub Releases 页面下载最新公开版本：

<https://github.com/ethansrz9/icon-hook-lsp/releases>

公开发布文件的校验和详见 `SHA256SUMS.txt`（如有提供）。

## 使用方法

1. 从 GitHub Releases 下载最新 APK。
2. 在设备上安装 APK。
3. 在 LSPosed/Xposed 中启用该模块。
4. 选择模块推荐的作用域。
5. 打开 Icon Hook LSP，为需要自定义的应用创建替换规则。
6. 如更改未立即生效，请重启或重新加载相关 Android UI 进程。

## 说明

- 本仓库为面向发布的公开仓库。
- 不包含完整的私有构建环境。
- 内部实现细节、私有适配笔记和完整源代码均不公开。
- 本仓库不提供复现私有模块实现的说明。
- 公开 APK 构建通过 GitHub Releases 分发。

## 许可证

保留所有权利。详见 `LICENSE` 文件。
