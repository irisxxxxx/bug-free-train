# bug-free-train

我的 Claude 技能（Skills）仓库：存放已安装技能的原始文件和安装包。

## 已安装的技能

### 写作与论文

| 技能 | 用途 | 怎么说 |
|---|---|---|
| anti-defensive-writing | 论文写作：围绕核心贡献组织叙事，去掉“心虚”的写法 | “帮我改这段摘要 / 引言 / 结论”“回复审稿意见” |
| humanizer-zh | 中文去 AI 腔：去掉空话、套话、模板化表达，保留事实和作者语气 | “用 humanizer-zh 润色这段” |
| humanizer | 英文去 AI 腔（温和版） | “用 humanizer 改一下这段英文” |
| stop-slop | 去 AI 腔（严格版），改得更干脆 | “用 stop-slop 改这段” |
| grill-me | 追问你的计划，逐个问题理清思路 | “grill me，我想写一篇关于……的论文” |

### 营销与传媒

| 技能 | 用途 | 怎么说 |
|---|---|---|
| media-marketing-kit（营销传媒工具箱） | 小红书/抖音内容、文案、短视频、达人合作、公关、品牌案例拆解、竞品与用户研究、营销心理学 | “写一篇小红书笔记”“用营销大师的理论分析××品牌” |

### 演示文稿

| 技能 | 用途 | 怎么说 |
|---|---|---|
| frontend-slides | 设计感强、带动画的网页版演示（.html，浏览器放映） | “用 frontend-slides 做一个关于××的演示” |
| pptx（Claude 自带） | 可编辑的 PowerPoint 文件（.pptx） | “帮我做一份 10 页的 PPT” |

### 写代码（不写代码可在技能列表里关掉）

| 技能 | 用途 |
|---|---|
| ponytail 系列（6 个） | 用最少的代码解决问题、代码审查 |

## 常用组合

- **写论文**：grill-me 理清研究思路 → anti-defensive-writing 写和改 → humanizer-zh 最后去 AI 腔
- **课堂汇报**：营销传媒工具箱 做案例分析 → frontend-slides 或 pptx 做演示
- **发小红书 / 抖音**：营销传媒工具箱 写内容 → humanizer-zh 润色

## 文件位置

- `.claude/skills/`：各技能原始文件（在 Claude Code 中打开本仓库时自动可用）
- `kits/`：整合后的技能源文件（营销传媒工具箱）
- `zips/`：上传到 Claude 网页版 / App 用的安装包（自定义 → 技能 → + → 创建技能 → 上传技能）

## 来源（均为 MIT 许可）

- ponytail — DietrichGebert/ponytail
- humanizer — blader/humanizer
- humanizer-zh — op7418/Humanizer-zh
- stop-slop — hardikpandya/stop-slop
- marketingskills（营销传媒工具箱的来源）— coreyhaines31/marketingskills
- frontend-slides — zarazhangrui/frontend-slides
- anti-defensive-writing — Adkid-Zephyr/anti-defensive-writing-Skill（简介已缩短以适配 200 字限制）
- grill-me — RobMitt/grill-me-skill（无许可文件，未收录在本仓库，仅本地安装）
