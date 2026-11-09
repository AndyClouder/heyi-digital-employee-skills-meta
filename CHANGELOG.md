# CHANGELOG

## v2.2

- 新增可选 `SKILLS_INDEX.md` 空模板（技能清单表） — 学员独立包（2026-11-09）

面向合一线学员的可独立交付形态。方法论（五件套、九块、五条件、风险 A–E、版本阶梯）保持不变；去掉对个人 Obsidian 知识库的默认前提。

### 新增

- `README.md`：产品介绍、受众、五件套关系、快速开始、与本体建模的关系
- `学员手册.md`：练习路径、风险与版本说明、常见坑、自检清单
- 本 `CHANGELOG.md`

### 改写

- `安装说明.md`：多工具通用安装；以当前工作区 skills 根目录为准；刷新/重启按所用工具；双目录同步改为可选询问
- `Skill生成/SKILL.md`：落盘与索引改为工作区约定；去掉默认 `.agents` 镜像假设
- `Skill测试/SKILL.md`：技能中心索引改为可选索引表表述
- `Skill迭代/SKILL.md`：镜像与索引改为可选、先问再同步
- `Skill治理/SKILL.md`：巡检范围改为用户指定的 skills 根目录；`00.技能中心` 改为可选索引；去掉「知识库馆长 / 知识库巡检助手」具名依赖，改为泛化表述

### 未改

- 各 skill 的 frontmatter `name`（`skill-builder` / `skill-tester` / `skill-iterator` / `skill-governor` / `prompt-generator`）
- `references/` 下模板与方法论正文（无知识库硬依赖）

## v2.1 — 2026-07-05

元技能五件套 + 提示词生成原版（面向知识库 `.claude/skills` / `.agents/skills` 安装）。

- 交付目录命名为「合一AI数字员工Skills构建元技能」；各 SKILL.md 正文标题统一为 v2.2。
