# msys-cn

This wiki exported from code.google.com/p/msys-cn

MSYS 中国项目，Windows 下程序开发、远程登录、科学计算、代码移植的瑞士军刀。

## 项目简介

MSYS 不是一个操作系统，而是一个将 Linux 源代码在 Win 32 上编译而成的 UNIX 工作环境。MSYS 类似于 Cygwin，但是由于工作原理的不同，速度更快、体积更小、功能强大、便于携带。

你可以使用 MSYS 可以完整地取代商业的 VC 环境，在开发商业版权程序的时候不受任何版权限制。

本项目开发了 mpkg 包管理程序，添加对各种开源库支持，提供 MSYS 发行版的方便下载服务。默认提供捆绑在一起的 ASM / C / C++ / ObjC / ObjC++ / Fortran 编译器，适用于各种用户。编译器中预先配置好了所需的 DDK、DirectX 9 SDK、Pthread 库，无需再次调试开发环境。

本项目的初衷，是为 Phoenix 操作系统开发项目提开发环境。但时过境迁，如今的 Windows 已经内置了非常出色的 Linux 子系统（WSL），这个项目也少了很多实用价值。不过对于那些希望深入了解如何在 Windows 下搭建 UNIX 开发工具链的朋友们来说，此项目仍然存在一些参考价值。

项目通过 GNU 开发的 info 帮助系统提供了所有命令的帮助手册，开发者应当用 MSDN 作为函数手册。

## 相关教程

01. 介绍、下载与安装方法
02. 操作系统历史回顾
03. MSYS 开发环境与开发工具
04. 基于 MSYS 环境的 C 语言教程（精简版）
05. 基于 MSYS、MingW 的 Windows 编程教程
06. 基于 MSYS 的 Flex & Bison（编译器开发工具）使用教程
07. 基于 MSYS 的 Win32 动态链接库 DLL 开发
08. 基于 MSYS 的 Windows 驱动程序开发
09. 通用 PID 算法例子
10. 数据结构与算法快速教程
11. 让 kqemu 加速模块可以在 windows 的 mingw 上编译的代码补丁
12. 通用数学矢量类算法封装
13. 手写词法分析教程
14. 通用多源代码格式支持、依赖关系支持 Makefile
