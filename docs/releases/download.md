---
lang: zh-CN
title: 下载安装
---

# 下载安装

## 环境要求

Windows 10 1809 及以上版本，建议升级到最新版本。

## 下载

通过以下链接下载最新版本：

[线路一](https://file.xunkong.cc/download/desktop/Xunkong.Desktop.Package.zip)

[线路二](https://scighost-generic.pkg.coding.net/xunkong/releases/Xunkong.Desktop.Package.zip)

## 安装

- 解压已下载的安装包
- 找到名为 **Install.ps1** 的文件，右键点击打开菜单
- 点击 **使用 PowerShell 运行**
- 根据提示完成后续操作
- 安装完成后，点击开始菜单的寻空图标启动应用

## 可能遇到的问题

#### 无法加载文件 Install.ps1，因为在此系统中禁止执行脚本。

以管理员身份运行 PowerShell，输入 `Set-ExecutionPolicy RemoteSigned` ，然后按下回车。

上述语句的作用是允许本地计算机中未签名的脚本运行。

#### 应用安装在哪里

以 MSIX 打包的应用安装在 `C:\Program Files\WindowsApps` 文件夹内。