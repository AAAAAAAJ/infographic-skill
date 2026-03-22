# 高密度信息大图生成专家 Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/AAAAAAAJ/infographic-skill)](https://github.com/AAAAAAAJ/infographic-skill/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/AAAAAAAJ/infographic-skill)](https://github.com/AAAAAAAJ/infographic-skill/commits/main)

> 9 种视觉风格 × NanoBanana API × 2K/4K 分辨率 × 5 种比例

将复杂专业知识转化为**超高信息密度**的干货内容，支持**9 种视觉风格**切换。

---

## 🚀 Quick Start

```bash
# OpenClaw 安装（推荐）
/install https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md

# Claude Code 安装
/load https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

---

## 📥 安装方式

| 方式 | 命令 | 适用场景 |
|------|------|----------|
| **OpenClaw** | `/install <url>` | 长期技能，推荐 ⭐ |
| **Claude Code** | `/load <url>` | 临时使用 |
| **本地安装** | `curl -O <url>` + `/load ./file.md` | 离线使用 |

### 详细安装步骤

<details>
<summary>📖 点击展开完整安装指南</summary>

#### 方式 1：OpenClaw 安装（推荐）
```bash
/install https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

#### 方式 2：Claude Code 加载
```bash
/load https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

#### 方式 3：下载本地使用
```bash
# 下载
curl -L https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md -o high-density-infographic-skill.md

# 加载
/load ./high-density-infographic-skill.md
```

#### 方式 4：Git Clone
```bash
git clone https://github.com/AAAAAAAJ/infographic-skill.git
cd infographic-skill
/load ./high-density-infographic-skill.md
```

</details>

---

## ⚙️ 配置

### 1. 获取 API Key
访问 [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key) 获取 API Key

### 2. 设置环境变量
```bash
NANOBANANA_API_KEY=你的 API 密钥
```

### 3. 验证配置
```
输入任意主题，AI 会检测 API Key 状态
未配置时仅提供内容策划服务
```

---

## 🎨 9 种视觉风格

| # | 风格 | 核心特征 | 适用场景 |
|---|------|----------|----------|
| 1 | 🧪 坐标蓝图 | 坐标系统 + 技术网格 | 技术参数、专业评测 |
| 2 | 📐 复古波普 | 瑞士兵网格式 + 粗黑线 | 干货清单、对比表格 |
| 3 | 📁 文件夹 | 3D 文具 + 剪贴板 | 系统指南、分类清单 |
| 4 | 🧾 热敏纸 | 票据穿孔 + 3D 图标 | 步骤清单、时间线 |
| 5 | 📓 复古手帐 | 拼贴证据板 + 图钉 | 案例研究、调查分析 |
| 6 | ✏️ 陶土手绘 | 涂鸦粗轮廓 + 几何形 | 轻松干货、亲和科普 |
| 7 | 💾 酸性复古 | Y2K 像素 + 镭射渐变 | 数码评测、极客内容 |
| 8 | 🎫 剧场票据 | 票根胶片 + 五幕剧 | 故事演进、系列指南 |
| 9 | 🖼️ 矢量插图 | 黑轮廓线稿 + 几何简化 | PPT 封面、场景插画 |

---

## 🚀 使用示例

### 你输入 → AI 输出

| 你说 | AI 执行 |
|------|---------|
| "咖啡豆选择指南" | 生成 6-7 模块内容框架 |
| "风格 2，4K，3:4 比例" | 调用复古波普模板 + 4K 生图 |
| "确认生图" | 调用 NanoBanana API 生成图片 |

### 完整示例

```
用户输入：
主题：咖啡豆选择指南
描述：帮助新手快速分辨不同产地和烘焙度的咖啡豆，避免踩坑
数量：5 张
风格：2（复古波普网格）
分辨率：4K
比例：3:4（默认）

AI 输出：
1. 生成 5 个主题的内容框架（每图 6-7 模块）
2. 等待「确认生图」
3. 调用 API 生成 5 张 4096×5464 高清图片
```

---

## 📊 分辨率与比例

### 分辨率选择
| 分辨率 | 尺寸 | 适用场景 |
|--------|------|----------|
| 2K | 2048 × 2732 | 社交媒体、快速预览 |
| 4K | 4096 × 5464 | 打印、高清展示 |

### 比例选择
| 比例 | 适用场景 |
|------|----------|
| 3:4 | 小红书/手机竖屏（默认） |
| 1:1 | 朋友圈/Instagram |
| 4:3 | PPT/演示文稿 |
| 9:16 | 短视频封面/全屏 |
| 16:9 | 横幅/网站头图 |

---

## 📋 工作流程

```
┌─────────────────────────────────────────────────────────┐
│ 步骤 1: 信息采集（6 项）                                 │
│ 主题 → 描述 → 数量 → 风格 → 分辨率 → 比例               │
└─────────────────────────────────────────────────────────┘
                           ↓
