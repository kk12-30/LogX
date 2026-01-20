
<p align="center">
   <img src="https://img.cdn1.vip/i/696f9035aca11_1768919093.jpeg" alt="LogX Logo" width="200"> 
  <h1 align="center">LogX</h1>
</p>

<p align="center">
  <strong>🚀 基于 Go + Wails + Vue 3 的现代化日志分析与威胁检测平台</strong>
</p>

<p align="center">
  <a href="https://github.com/kk12-30/LogX">
    <img src="https://img.shields.io/github/stars/kk12-30/LogX?style=flat-square" alt="GitHub Stars">
  </a>
  <a href="https://github.com/kk12-30/LogX/forks">
    <img src="https://img.shields.io/github/forks/kk12-30/LogX?style=flat-square" alt="GitHub Forks">
  </a>
  <a href="https://github.com/kk12-30/LogX/issues">
    <img src="https://img.shields.io/github/issues/kk12-30/LogX?style=flat-square" alt="GitHub Issues">
  </a>
</p>

<p align="center">
  <a href="#特性">特性</a> •
  <a href="#安装">安装</a> •
  <a href="#使用">使用</a> •
  <a href="#开发">开发</a> •
  <a href="#技术栈">技术栈</a>
</p>

> **公众号：蓝剑安全** | 关注获取更多安全工具与技术分享

---

## ✨ 项目简介

**LogX** 是一款专为应急响应和安全分析设计的现代化桌面应用。它结合了 Go 语言的高性能解析能力和 Vue 3 的交互式可视化体验，能够快速处理百万级 Web 日志，自动识别 SQL 注入、XSS、WebShell 等常见攻击，并提供直观的攻击溯源和地理定位功能。

## 🔥 核心特性

### 🔍 极速日志解析
- **多格式支持**：自动识别 Apache、Nginx、IIS、JSON 等常见日志格式。
- **高性能引擎**：基于 Go 并发处理，秒级解析百万条日志记录。
- **自定义格式**：支持正则表达式自定义解析规则，适应各种非标日志。

### 🛡️ 智能威胁检测
内置强大的检测规则库，自动识别各类 Web 攻击：
- **高危攻击**：SQL 注入、XSS 跨站脚本、命令执行 (RCE)。
- **WebShell**：自动检测菜刀、蚁剑、冰蝎等连接特征。
- **扫描器识别**：识别 Nmap、SQLMap、DirBuster 等扫描器指纹。
- **漏洞利用**：Log4j2、Fastjson、Struts2 等常见漏洞利用尝试。
- **AI 辅助**：集成 AI 助手，对疑难日志进行深度分析和解释。

### 📊 可视化分析
- **攻击大屏**：实时展示攻击态势、威胁等级分布和 Top 攻击源。
- **路径分析树**：独创的树状视图，快速梳理网站目录结构和访问热度。
- **地理溯源**：基于 ECharts 的 3D/2D 地球视图，精准定位攻击者物理位置。
- **交互式图表**：支持多维度的流量趋势、状态码分布和 UA 分析。

### ⚡ 高效交互体验
- **虚拟滚动**：流畅浏览海量日志数据，无卡顿。
- **多维过滤**：支持 IP、时间、状态码、攻击类型等组合筛选。
- **会话追踪**：自动关联攻击者的完整会话轨迹。


## 📄 许可证

本项目采用 MIT 许可证。

---

<p align="center">
  <strong>LogX</strong> 由 <a href="https://github.com/kk12-30">kk12-30</a> 开发维护
  <br>
  关注公众号 <strong>蓝剑安全</strong> 获取最新更新
</p>
