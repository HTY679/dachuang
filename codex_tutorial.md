# 🚀 Codex 使用教程（大创小组内部版）

> 核心理念：  
> 👉 用自然语言描述需求 → AI生成代码 → 验证 → 迭代优化  
> 👉 先做“最小可运行版本”，再逐步增强功能  

---

# 🧠 一、Codex是什么？

Codex 是一个 AI 编程工具，本质属于：

- 🤖 “终端级 AI / 智能开发助手”
- 🧾 输入自然语言 → 自动生成代码
- ⚡ 适合快速开发原型（大创非常适合）

---

# ✍️ 二、核心使用方法（通用）

## 1️⃣ 基本流程（必须掌握）

需求描述 → Prompt设计 → AI生成代码 → 本地运行 → 修改优化

---

## 2️⃣ 标准 Prompt 模板（直接复制用）

我需要实现一个【功能名称】。

需求描述：
- 功能1：
- 功能2：
- 页面/交互逻辑：

输入输出示例：
输入：
输出：

技术栈：Python + Flask（或 React / Vue）

约束要求：
- 代码必须完整可运行
- 注释清晰
- 不要省略关键函数
- 结构清晰

请直接输出完整代码，并说明运行方法。

---

## 3️⃣ 使用策略（非常关键）

- ✅ 先生成最简版本
- ❌ 不要一开始就做复杂系统
- 🔁 多轮迭代优化

---

# 🍎 三、Mac 版 Codex 教程

## 1️⃣ 环境准备

### 安装基础环境

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install node
brew install python
```

### 安装 VS Code

https://code.visualstudio.com/

### 配置 Codex

```bash
pip install openai
export OPENAI_API_KEY="你的key"
```

---

## 2️⃣ 使用方式

### 终端调用

```bash
openai chat.completions.create \
  -m gpt-4.1 \
  -g user "帮我写一个Flask网站，实现用户登录功能"
```

### VS Code 插件（推荐）

- GitHub Copilot
- ChatGPT 插件

---

## 3️⃣ 运行项目

```bash
pip install flask
python app.py
```

访问：http://127.0.0.1:5000

---

# 🪟 四、Windows 版 Codex 教程

## 1️⃣ 环境准备

### 安装 Python

https://www.python.org/

✔ 勾选 Add Python to PATH

### 安装 Node.js

https://nodejs.org/

### 安装 VS Code

https://code.visualstudio.com/

---

## 2️⃣ 配置 Codex

```powershell
pip install openai
setx OPENAI_API_KEY "你的key"
```

---

## 3️⃣ 使用方式

```powershell
openai chat.completions.create `
  -m gpt-4.1 `
  -g user "写一个学生管理系统，Python实现"
```

---

## 4️⃣ 运行项目

```powershell
python app.py
```

---

# 🧩 五、Skill（技能）使用指南

## 常见 Skill

### API

帮我调用某某API，实现数据获取

### Debug

这段代码报错如下，请帮我定位问题并修复

### 前端UI

帮我用 React 写一个美观的页面，使用 Ant Design

### 数据库

帮我设计 MySQL 表结构，实现用户系统

---

# ⚠️ 六、常见问题

## AI代码运行失败

👉 提供完整报错 + 代码给AI

## 功能混乱

👉 Prompt太模糊，拆分需求

## 看不懂代码

👉 需要数据结构基础

---

# 🏁 七、团队协作建议

## 分工

- 产品：写Prompt
- 开发：用Codex生成代码
- 测试：运行代码
- 优化：Debug

## 流程

1. 明确需求
2. 写Prompt
3. AI生成最小版本
4. 本地运行
5. 逐步优化

---

# 🎯 总结

- Codex适合快速开发与原型验证
- 复杂系统仍需人工设计
