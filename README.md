# 高密度信息大图生成专家 Skill

> 9 种视觉风格 × NanoBanana API × 2K/4K 分辨率

将复杂专业知识转化为**超高信息密度**的干货内容，支持**9 种视觉风格**切换。

---

## 🎨 9 种视觉风格

| # | 风格 | 适用场景 |
|---|------|----------|
| 1 | 🧪 坐标蓝图 | 技术参数、专业评测 |
| 2 | 📐 复古波普 | 干货清单、对比表格 |
| 3 | 📁 文件夹 | 系统指南、分类清单 |
| 4 | 🧾 热敏纸 | 步骤清单、时间线 |
| 5 | 📓 复古手帐 | 案例研究、调查分析 |
| 6 | ✏️ 陶土手绘 | 轻松干货、亲和科普 |
| 7 | 💾 酸性复古 | 数码评测、极客内容 |
| 8 | 🎫 剧场票据 | 故事演进、系列指南 |
| 9 | 🖼️ 矢量插图 | PPT 封面、场景插画 |

---

## 📥 安装方式

### 方式 1：Claude Code 直接加载

在 Claude Code 中输入：
```
/load https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md
```

### 方式 2：下载后本地加载

1. 下载文件：
   ```bash
   curl -L https://raw.githubusercontent.com/AAAAAAAJ/infographic-skill/main/high-density-infographic-skill.md -o high-density-infographic-skill.md
   ```

2. 在 Claude Code 中加载：
   ```
   /load ./high-density-infographic-skill.md
   ```

### 方式 3：复制粘贴

1. 打开 [high-density-infographic-skill.md](https://github.com/AAAAAAAJ/infographic-skill/blob/main/high-density-infographic-skill.md)
2. 复制全部内容
3. 在 Claude Code 中创建新技能并粘贴

---

## ⚙️ 配置

### 1. 获取 API Key

访问 [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key) 获取 API Key

### 2. 设置环境变量

在 Claude Code 设置中添加：
```
NANOBANANA_API_KEY=你的 API 密钥
```

---

## 🚀 使用示例

**输入：**
```
主题：咖啡豆选择指南
描述：帮助新手快速分辨不同产地和烘焙度的咖啡豆，避免踩坑
数量：5 张
风格：2（复古波普网格）
分辨率：4K
```

**输出：**
1. AI 生成 5 个主题的内容框架
2. 回复「确认生图」
3. 调用 NanoBanana API 生成 5 张 4K 高清图片

---

## 📋 工作流程

```
步骤 1: 信息采集（主题/描述/数量/风格/分辨率）
    ↓
步骤 2-3: 搜索与提炼（收集数据/筛选价值）
    ↓
步骤 4: 智能拆分（6-7 模块结构）
    ↓
步骤 5: 生成内容框架
    ↓
步骤 6: 用户确认 → 调用 API 生图
```

---

## ✅ 分辨率选择

| 分辨率 | 尺寸 | 适用场景 |
|--------|------|----------|
| 2K | 2048 × 2732 | 社交媒体、快速预览 |
| 4K | 4096 × 5464 | 打印、高清展示、文字细节 |

---

## 📄 许可证

Template by: WaytoAGI

---

**🔗 相关链接：**
- [GitHub 仓库](https://github.com/AAAAAAAJ/infographic-skill)
- [NanoBanana API 文档](https://ai.google.dev/gemini-api/docs/api-key)
