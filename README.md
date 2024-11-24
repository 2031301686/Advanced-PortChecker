# 高级端口检查器

![高级端口检查器](https://i.imgur.com/vdt1sXZ.png)

![GitHub](https://img.shields.io/badge/语言-JavaScript+Rust-绿色)
![GitHub](https://img.shields.io/github/license/CodeDead/Advanced-PortChecker)
![GitHub发布（按日期最新）](https://img.shields.io/github/v/release/CodeDead/Advanced-PortChecker)
[![测试](https://github.com/CodeDead/Advanced-PortChecker/actions/workflows/test.yml/badge.svg)](https://github.com/CodeDead/Advanced-PortChecker/actions/workflows/test.yml)
[![发布](https://github.com/CodeDead/Advanced-PortChecker/actions/workflows/release.yml/badge.svg)](https://github.com/CodeDead/Advanced-PortChecker/actions/workflows/release.yml)

高级端口检查器是一款免费的开源应用程序，可帮助您检查特定主机上的端口是打开还是关闭状态。您可以一次性检查多个端口，并将结果以纯文本、CSV或JSON格式导出！

## 构建

高级端口检查器使用Tauri来构建桌面应用程序。您可以在此处[https://tauri.app/v1/guides/](https://tauri.app/v1/guides/)找到有关Tauri的更多信息。

有关使用`vite`进行构建的更多信息，请阅读此处[https://vitejs.dev/guide/build.html](https://vitejs.dev/guide/build.html)的`Vite`文档。

### 开发

您可以通过运行`yarn tdev`命令来启动开发预览：
```shell
yarn tdev
```

### Windows系统

#### 安装程序

您可以通过在Windows主机上运行`yarn tbuild`命令来创建一个可执行的安装程序：
```shell
yarn tbuild
```

### Linux系统

#### deb格式

您可以通过在Linux主机上运行`yarn tbuild`命令来创建一个.deb文件：
```shell
yarn tbuild
```

#### AppImage格式

您可以通过在Linux主机上执行`yarn tbuild`命令来创建一个[AppImage](https://appimage.github.io/)文件：
```shell
yarn tbuild
```

### macOS系统

#### dmg格式

您可以通过在macOS主机上运行`yarn tbuild`命令来创建一个macOS版本的构建：
```shell
yarn tbuild
```

#### 归档文件

您可以通过在macOS主机上运行`yarn tbuild`命令来创建一个macOS版本的构建：
```shell
yarn tbuild
```

## 鸣谢

## 中文维护
本项目由[天无神话](https://github.com/2031301686)提供中文语言，它的博客地址为：[https://wxsnote.cn/](https://wxsnote.cn/)

### Tauri
本项目使用[Tauri](https://tauri.app/)来创建跨平台应用程序。

### ReactJS
本项目使用[React](https://reactjs.org/)来创建用户界面。

### 主题
本应用程序中使用的主题是[MUI](https://mui.com/)。

### 图片
应用程序图标（及其衍生图标）由[RemixIcon](https://remixicon.com/)提供。
所有其他图片由[MUI](https://mui.com/material-ui/material-icons/)提供。

## 关于我们
这个库由CodeDead维护。您可以通过以下链接了解更多关于我们的信息：
* [网站](https://codedead.com/)
* [推特](https://twitter.com/C0DEDEAD/)
* [脸书](https://facebook.com/deadlinecodedead/)

版权所有 © 2024 CodeDead 
