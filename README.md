# Codex 学习资料导航（四文件阅读版）

本仓库包含 4 份入门到进阶的 Codex 教程文档，覆盖：
- Codex 基础认知与使用流程
- Prompt / Agent / Skill 核心概念
- Windows / macOS / VS Code 配置实践
- Skill 的创建、调用与团队落地

## 文档清单

1. [codex_tutorial.md](https://github.com/HTY679/dachuang/blob/main/codex_tutorial.md)  
   适合先读，建立整体认知：Codex 是什么、怎么提需求、怎么迭代、常见问题与团队协作方式。

2. [prompt_agent_skill_tutorial.md](https://github.com/HTY679/dachuang/blob/main/prompt_agent_skill_tutorial.md)  
   重点解释 Prompt、Agent、Skill 的区别与关系，并给出项目场景下可直接复用的写法。

3. [codex_setup_tutorial.md](https://github.com/HTY679/dachuang/blob/main/codex_setup_tutorial.md)  
   实操配置指南：Windows/macOS、VS Code 插件、WSL 建议路径、首次任务建议。

4. [codex_skill_tutorial.md](https://github.com/HTY679/dachuang/blob/main/codex_skill_tutorial.md)  
   Skill 专题：如何创建 Skill、如何调用、推荐的 5 类高频 Skill、常见误区。

## 推荐阅读顺序

1. `codex_tutorial.md`（先建立全局框架）  
2. `prompt_agent_skill_tutorial.md`（理解核心方法论）  
3. `codex_setup_tutorial.md`（完成本地环境配置）  
4. `codex_skill_tutorial.md`（进入可复用工作流阶段）

## 阅读目标

读完后，你应该能做到：
- 能写出结构清晰、边界明确的 Prompt
- 能把 Codex 当作 Agent 使用（先规划再执行）
- 能在 VS Code / 本地环境稳定运行 Codex
- 能为团队沉淀基础 Skill（如 Debug / 前端生成 / API / 项目讲解）

## 团队使用建议

- 先统一文档阅读顺序，再开始实操
- 每个成员先完成 1 次“项目结构分析 + 最小功能开发 + 最小修复”
- 在仓库中持续沉淀 `.codex/skills/`，形成团队复用能力

## 备注

以上四份文档适合大创项目的快速落地与团队协作训练。  
建议按“理解 → 配置 → 实战 → 沉淀 Skill”的路径推进。
