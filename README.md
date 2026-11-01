# bug-free-train

这个仓库用来存放我自己的 Claude Skills（技能）。

## 什么是 Skill

Skill 是一个文件夹，里面至少有一个 `SKILL.md` 文件，用来告诉 Claude 在什么时候、按什么步骤完成某类任务。
Claude 会根据 `SKILL.md` 开头的 `description` 自动判断什么时候使用它。

## 目录结构

```
skills/
└── 技能名称/
    ├── SKILL.md        # 必需：技能说明
    ├── scripts/        # 可选：脚本
    └── references/     # 可选：参考资料
```

## SKILL.md 格式

```markdown
---
name: my-skill
description: 一句话说明这个技能做什么，以及什么时候应该使用它。
---

# 技能标题

这里写给 Claude 的具体步骤和要求。
```

## 安装方法

- **Claude 网页版 / App**：设置 → 功能（Capabilities）→ Skills，把技能文件夹压缩成 `.zip` 后上传。
- **Claude Code**：把技能文件夹放到项目的 `.claude/skills/` 或个人目录 `~/.claude/skills/` 下。
