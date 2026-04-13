# indie-skills

> 少即是多。给独立创作者的 AI 技能包。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Indie](https://img.shields.io/badge/indie-skills-87CEEB)](https://github.com/rocwood/indie-skills)

每个技能都带着清晰的流程和边界，拿来就能用。

- **精巧** — 一个技能只做一件事，把它做到位
- **实用** — 覆盖创作与工作中真正高频的场景
- **干净** — 没有多余的提示词，没有多余的依赖

---

## 技能列表

| 技能 | 目录名 | 说明 |
|------|--------|------|
| 产品顾问 | `product-advisor` | 帮你理清产品想法，做需求分析和方案评审 |
| 会议总结 | `meeting-summary` | 把会议记录变成清晰的决策、待办和要点 |
| 写作者 | `writer` | 用你喜欢的风格写文章，也能帮你改稿润色 |
| 对话导出 | `chat-export` | 把 AI 对话导出为 Markdown，完整记录或精华摘要 |

> 如无必要，勿增实体。更多技能打磨中，但绝不凑数。

---

## 如何使用

### 1. 命令安装

```bash
npx skills
```

选你想要的技能，一键装好。

### 2. 手动复制

把 `skills/` 里的技能文件夹，复制到对应目录即可：

```
~/.agents/skills/      # 用户目录 — 所有项目都能用
.agents/skills/        # 工程目录 — 只在当前项目生效
```

---

## 仓库结构

```
skills/
  product-advisor/    # 产品顾问
  meeting-summary/    # 会议总结
  writer/             # 写作者
  chat-export/        # 对话导出
```

---

## 许可

[MIT](LICENSE)
