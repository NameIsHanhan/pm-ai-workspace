# 🚀 PM AI Workspace — 产品经理 AI 工作空间

> 一个为产品经理量身打造的 AI IDE 工作空间，借助 AI 能力高效完成 PRD 撰写、字段清单整理、前端 Demo 生成和业务分析等日常工作。

## 📖 项目简介

本工作空间围绕产品经理的日常工作流程设计，通过结构化的目录组织和 AI 工作流配置，实现：

- 📝 **PRD 撰写**：从需求分析到规格输出的全流程支持
- 📋 **字段清单整理**：结构化的数据字段管理
- 🎨 **前端 Demo 生成**：快速原型搭建与验证
- 📊 **业务分析**：数据分析、流程推演、影响范围评估

## 📁 项目结构

```
pm-ai-workspace/
├── .trae/                        # AI配置中心（核心）
│   ├── rules/                    # 项目规则
│   ├── skills/                   # AI技能包
│   └── workflows/                # 标准工作流
├── analysis/                     # 业务分析区
│   ├── data-analysis/            # 数据分析
│   ├── process-simulation/       # 流程推演
│   └── scope-analysis/           # 影响范围分析
├── assets/                       # 资源文件库
│   ├── images/                   # 图片素材
│   ├── icons/                    # 图标
│   ├── mockups/                  # 原型图、设计稿
│   └── diagrams/                 # 流程图、架构图
├── context/                      # 项目上下文
├── docs/                         # 参考文档库
│   ├── 01-reference/             # 参考资料
│   └── 02-other-docs/            # 其他文档
├── drafts/                       # 草稿区
│   └── archive/                  # 归档
├── outputs/                      # 最终交付物
│   ├── client-prds/              # 对外交付的PRD
│   ├── presentations/            # 汇报演示材料
│   ├── handoff-docs/             # 交接文档
│   └── archive/                  # 归档
├── prds/                         # 正式PRD输出区
│   └── archive/                  # 归档
├── prompts/                      # 提示词库
├── templates/                    # 模板库
├── AGENT.md                      # 全局知识库
└── README.md                     # 本文件
```

## 🚀 快速开始

### 第一步：了解核心配置

| 文件/目录 | 重要性 | 说明 |
|-----------|--------|------|
| `AGENT.md` | ⭐ 核心 | 全局知识库，AI 的"大脑" |
| `.trae/` | ⭐ 核心 | AI 配置中心，包含规则（Rules）、技能包（Skills）和工作流（Workflows） |
| 其他目录 | 📌 建议 | 按需使用，灵活调整 |

### 第二步：启动工作流

1. 打开 AI IDE（如 Trae、Cursor 等）
2. 加载本工作空间
3. 使用 `.trae/workflows/` 中的工作流开始工作：
   - `1-analyze-requirement.md` → 需求洞察
   - `2-design-solution.md` → 方案架构
   - `3-generate-specs.md` → 规格生成
   - `4-verify-iterate.md` → 验证迭代

### 第三步：开始产出

- 草稿放入 `drafts/`
- 正式 PRD 放入 `prds/`
- 最终交付物放入 `outputs/`

## 📂 文件夹说明

| 文件夹 | 用途 | 必要性 |
|--------|------|--------|
| `.trae/` | AI 配置中心：规则、技能包、工作流 | 强制推荐 |
| `analysis/` | 业务分析：数据分析、流程推演、影响范围 | 建议 |
| `assets/` | 资源管理：图片、图标、原型图、流程图 | 建议 |
| `context/` | 项目上下文：背景信息、目标用户、核心策略 | 建议 |
| `docs/` | 参考文档：行业资料、竞品分析、技术文档 | 建议 |
| `drafts/` | 草稿区：AI 初稿、快速记录、迭代试错 | 建议 |
| `outputs/` | 最终交付：对外 PRD、汇报材料、交接文档 | 建议 |
| `prds/` | 正式 PRD：经过评审的产品需求文档 | 建议 |
| `prompts/` | 提示词库：常用 Prompt、场景化提示词 | 建议 |
| `templates/` | 模板库：PRD 模板、字段清单模板等 | 建议 |

## 💡 使用技巧

### 1. 善用 AI 工作流

按照 **分析 → 设计 → 生成 → 验证** 的四阶段工作流，让 AI 逐步深入理解需求并输出高质量文档。借助 `.trae/skills/` 中的专业技能包（Requirement-Clarifier、Data-Modeler、Edge-Case-Detector），进一步提升每个阶段的输出质量。

### 2. 积累知识库

在 `AGENT.md` 中持续记录项目经验和最佳实践，让 AI 越来越懂你的项目。

### 3. 模板复用

将成功的文档结构沉淀到 `templates/`，提升后续工作效率。

### 4. 版本管理

利用 `archive/` 目录管理历史版本，保持工作区整洁。

### 5. 上下文管理

在 `context/` 中维护项目背景信息，确保 AI 始终理解项目全貌。

---

> 📌 **提示**：本工作空间的结构是灵活的，你可以根据自己的工作习惯和项目特点自由调整。核心是 `.trae/` 配置和 `AGENT.md` 知识库，其他部分按需取用。