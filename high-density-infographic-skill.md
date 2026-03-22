# Skill: 高密度信息大图生成专家

**版本:** v4.0
**作者:** WaytoAGI
**功能:** 9 种视觉风格 × NanoBanana API × 2K/4K 分辨率信息图生成

---

## 🎯 技能描述

将复杂专业知识转化为**超高信息密度**的干货内容，支持**9 种视觉风格**切换，调用**NanoBanana API**生成 2K/4K 高清图片。

---

## 🔧 配置检查

### 环境变量
```
NANOBANANA_API_KEY - NanoBanana API 密钥
```

### API 获取
未配置时引导用户访问：https://ai.google.dev/gemini-api/docs/api-key

### 状态逻辑
| 状态 | 行为 |
|------|------|
| ✅ API 已配置 | 执行完整流程：内容策划 → 用户确认 → API 生图 |
| ⚠️ API 未配置 | 仅内容策划，输出框架 + 配置指引 |

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

**速记口诀:** 1 蓝 2 格 3 文件 4 票据 5 手帐 6 涂鸦 7 酸 8 剧 9 矢量

---

## 📋 工作流程

```
┌─────────────────────────────────────────────────────────┐
│ 步骤 1: 信息采集 → 步骤 2: 搜索 → 步骤 3: 提炼           │
│      ↓                                                   │
│ 步骤 4: 拆分 → 步骤 5: 生成框架 → 步骤 6: 确认 → 生图    │
└─────────────────────────────────────────────────────────┘
```

### 步骤 1: 启动询问

**必须收集 5 项信息:**

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📝 高密度信息图生成需求表
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
1️⃣ 主题：你想要制作的干货主题是什么？
2️⃣ 描述：用 1-2 句话说明核心要点或目标受众
3️⃣ 数量：希望生成多少张图片？（3-10 张）
4️⃣ 风格：选择一种风格（输入编号 1-9）
   1 坐标蓝图 | 2 复古波普 | 3 文件夹 | 4 热敏纸
   5 复古手帐 | 6 陶土手绘 | 7 酸性复古 | 8 剧场 | 9 矢量
5️⃣ 分辨率:
   2K - 快速生成（默认）
   4K - 最佳质量（推荐 ⭐）
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### 步骤 2-3: 搜索与提炼

**数据收集重点:**
- 价格区间、技术参数、使用寿命
- 百分比数据、品牌推荐、技术指标

**价值筛选三标准:**
- ✅ 实用性强：用户可直接执行
- ✅ 稀缺性高：非泛泛而谈
- ✅ 引发共鸣：戳中痛点

### 步骤 4: 智能拆分

**标准模块结构（每图 6-7 模块）:**

```
图片 X → [主题名称]
├─ 模块 1:品牌阵列（3-6 个选项/等级）
├─ 模块 2:对比阶梯（场景/优劣）
├─ 模块 3:参数标准（数值/规格）
├─ 模块 4:识别技巧（方法/步骤）
├─ 模块 5:场景推荐（适用性）
├─ 模块 6:避坑提醒（警告/禁忌）
└─ 模块 7:快速对照（总结/检查表）
```

### 步骤 5: 生成内容框架

**输出格式:**

```markdown
## 图片 [X]:[主题名称]

**主标题**:[主题] 选择指南 / 避坑攻略
**副标题**:X 大维度全面解析

### 模块内容
**[模块 1] 品牌阵列**
- 品牌 A:价格/参数/特点
- 品牌 B:价格/参数/特点

**[模块 2] 对比阶梯**
- 高端:XXX 元，特点...
- 中端:XXX 元，特点...
- 入门:XXX 元，特点...

...（6-7 个模块完整展开）
```

### 步骤 6: 用户确认与生图

**等待用户回复「确认生图」后执行:**

#### 6.1 API 状态检查
```
IF NANOBANANA_API_KEY 未配置:
    → 输出提示 + 已生成的内容框架
    → 引导配置 API Key
ELSE:
    → 进入生图流程
```

#### 6.2 生图参数配置

| 参数 | 值 |
|------|-----|
| 模型 | `nano-banana-2` |
| 2K 分辨率 | 2048 × 2732 |
| 4K 分辨率 | 4096 × 5464 |
| 宽高比 | 3:4 |
| 格式 | PNG |

#### 6.3 调用对应风格 Prompt
根据用户选择的风格编号，调用下方 **Prompt 模板库** 中的对应模板。

---

## 🎨 Prompt 模板库

### 模板 01: 坐标蓝图·波普实验室

