# DeskSocket

![Platform](https://img.shields.io/badge/paltform-win--64-brightgreen)
![Qt Version](https://img.shields.io/badge/_Qt_-6.x.x、5.x.x-yellowgreen)
![Build](https://img.shields.io/badge/build-MSVC_2019_x64-blue)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/Mtr1994/DeskSocket)
![GitHub](https://img.shields.io/github/license/Mtr1994/DeskSocket)

`DeskSocket` 是一款用于测试网络通信的桌面（`Windows 10`）工具软件，软件支持 `TCP 服务端`、`TCP 客户端` 、`UDP 服务端` 和`UDP 客户端` 四种工作模式；同时对每种模式提供几种重要的菜单功能，满足程序员日常工作中对网络数据通信测试的需求。

#### 编译环境及语言

* 系统版本：`Windows 10 (x64)` 
* 开发环境：`Qt 6.2.1` 
* 编译器　：`MSVC 2019 64 bit`
* 开发语言：`C++ (11)`    `QMake`    `QSS`

#### 第三方依赖说明

* 软件使用 `HP Socket` 作为通信库，在实际的运行过程中，需要将动态库（./Libs/hpsocket/bin/HPSocket_U.dll）添加到系统环境变量，或者将其拷贝到可执行文件夹所在目录

* 软件使用 `spdlog` 作为日志库，在实际的运行过程中，需要将动态库（./Libs/spdlog/bin/spdlog.dll）添加到系统环境变量，或者将其拷贝到可执行文件夹所在目录
