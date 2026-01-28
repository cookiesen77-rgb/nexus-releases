# Nexus

<p align="center">
  <img src="https://img.shields.io/badge/version-0.0.10-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey.svg" alt="Platform">
</p>

**Nexus** 是一款强大的 AI 工作流画布应用，让你轻松创建文生图、图生视频等 AI 创作工作流。

---

## 功能特性

- **可视化节点画布** - 拖拽式操作，直观创建工作流
- **文生图工作流** - 支持多种主流 AI 绘图模型
- **图生视频工作流** - 一键将静态图片转为动态视频
- **智能 AI 助手** - 内置对话助手，辅助创作
- **高性能渲染** - GPU/DOM 自动切换，流畅体验
- **本地存储** - 数据保存在本地，隐私安全

---

## 下载安装

### 最新版本: v0.0.10

| 平台 | 下载链接 | 说明 |
|------|----------|------|
| **macOS (Intel)** | [Nexus_0.0.10_x64.dmg](https://github.com/cookiesen77-rgb/nexus-source/releases/download/v0.0.10/Nexus_0.0.10_x64.dmg) | 适用于 Intel 芯片 Mac |
| **macOS (Apple Silicon)** | [Nexus_0.0.10_aarch64.dmg](https://github.com/cookiesen77-rgb/nexus-source/releases/download/v0.0.10/Nexus_0.0.10_aarch64.dmg) | 适用于 M1/M2/M3 芯片 Mac |
| **Windows (EXE)** | [Nexus_0.0.10_x64-setup.exe](https://github.com/cookiesen77-rgb/nexus-source/releases/download/v0.0.10/Nexus_0.0.10_x64-setup.exe) | Windows 安装程序 |
| **Windows (MSI)** | [Nexus_0.0.10_x64_en-US.msi](https://github.com/cookiesen77-rgb/nexus-source/releases/download/v0.0.10/Nexus_0.0.10_x64_en-US.msi) | Windows MSI 安装包 |

[查看所有版本](https://github.com/cookiesen77-rgb/nexus-releases/releases)

---

## 获取 API Key

<p align="center">
  <b>使用 Nexus 需要配置 API Key 才能使用 AI 功能</b>
</p>

<p align="center">
  <a href="https://nexusapi.cn/" target="_blank">
    <img src="https://img.shields.io/badge/获取 API Key-nexusapi.cn-brightgreen?style=for-the-badge" alt="Get API Key">
  </a>
</p>

### 获取步骤：

1. 访问 **[nexusapi.cn](https://nexusapi.cn/)**
2. 注册/登录账号
3. 在控制台获取你的 API Key
4. 打开 Nexus 应用，进入设置页面
5. 粘贴 API Key 并保存

### 为什么选择 nexusapi.cn？

- **稳定可靠** - 高可用 API 服务
- **多模型支持** - GPT、Gemini、DALL·E、Midjourney 等
- **价格实惠** - 按量计费，无月费
- **中文优化** - 针对中文场景优化

[查看价格方案](https://nexusapi.cn/pricing)

---

## 系统要求

### macOS
- macOS 10.15 (Catalina) 或更高版本
- Intel 或 Apple Silicon 处理器

### Windows
- Windows 10 (1803) 或更高版本
- x64 处理器

---

## 应用截图

### AI 助手与工作流画布

<p align="center">
  <img src="screenshots/ai-assistant.png" alt="AI 助手" width="100%">
</p>

<p align="center">
  <i>智能 AI 助手，自动执行工作流创建</i>
</p>

### 完整工作流示例

<p align="center">
  <img src="screenshots/workflow-canvas.png" alt="工作流画布" width="100%">
</p>

<p align="center">
  <i>可视化节点画布，从文生图到图生视频的完整工作流</i>
</p>

---

## 更新日志

### v0.0.10
- **新增工作流模板** - 漫画分镜、多角度分镜模板
- **新增导演台** - AI 智能生成分镜脚本
- **新增草图编辑器** - 涂鸦生图/生视频
- **新增音频工作室** - Suno 文生音乐
- **新增提示词库** - 运镜/Nano Banana/漫画模板

### v0.0.9
- 新增提示词库功能
- 修复侧边栏按钮状态

### v0.0.8
- 修复应用启动崩溃问题
- 优化构建流程

### v0.0.7
- 修复批量下载和历史面板功能
- 修复 Tauri 环境中的图片/视频生成问题

### v0.0.6
- **修复桌面端无法生成图片/视频的问题** (load failed)
- 使用 Tauri HTTP 插件绕过 CORS 限制

### v0.0.5
- 默认切换为浅色主题
- 项目独立聊天记录
- 修复模型选择不一致的 bug
- 移除 Base URL 配置项
- 添加 GitHub Actions 自动构建
- 支持 macOS (Intel/ARM) 和 Windows

---

## 许可证

本软件仅供个人使用。

---

## 相关链接

| 链接 | 说明 |
|------|------|
| [nexusapi.cn](https://nexusapi.cn/) | API 服务官网 |
| [价格方案](https://nexusapi.cn/pricing) | 查看定价 |

---

<p align="center">
  <b>Powered by <a href="https://nexusapi.cn/">nexusapi.cn</a></b>
</p>