```
Create a high-density professional information design infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Laboratory manual + Blueprint coordinate system
【MOOD】Precision, Technical, Data-driven

【COLOR PALETTE】
- Background: Grayish-white grid (#F2F2F2)
- Primary: Muted Teal/Sage Green (#B8D8BE)
- Alert: Fluorescent Pink (#E91E63)
- Highlight: Lemon Yellow (#FFF200)
- Lines: Charcoal Brown (#2D2926)

【LAYOUT】
- Coordinate labels on every module (R-20, G-02, SEC-08)
- 6-7 distinct modules packed tightly
- Technical rulers with markers (0.5mm, 1.8mm, 45°)
- Metadata: barcodes, timestamps, parameters

【ELEMENTS】
- Exploded views, cross-sections
- Mathematical symbols (Σ, Δ, ∞)
- Cross-hair targets, X/Y axis arrows
- "Marker-over-Print" offset effect

【TYPOGRAPHY】
- Headers: Bold Brutalist Chinese
- Body: Technical sans-serif
- Numbers: Large, color-highlighted

【AVOID】
❌ Doodles ❌ Soft pastels ❌ White space ❌ Generic icons

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 02: 复古波普网格

```
Create a flat graphic design infographic poster about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】1970s Retro Pop Art + Swiss Grid System
【MOOD】Orderly, Bold, Graphic

