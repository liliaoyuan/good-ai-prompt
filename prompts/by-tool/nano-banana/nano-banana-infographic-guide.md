# 🍌 Nano Banana Pro — Infographic 提示词速成指南

> Gemini → Create images → **Thinking 模式**（不是 Fast）

---

## ⚡ 核心 6 步

```
1. DECOMPOSE  → 拆解成 节点 / 关系 / 标签
2. CHOOSE     → 选择视觉格式（见下表）
3. ASSIGN     → 指定颜色（必须写 #hex）、位置、标签
4. ASSEMBLE   → 填入模板
5. CONSTRAIN  → 渲染文字 < 400 词
6. ITERATE    → 用 Follow-up 指令微调
```

---

## 🗂️ 视觉格式选择

| 你的数据结构 | 用这个格式 |
|-------------|-----------|
| 层级（父→子） | Layered stack 分层堆叠 |
| 中心+周边 | Radial hub-and-spoke 辐射图 |
| 顺序（A→B→C） | Flowchart / Pipeline 流程图 |
| 对比（A vs B） | Split panel 分栏对比 |
| 整体的部件 | Exploded / Isometric 3D 爆炸图 |
| N 个独立项目 | Card grid 卡片网格 |
| 嵌套（层中层） | Nested cubes 嵌套立方体 |
| 时间顺序 | Timeline 时间轴 |

---

## 🎨 5 种风格预设（直接复制粘贴）

### 🌑 Dark Technical
```
STYLE: Dark navy background (#1a1a2e), subtle grid lines, crisp sans-serif typography, glowing accent connection lines, semi-transparent layered elements, professional tech-architecture aesthetic.
```

### ☀️ Light Minimal
```
STYLE: Warm cream background (#f5f0e8), clean minimal design, soft drop shadows, blue (#3498DB) dashed connection lines, rounded corners, modern SaaS documentation aesthetic.
```

### 📘 Blueprint
```
STYLE: Deep blue background (#0a1628), white and cyan line art, monospaced labels, no fills — outlines only, engineering blueprint aesthetic with grid overlay.
```

### 📰 Editorial
```
STYLE: White background (#ffffff), bold serif titles, thin sans-serif body text, muted earth-tone accent colors, generous whitespace, magazine editorial layout.
```

### 🌈 Neon Cyberpunk
```
STYLE: Black background (#0d0d0d), neon cyan (#00f5ff) and magenta (#ff00ff) accents, glowing thin lines, glassmorphism card panels, monospaced coding font labels, cyberpunk schematic aesthetic.
```

---

## 📐 长宽比

| 用途 | 写这个 |
|------|--------|
| 简报/幻灯片 | `16:9 landscape` |
| 社交方图 | `1:1 square` |
| 手机竖屏 | `9:16 portrait` |
| 文档打印 | `4:3` |

---

## 🔄 Follow-up 迭代指令

生成后直接在 Gemini 对话里继续输入：

```bash
# 修文字错误
"Fix the text on [元素] to read exactly '[正确内容]'"

# 改颜色
"Change [元素] color to [#hex], keep everything else"

# 移动位置
"Move [元素] to [位置], keep everything else"

# 添加元素
"Add a [#颜色] [形状] labeled '[名称]' at [位置]"

# 删除元素
"Remove [元素] and enlarge [其他元素] to fill the space"

# 换风格
"Recreate this in [风格名] aesthetic, keep same layout"

# 联网补数据
"Research [话题] and add a small chart showing [指标]"

# 提升分辨率
"Regenerate at maximum resolution 4K, keep identical"
```

---

## ⚠️ 三条铁律

1. **颜色必须写 #hex**，绝对不要写 "blue" "green"
2. **渲染文字 < 400 词**，超了先删副标题
3. **结尾必须加**：`All text must be legible and correctly spelled.`
