# 高密度信息大图生成专家 Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/AAAAAAAJ/infographic-skill)](https://github.com/AAAAAAAJ/infographic-skill/stargazers)

> 10 种视觉风格 × NanoBanana API × 2K/4K 分辨率 × 5 种比例（也可以自己定义比例）
> Wan2.7 也适配，需要写完整需要呈现的文字 https://canary-create.wan.video/

---

## 🚀 Quick Start

```bash
/install https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

---

## 🎨 10 种视觉风格

```
┌─────────────────────────────────────────────────────────────────┐
│  1️⃣ 🧪 坐标蓝图  │  2️⃣ 📐 复古波普  │  3️⃣ 📁 文件夹       │
│  坐标 + 技术网格   │  瑞士网格 + 粗线   │  3D 文具 + 剪贴板     │
├─────────────────────────────────────────────────────────────────┤
│  4️⃣ 🧾 热敏纸  │  5️⃣ 📓 复古手帐  │  6️⃣ ✏️ 陶土手绘     │
│  票据穿孔 +3D 图标  │  拼贴证据板 + 图钉  │  涂鸦粗轮廓 + 几何    │
├─────────────────────────────────────────────────────────────────┤
│  7️⃣ 💾 酸性复古  │  8️⃣ 🎫 剧场票据  │  9️⃣ 🖼️ 矢量插图    │
│  Y2K 像素 + 镭射   │  票根胶片 + 五幕剧  │  黑轮廓线稿 + 几何    │
├─────────────────────────────────────────────────────────────────┤
│  1️⃣0️⃣ 🎨 孟菲斯网格                                           │
│  可见网格 + 模块色块 + 抽象几何                                 │
└─────────────────────────────────────────────────────────────────┘
```

**速记:** 1 蓝 2 格 3 文件 4 票据 5 手帐 6 涂鸦 7 酸 8 剧 9 矢量 10 孟菲斯

⏺ <table>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/7a1ea515-c3ac-4fba-acef-94c4d42d72ed" width="200"/></td>
      <td><img src="https://github.com/user-attachments/assets/fa9806c9-839f-4aea-bd5b-186dd165a7a3" width="200"/></td>
      <td><img src="https://github.com/user-attachments/assets/2a9971fd-eaf0-4260-b59e-fb4cbb735775" width="200"/></td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/4e553826-19a8-4b73-9c8a-c21732d1ce1d" width="200"/></td>
      <td><img src="https://github.com/user-attachments/assets/72b0967c-36e6-43cd-80fd-727b6aae855b" width="200"/></td>
      <td><img src="https://github.com/user-attachments/assets/52196436-657f-4f29-bb9c-0a7ba6495226" width="200"/></td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/d6a41a94-d84e-4220-ac93-0826806755ef" width="200"/></td>
      <td><img src="https://github.com/user-attachments/assets/9ae63c31-6536-4f1a-b1df-a116656590a2" width="200"/></td>
      <td><img src="https://github.com/user-attachments/assets/f1436346-9e39-48a5-bbd8-ad488346fbc3" width="200"/></td>
    </tr>
  </table>


---

## 📊 分辨率 × 比例

```
        ┌──────────────┬──────────────┐
        │     2K       │     4K ⭐     │
        ├──────────────┼──────────────┤
  3:4   │ 2048×2732    │ 4096×5464    │
  1:1   │ 2048×2048    │ 4096×4096    │
  4:3   │ 2732×2048    │ 5464×4096    │
  9:16  │ 2048×3640    │ 4096×7280    │
  16:9  │ 3640×2048    │ 7280×4096    │
        └──────────────┴──────────────┘
```

---

## 🔄 工作流程

```
     ┌─────┐      ┌───────┐      ┌─────┐
     │ 主题 │ ────→│ 搜索  │ ────→│ 提炼 │
     └─────┘      └───────┘      └─────┘
                                        │
     ┌─────┐      ┌───────┐      ┌─────┤
     │ 生图 │ ←────← 确认  │ ←────┤ 拆分 │
     └─────┘            └───────┘      └─────┘
