# Marx Perspective - Claude Code Skill

以《资本论》为核心的卡尔·马克思思维框架，可作为 Claude Code 的 AI 思维顾问使用。

## 这是什么

本 Skill 蒸馏了马克思的思维操作系统，包括：

- **5 个核心心智模型**：内在批判法、形式分析、商品拜物教批判、现象与本质的辩证法、历史的暂时性
- **7 条决策启发式**：从「细胞形式」开始分析、追问谱系、怀疑一切……
- **完整的表达 DNA**：哥特式讽刺、交错法句式、莎士比亚/但丁/巴尔扎克引用体系
- **Agentic Protocol**：遇到需要事实的问题先 WebSearch 获取真实数据再分析，而非凭训练语料编造

基于《资本论》全三卷、9 部核心著作、30+ 封关键书信、10 个重大决策案例的深度调研。

## 安装

```bash
# 克隆到 Claude Code 的 skills 目录
cd ~/.claude/skills/
git clone https://github.com/Slzx1/marx-perspective.git marx-perspective
```

或者通过 Claude Code 内置 skill 安装：

```
/npx skills add Slzx1/marx-perspective
```

## 使用

在 Claude Code 对话中，直接说以下任意触发词即可激活：

- 「用马克思的视角」「马克思会怎么看」
- 「阶级分析」「异化」「拜物教」
- 「996」「加班文化」「打工」
- 「资本为什么……」「剩余价值怎么看」

也可以直接 `/marx-perspective` 激活。

## 文件结构

```
marx-perspective/
├── SKILL.md                         # Skill 主文件
├── README.md
└── references/research/             # 6 份调研文件（共 282KB）
    ├── 01-writings.md               # 著作与系统思考（52K）
    ├── 02-conversations.md          # 书信与即兴思考（44K）
    ├── 03-expression-dna.md         # 表达风格分析（29K）
    ├── 04-external-views.md         # 外部视角与批评（80K）
    ├── 05-decisions.md              # 决策记录与行动（50K）
    └── 06-timeline.md               # 完整时间线（27K）
```

## 许可

本 Skill 中的调研内容基于马克思原著（已进入公共领域）及学术研究整理。

> 本 Skill 由 [女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 生成
> 创建者：[花叔](https://x.com/AlchainHust)
