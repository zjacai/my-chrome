## 简介

MyChrome 是Google Chrome的便携版引导器，
1. 自定义Chrome浏览器程序文件、数据文件夹、缓存文件夹的位置等。
2. 制作Chrome便携版，可设为默认浏览器。
3. 便携版浏览器可自动更新，支持Stable / Beta / Dev / Canary / Chromium，可设置代{过}{滤}理服务器，支持多线程下载。
4. 支持浏览器启动/退出时运行外部程序。

![https://github.com/cnjackchen/my-chrome/blob/master/MyChrome_v3.7.gif](https://github.com/cnjackchen/my-chrome/blob/master/MyChrome_v3.7.gif)

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

## 最近更新
  **2026.11.23 v3.9.2**
适配 Windows 10 / 11 默认浏览器机制：
1. 按系统要求完整注册便携版（ProgID、Capabilities、RegisteredApplications）。
2. 设置界面新增「设为默认浏览器」，Win11 会打开系统设置完成授权。
3. 固定 AppUserModelID，改善任务栏钉住与窗口分组。
4. 更新 Omaha 通道参数、Chromium x64 快照源，并启用 WinHTTP TLS 1.2。
5. 支持资源管理器右键“用 MyChrome 打开”、开机启动、PDF 关联。
6. 设置窗口跟随系统深色标题栏，并启用每显示器 DPI。

[更新历史](https://github.com/cnjackchen/my-chrome/wiki/History)

## 下载
https://github.com/cnjackchen/my-chrome/tree/master/release
 
32位系统只能用32位的MyChrome/Chrome；64位系统可用任意选择使用32/64位的MyChrome/Chrome。

## 多语言
简体中文，繁体中文，英语。如果您要翻译其他语言:
 1. 选择英语或繁体中文。
 2. 在`lang`文件夹中找到语言文件 `en-US.ini`或 `zh-TW.ini`。
 3. 翻译`lang.ini`。

## 使用说明
 1. 下载并解压`MyChrome_vXX.7z`到任意位置。
 2. 运行 `MyChrome.exe` 显示设置界面，如有必要修改设置。
 3. 点击 `确定`... 就这么简单!
 4. 以后如果要调用设置界面，双击`MyChrome.vbs`。

## 问题反馈
 1. [Issues](https://github.com/cnjackchen/my-chrome/issues)
 2. [卡饭论坛的帖子](http://bbs.kafan.cn/thread-1725205-1-1.html)
