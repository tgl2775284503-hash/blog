---
date: 2026-03-25
categories:
  - 视频教程
tags:
  - 工具
  - AI
---
# Openclaw 安装、使用教程（Mac、Windows）

---

## 一、常用网址

* **Openclaw 官网**：[https://openclaw.ai/](https://openclaw.ai/)
* **Node.js 官网（中国区）**：[https://nodejs.org/zh-cn](https://nodejs.org/zh-cn)
* **Git 官网地址**：[https://git-scm.com/](https://git-scm.com/)

---

## 二、准备工具
* **远程控制软件（Todesk）**：[https://www.todesk.com](https://www.todesk.com/download.html)
* **代理软件（V2rayN）**:[https://github.com/2dust/v2rayN](https://github.com/2dust/v2rayN)
```节点订阅地址（自用）
https://usapi.saojc.xyz/assets/user/avatar/ab4e66a5e278.png?ref=8eda51132217e4f36e7f5a85b033a003
```

---

## 三、Windows 版本安装方法

### 1. 安装 Node.js + npm
* **下载地址 Node.js 官网（中国区）**[https://nodejs.org/zh-cn](https://nodejs.org/zh-cn)

* **检查node版本命令：**
```powershell
node -v  
# 正确返回结果示例：v24.13.0
```

* **检查npm版本命令**
```powershell
npm -v 
# 正确返回结果示例：11.6.2
```
### 2.安装Git
* **下载地址 Git官网**[https://git-scm.com/](https://git-scm.com/)

* **检查git版本命令**
```powershell
git --version
# 正确返回示例：git version 2.53.0.windows.1
```

### **3.Windows脚本权限开启命令**
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser 
# 正确返回示例：无
```

* **脚本权限检查命令**
```powershell
Get-ExecutionPolicy -Scope CurrentUser 
# 正确返回示例：RemoteSigned
```

### **4.安装Openclaw命令**
```powershell
iwr -useb https://molt.bot/install.ps1 | iex
```

### **5.配置初始化命令**
```powershell
openclaw onboard
```

## **苹果Mac系统 安装方法**

### **1.安装Apple命令开发工具命令**
```zsh
xcode-select --install
```

### **2.安装Homebrew**
```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
