# Native UI Skills (Naive UI Vue 3 Component Library Skill)

本仓库包含了 **Naive UI** 全部 97 个 Vue 3 组件的完整使用指南、API 规范与渐进式索引，专为 AI Coding Agent（如 Gemini Antigravity, Claude, Cursor, Windsurf 等）设计，便于在代码生成与重构过程中快速检索组件文档。

---

## 🚀 快速使用 (via skills.sh)

你可以使用 [skills.sh](https://skills.sh) / `npx skills` 命令行工具一键将当前 Skill 添加到你的开发环境中：

### 1. 使用 `skills.sh` 命令行快速添加

在你的项目根目录或 Agent 工作区终端中运行：

```bash
# 使用 npx 直接添加 GitHub 仓库 Skill
npx skills add akirousnow/native-ui-skills

# 或者通过完整 GitHub URL 添加
npx skills add https://github.com/akirousnow/native-ui-skills
```

### 2. 手动安装或配置到全局/项目 Agent 路径

如果需要手动配置：

* **全局配置**：克隆到你的 Agent 全局 Skills 目录（例如 `~/.gemini/config/skills/native-ui` 或 `~/.cursor/skills/native-ui`）：
  ```bash
  git clone https://github.com/akirousnow/native-ui-skills.git ~/.gemini/config/skills/native-ui
  ```

* **项目本地配置**：在目标项目中作为 Git Submodule 引入：
  ```bash
  git submodule add https://github.com/akirousnow/native-ui-skills.git .agents/skills/native-ui
  ```

---

## 📖 库结构说明

* [`SKILL.md`](SKILL.md)：核心 Skill 入口文件，包含全局配置及所有 97 个组件的功能提炼与速查表格。
* [`docs/`](docs/)：所有 Naive UI 组件的详细文档集合，包含每个组件的：
  * 功能简述
  * 属性 (Props) 列表与默认值
  * 事件 (Events) 签名
  * 插槽 (Slots) 与 Template 规则
  * 类型定义 (TypeScript Types) 与使用范例

---

## 📄 许可证

[MIT](LICENSE)
