# indie-skills

> 给独立创作者的 AI 技能包，每个技能都恰到好处。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Indie Skills](https://img.shields.io/badge/indie-skills-87CEEB)](https://github.com/rocwood/indie-skills)

## 🧰 技能列表

- `chat-export` **对话导出** — 把当前 AI 对话导出为结构化 Markdown，保留完整上下文
- `handoff` **会话交接** — 把当前 AI 会话整理为可交接、可分享的 Markdown 文件
- `meeting-summary` **会议总结** — 从会议文字稿中提炼决策、待办和关键讨论，结论先行
- `coach` **成长教练** — 苏格拉底式提问，不给答案，帮你觉察盲点、理清思路
- `grill-it` **想法拷问** 🧪 — 对想法、产品和方向进行系统追问，澄清核心体验、判断依据、关键假设和验证路径
- `spark-collect` **闪念收集** — 随手捕捉碎片想法，自动归档到当天文档，按需展开深聊
- `knowledge-distill` **认知提炼** 🧪 — 从讨论记录中提取已确认结论，维护到认知知识库

### 已归档（已过时或待优化，不建议使用）

- `writer` **风格写作** — 按指定风格写文章或改稿，支持自定义风格模板


## 🚀 如何使用

### 1. 命令行安装

```bash
npx skills add rocwood/indie-skills
```

### 2. 手动复制

把 `skills/` 里的技能文件夹，复制到对应目录即可：

```
~/.agents/skills/      # 用户目录 — 所有项目都能用
.agents/skills/        # 工程目录 — 只在当前项目生效
```
