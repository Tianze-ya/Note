---
title: PowerShell7的配置
date: 2025-12-06
categories: 软件
tags:
cover:
---
# 简介
PowerShell 7 是微软开发的跨平台命令行工具，基于.NET Core构建，支持Windows、Linux和macOS系统。它提供了强大的自动化脚本功能、对象管道处理、丰富的模块生态系统，是系统管理和DevOps的重要工具。

# 使用
[Github](https://github.com/PowerShell/PowerShell)
下载
```bash
winget install --id Microsoft.PowerShell --source winget
```
配置文件`$PROFILE`

# 模块 
## PSCompletions
```bash
Install-Module PSCompletions -Scope CurrentUser
scoop bucket add abyss https://github.com/abgox/abyss
scoop install abyss/sigoden.Argc-completions
```
配置文件中添加
```
Import-Module PSCompletions
```