【COLOR PALETTE】
- Background: Vintage cream (#F5F0E6)
- Accents: Salmon pink, Sky blue, Mustard yellow, Mint green
- Contrast: Pure Black (#000000) + White (#FFFFFF)
- Outlines: Thick solid black

【LAYOUT】
- Strict Swiss grid: square/rectangular cells
- 6-7 modules in separate cells
- Thick black line dividers
- Warning module: White text on Black background

【ELEMENTS】
- Quirky geometric product icons
- Vintage comic faces (😊✓ 😐 ☹️✗)
- Checkerboards, diagonal line patterns
- Flat abstract symbols

【TYPOGRAPHY】
- Headers: Bold retro display fonts
- Body: Clean sans-serif (Chinese)
- Decorative: English "WARNING", "INFO"

【AVOID】
❌ 3D ❌ Gradients ❌ Thin lines ❌ Floating layouts ❌ White canvas

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 03: 文件夹/档案风

```
Create a stationery-style 3D infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Neo-skeuomorphism + File folder organization
【MOOD】Clean, Professional, Organized

【COLOR PALETTE】
- Background: Cream/Beige (#F5F5DC)
- Primary: Klein Blue
- Accent: Vibrant Orange
- Text: Soft Grey + Deep Black

【LAYOUT】
- Vertical clipboard composition
- Layered folders with index tabs
- List documents inside folders
- 3D metal clip at top

【ELEMENTS】
- 3D metal clipboard clip
- Layered folder tabs with labels
- Index navigation tags
- 3D mouse cursor, notification icons
- Subtle drop shadows for depth

【TYPOGRAPHY】
- Headers: Large bold sans-serif
- Body: Clean organized lists
- Tab labels: Compact uppercase

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 04: 热敏纸/票据风

```
Create a high-density receipt-style infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Modern ticket/receipt + Perforated edges
【MOOD】Sequential, Functional, Tactile

【COLOR PALETTE】
- Border: Bright Cyan (#00AEEF) or Mustard (#FFD100)
- Paper: Off-white (#F9F9F9) with texture
- Text: Dark charcoal
- Highlight: Border color as marker

【LAYOUT】
- Vertical receipt flow
- Perforated edge details
- 3D dispenser header
- Sequential numbered sections

【ELEMENTS】
- 3D/Claymorphism section icons
- Hand-drawn checkboxes ✓
- Highlighter circles around keywords
- Pixel font header "{ }"
- Small English subtext layer

【TYPOGRAPHY】
- Header: Retro digital/pixel font
- Title: Bold modern sans-serif
- Body: Light sans-serif

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 05: 复古手帐风

```
Create a vintage scrapbook-style infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Mixed-media archival + Evidence board
【MOOD】Investigative, Layered, Analog

【COLOR PALETTE】
- Base: Cream, Kraft brown, Off-white
- Type: Deep Black + Navy Blue
- Accents: Vibrant Green + Red
- Tape: Soft Yellow

【LAYOUT】
- Collage composition with overlap
- "Pinned" element illusion
- Marginalia side-notes
- Clipboard or corkboard base

【ELEMENTS】
- Torn paper edges
- Halftone dot patterns
- Paper clips, push pins, tape
- Polaroid-style photo frames
- Hand-drawn arrows, dashed lines

【TYPOGRAPHY】
- Headers: Bold sans-serif
- Data: Typewriter monospace
- Notes: Script/handwriting style

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 06: 陶土手绘风

```
Create a hand-drawn doodle-style infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Organic hand-drawn + Imperfect lines
【MOOD】Friendly, Approachable, Playful

【COLOR PALETTE】
- Dominant: Terracotta/Rust Orange
- Contrast: Charcoal Black (#2D2926)
- Background: Off-White/Cream
- Dots: Light blue + Soft pink

【LAYOUT】
- Hand-drawn module dividers
- Color block sections
- Imperfect organic shapes
- Wavy decorative borders

【ELEMENTS】
- Geometric shapes (circles, triangles, stars)
- Squiggly decorative lines
- Simple hand icons
- Dot pattern textures
- Intentionally imperfect lines

【TYPOGRAPHY】
- Headers: Friendly rounded sans-serif
- Body: Clean legible text
- Emphasis: Hand-lettered feel

【AVOID】
❌ Straight lines ❌ Gradients ❌ 3D ❌ Cold colors

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 07: 色块/酸性复古

```
Create a Y2K retro-futurist infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Y2K Tech-Nostalgia + Acid Graphics
【MOOD】Edgy, Digital, Cyber

【COLOR PALETTE】
- Background: Dark Charcoal (#1A1A1A) with grain
- Accents: Cyber Yellow, Electric Orange, Neon Green
- Metallic: Silver/Chrome
- Effects: Rainbow gradients

【LAYOUT】
- Asymmetric modular grid
- Heavy layering
- Sticker-style labels
- Pixel art insertions

【ELEMENTS】
- Vintage tech (Old Mac, CD-ROM, floppy)
- Pixel icons
- Holographic gradient accents
- Sticker borders
- Heavy grain texture overlay

【TYPOGRAPHY】
- Headers: Bold heavy sans-serif
- Data: Monospace/terminal font
- Labels: Sticker-style

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 08: 剧场票据风

```
Create a theater-ticket style infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Vintage tickets + Film noir collage
【MOOD】Dramatic, Sequential, Cinematic

【COLOR PALETTE】
- Background: Deep Navy or Dark Charcoal (grain)
- Tickets: Teal, Canary Yellow, Coral Pink, Mint Green
- Metal: Silver clips/staples
- Text: White on dark (high contrast)

【LAYOUT】
- Overlapping ticket stack
- Jagged ticket edges
- Film strip borders
- "Act 01, Act 02" side labels

【ELEMENTS】
- Vintage theater tickets
- Metal paper clips
- Film sprocket holes
- Script/cast list pages
- Grainy film texture

【TYPOGRAPHY】
- Titles: Bold Serif
- Body: Monospaced typewriter
- Labels: All-caps block

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

### 模板 09: 矢量插图风

```
Create a flat vector illustration infographic about「[主题名称]」.

=== STYLE REQUIREMENTS ===
【AESTHETIC】Flat monoline vector + Geometric simplification
【MOOD】Clean, Friendly, Educational

【COLOR PALETTE】
- Background: Cream/Off-white paper texture
- Accents: Coral Red, Mint Green, Mustard Yellow, Burnt Orange, Rock Blue

【LAYOUT】
- Panoramic horizontal band (top 1/3)
- 2.5D layered perspective
- Equal clarity all layers (no atmospheric fade)

【LINE WORK】
- Uniform black monoline stroke
- Rounded line ends
- Closed outlines for all objects
- No sharp angles

【ELEMENTS】
- Geometric simplification:
  - Trees: Lollipop/triangle shapes
  - Buildings: Simple rectangles
  - Windows: Small square grids
  - Clouds: Pill/capsule shapes
- Radiating lines (sunlight)
- Simple dots and stars

【TYPOGRAPHY】
- Title: Huge bold Retro Serif
- Subtitle: All-caps Sans in colored block
- Body: Clean modern Sans-serif

Aspect Ratio: 3:4
Resolution: [2048x2732 | 4096x5464]
```

---

## ✅ 质量检查清单

**内容层:**
- [ ] 6-7 个子模块完整
- [ ] 每个模块有具体数据/品牌/参数
- [ ] 模块命名统一（4 字格式）

**视觉层:**
- [ ] Prompt 包含风格限制词
- [ ] 配色符合选定规范
- [ ] 禁止事项明确声明
- [ ] 纵横比 3:4

**技术层:**
- [ ] API Key 有效
- [ ] 分辨率确认（2K/4K）
- [ ] 模型：nano-banana-2

---

## 🚀 使用示例

### 场景 A: API 已配置（完整流程）

```
用户：主题：咖啡豆选择
     描述：新手快速分辨产地和烘焙度，避免踩坑
     数量：5 张
     风格：2
     分辨率：4K

AI → 步骤 1-5：生成 5 个主题的内容框架
     → 等待「确认生图」
     → 调用模板 02 + 4096x5464 参数
     → 输出 5 张高清图片
```

### 场景 B: API 未配置（内容模式）

```
用户：（同上输入）

AI → 步骤 1-5：生成完整内容框架
     → ⚠️ 提示：
        "检测到未配置 NanoBanana API Key
         请访问 https://ai.google.dev/gemini-api/docs/api-key 获取
         配置后可直接生图"
     → 输出内容框架（可手动生图）
```

---

## 📎 附录：分辨率选择建议

| 分辨率 | 尺寸 | 适用场景 | 生成速度 |
| --- | --- | --- | --- |
| 2K | 2048 × 2732 | 社交媒体、快速预览 | 快 |
| 4K | 4096 × 5464 | 打印、高清展示、文字细节 | 较慢 |

---

**版本:** v4.0
**Template by:** WaytoAGI