┌─────────────────────────────────────────────────────────┐
│ 步骤 2-3: 搜索与提炼                                     │
│ 收集数据 → 筛选价值（实用/稀缺/共鸣）                    │
└─────────────────────────────────────────────────────────┘
                           ↓
┌─────────────────────────────────────────────────────────┐
│ 步骤 4: 智能拆分（6-7 模块/图）                           │
│ 品牌阵列 → 对比阶梯 → 参数标准 → 识别技巧 → 场景推荐    │
│ → 避坑提醒 → 快速对照                                    │
└─────────────────────────────────────────────────────────┘
                           ↓
┌─────────────────────────────────────────────────────────┐
│ 步骤 5: 生成内容框架                                     │
└─────────────────────────────────────────────────────────┘
                           ↓
┌─────────────────────────────────────────────────────────┐
│ 步骤 6: 用户确认 → 调用 API 生图                         │
└─────────────────────────────────────────────────────────┘
```

---

## 💡 Tips

| 技巧 | 说明 |
|------|------|
| 🎯 模块数量 | 每图固定 6-7 个模块，信息密度优先 |
| 📊 数据支撑 | 每个模块必须有品牌/数值/参数 |
| 🎨 风格选择 | 专业评测用风格 1，干货清单用风格 2 |
| 📱 比例推荐 | 小红书 3:4，朋友圈 1:1，PPT 4:3 |
| ⚡ 快速生成 | 2K 速度快，4K 质量高（推荐） |

---

## 🔒 安全提示

> ⚠️ **重要：** API Key 是敏感信息
> - 不要在公开仓库中存放 API Key
> - 定期检查 API Key 使用情况
> - 发现泄露立即撤销并重新生成

---

## 📚 文档索引

| 文档 | 说明 |
|------|------|
| [Skill 源文件](high-density-infographic-skill.md) | 完整技能定义 |
| [Google AI API](https://ai.google.dev/gemini-api/docs/api-key) | API Key 获取 |
| [GitHub 仓库](https://github.com/AAAAAAAJ/infographic-skill) | 源码与更新 |

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

---

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

---

## 🔗 相关链接

- **GitHub 仓库**: https://github.com/AAAAAAAJ/infographic-skill
- **OpenClaw**: AI 技能管理平台
- **Google AI Studio**: https://ai.google.dev/gemini-api/docs/api-key

---

**Template by:** WaytoAGI | **Version:** v4.0 | **Last Updated:** 2026-03-23

---

# English Version

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/AAAAAAAJ/infographic-skill)](https://github.com/AAAAAAAJ/infographic-skill/stargazers)

> 9 Visual Styles × NanoBanana API × 2K/4K Resolution × 5 Aspect Ratios

Transform complex professional knowledge into **ultra-high information density** content.

---

## 🚀 Quick Start

```bash
# OpenClaw Installation (Recommended)
/install https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md

# Claude Code Installation
/load https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

---

## 📥 Installation

| Method | Command | Best For |
|--------|---------|----------|
| **OpenClaw** | `/install <url>` | Long-term use ⭐ |
| **Claude Code** | `/load <url>` | Temporary use |
| **Local** | `curl -O <url>` + `/load ./file.md` | Offline use |

---

## ⚙️ Configuration

### 1. Get API Key
Visit [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key)

### 2. Set Environment Variable
```
NANOBANANA_API_KEY=your_api_key_here
```

---

## 🎨 9 Visual Styles

| # | Style | Best For |
|---|-------|----------|
| 1 | 🧪 Blueprint Pop Lab | Technical specs, reviews |
| 2 | 📐 Retro Pop Grid | Checklists, comparisons |
| 3 | 📁 Archive Folder | System guides, lists |
| 4 | 🧾 Thermal Receipt | Step lists, timelines |
| 5 | 📓 Vintage Scrapbook | Case studies, analysis |
| 6 | ✏️ Terracotta Doodle | Casual guides, tutorials |
| 7 | 💾 Acid Retro | Tech reviews, geek content |
| 8 | 🎫 Theater Ticket | Story evolution, series |
| 9 | 🖼️ Flat Vector | PPT covers, illustrations |

---

## 📊 Resolution & Aspect Ratio

**Resolution:**
| Resolution | Size | Best For |
|------------|------|----------|
| 2K | 2048 × 2732 | Social media, quick preview |
| 4K | 4096 × 5464 | Print, HD display |

**Aspect Ratio:**
| Ratio | Best For |
|-------|----------|
| 3:4 | Xiaohongshu / Mobile (default) |
| 1:1 | WeChat / Instagram |
| 4:3 | PPT / Presentations |
| 9:16 | Video covers / Full screen |
| 16:9 | Banners / Website headers |

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

---

**Template by:** WaytoAGI | **Version:** v4.0
