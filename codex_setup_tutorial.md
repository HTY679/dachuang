# 🚀 Codex 基础配置教程（Windows / macOS）

## 📌 适用对象
大创项目成员 / 初学 AI 编程工具的同学

---

# 🧠 一、Codex 是什么

Codex 是一个 AI 编程代理，可以：
- 写代码
- 改代码
- 修 Bug
- 理解项目
- 自动执行开发任务

👉 核心：用自然语言驱动开发

---

# ⚙️ 二、准备工作

你需要：

- ChatGPT 账号（支持 Codex）
- 或 OpenAI API Key
- 安装 VS Code（推荐）

---

# 🍎 三、Mac 配置教程

## 1️⃣ 安装 Codex App

1. 下载 Codex App（官网）
2. 安装并打开
3. 登录 ChatGPT 账号
4. 选择项目目录
5. 开始使用

---

## 2️⃣ VS Code 安装 Codex 插件

步骤：

1. 打开 VS Code
2. 打开扩展市场
3. 搜索：Codex
4. 点击安装
5. 登录账号

---

## 3️⃣ 在 VS Code 中使用

示例任务：

```text
先不要改代码，先分析这个项目结构
```

```text
请新增一个登录页面，只修改前端
```

---

# 🪟 四、Windows 配置教程

## 1️⃣ 安装 Codex App

1. Microsoft Store 搜索 Codex
2. 安装并打开
3. 登录账号
4. 选择项目

---

## 2️⃣ 推荐方式：WSL2 + VS Code

### 安装 WSL

```powershell
wsl --install
```

### 使用步骤：

1. 打开 WSL
2. 进入项目目录
3. 执行：

```bash
code .
```

4. 在 WSL 环境安装 Codex 插件

---

## 3️⃣ VS Code 使用方式

```text
先解释项目结构
```

```text
新增功能（限制范围）
```

```text
修 Bug（最小修改）
```

---

# 🧩 五、在 VS Code 调用 Codex

步骤：

1. 打开项目
2. 打开 Codex 面板
3. 输入 Prompt
4. 查看结果
5. 接受或修改

---

# 🖥 六、在本地 App 使用 Codex

## 使用流程

1. 选择项目
2. 输入任务
3. 查看 diff
4. 接受 / 拒绝
5. 继续优化

---

## 示例

```text
分析项目结构
```

```text
新增页面
```

```text
修复报错
```

---

# ⚠️ 七、常见问题

## Windows 插件不稳定

👉 使用 WSL2

---

## 修改错误

👉 检查 diff，不要盲信 AI

---

## 项目混乱

👉 明确 Prompt 限制

---

# 🚀 八、推荐练习

```text
解释项目结构
```

```text
新增登录页
```

```text
找出潜在问题
```

---

# 🎯 总结

- Codex = AI开发助手
- VS Code = 主战场
- App = 快速开发工具

👉 核心能力：会提需求 + 会检查结果