```

---

## 📥 安装方式

```
┌────────────────────────────────────────────────────┐
│                                                    │
│  OpenClaw   →  /install <url>   (推荐 ⭐)          │
│                      ↓                             │
│  Claude Code →  /load <url>     (临时)            │
│                      ↓                             │
│  本地安装   →  curl + /load     (离线)            │
│                                                    │
└────────────────────────────────────────────────────┘
```

---

## ⚙️ 配置

```
1️⃣ 获取 API Key
   └─→ https://ai.google.dev/gemini-api/docs/api-key

2️⃣ 设置环境变量
   └─→ NANOBANANA_API_KEY=你的密钥
```

---

## 💡 使用示例

```
输入：
┌─────────────────────────────────────┐
│ 主题  → 咖啡豆选择指南               │
│ 描述  → 新手分辨产地和烘焙度          │
│ 数量  → 5 张                         │
│ 风格  → 2 (复古波普)                 │
│ 分辨率 → 4K                         │
│ 比例  → 3:4                        │
└─────────────────────────────────────┘

输出：
┌─────────────────────────────────────┐
│  ① 生成 5 个内容框架 (每图 6-7 模块)    │
│           ↓                         │
│  ② 等待「确认生图」                  │
│           ↓                         │
│  ③ 生成 5 张 4K 高清图 (3:4)           │
└─────────────────────────────────────┘
```

---

## 🎯 模块结构

```
每张图片 = 6-7 个模块

┌──────────┬──────────┬──────────┐
│ 品牌阵列 │ 对比阶梯 │ 参数标准 │
├──────────┼──────────┼──────────┤
│ 识别技巧 │ 场景推荐 │ 避坑提醒 │
├──────────┴──────────┼──────────┤
│    快速对照 (总结)   │          │
└─────────────────────┴──────────┘
```

---

## 🔒 安全提示

```
⚠️ API Key = 敏感信息

❌ 不要存放在公开仓库
✅ 定期检查使用情况
🔄 发现泄露立即撤销
```

---

## 🤝 贡献

```
Fork → Branch → Commit → Push → PR
```

---

## 📄 License

MIT License - 详见 [LICENSE](LICENSE)

---

**v4.0** | Template by WaytoAGI | 2026-03-23

---
---

# English Version

> 9 Styles × NanoBanana API × 2K/4K × 5 Ratios

---

## 🚀 Quick Start

```bash
/install https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

---

## 🎨 10 Visual Styles

```
┌────────────────────────────────────────────────┐
│ 🧪 Blueprint │ 📐 Retro Pop │ 📁 Folder       │
├────────────────────────────────────────────────┤
│ 🧾 Receipt   │ 📓 Scrapbook │ ✏️ Doodle       │
├────────────────────────────────────────────────┤
│ 💾 Acid      │ 🎫 Theater   │ 🖼️ Vector       │
├────────────────────────────────────────────────┤
│ 🎨 Memphis   │              │                 │
└────────────────────────────────────────────────┘
```

---

## 📊 Resolution × Ratio

```
        2K          4K⭐
  3:4  2048×2732   4096×5464
  1:1  2048×2048   4096×4096
  4:3  2732×2048   5464×4096
```

---

## 🔄 Workflow

```
Input → Search → Extract → Split → Generate → Confirm → Image
```

---

## ⚙️ Configuration

```
1. Get API Key → ai.google.dev/gemini-api
2. Set NANOBANANA_API_KEY
```
## How to Use This Skill (APIMart Image Generation)
//gemini-3.1-flash-image-preview: only cost $0.0250 for 0.5K, $0.025 for 1K, $0.0300 for 2K, $0.0400 for 4K

Step 1 — Get Your API Key

First, register an account on APIMart and obtain your API key:

https://apimart.ai/?sourceChannel=waytoagi

After logging in, create an API key and copy it for later use.

Step 2 — Provide API Information to OpenClaw

Your APIMart API key=“your key number”

API Documentation https://docs.apimart.ai/en/api-reference/images/gemini-3.1-flash/generation

The model name: gemini-3.1-flash-image-preview

```
Links
GitHub: https://github.com/AAAAAAAJ/slides
```

---

## 📄 License

MIT License - see [LICENSE](LICENSE)

---

**v4.0** | WaytoAGI | 2026-03-23
