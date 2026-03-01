# AI 编程工具对比分析研究

> 持续更新 AI 编程工具的对比分析和使用研究

## 📊 工具对比

### OpenCode vs Claude Code

| 维度 | OpenCode | Claude Code |
|------|----------|-------------|
| **Stars** | 11,164 | 72,157 ⭐ |
| **开发语言** | Go | Shell/TypeScript |
| **状态** | ⚠️ 已归档 → [Crush](https://github.com/charmbracelet/crush) | 活跃维护 |
| **支持模型** | 多提供商 (OpenAI/Gemini/Claude/Copilot 等) | 仅 Claude |
| **TUI 界面** | ✅ Bubble Tea | ✅ |
| **MCP 扩展** | ✅ | ✅ |
| **LSP 集成** | ✅ | ✅ |
| **自定义命令** | ✅ (Markdown) | ✅ (插件) |
| **SQLite 存储** | ✅ | ✅ |
| **Auto Compact** | ✅ (自动压缩上下文) | ✅ |

#### OpenCode 优缺点

**✅ 优点：**
- 支持任意 LLM 提供商，灵活性高
- 可以用 Gemini、Copilot 等低成本模型
- Go 语言，性能好
- 自定义命令功能强

**❌ 缺点：**
- **已停止维护**（迁移到 Crush）
- 生态不如 Claude Code
- 文档和社区支持较少

#### Claude Code 优缺点

**✅ 优点：**
- 官方维护，更新快
- 与 Claude 模型深度集成，能力最强
- 社区活跃（72k+ stars）
- GitHub 原生集成（@claude）
- 插件生态丰富

**❌ 缺点：**
- 仅支持 Claude 模型（成本较高）
- 不支持其他 LLM

---

## 🔧 其他 AI 编程工具

| 工具 | 模型 | 特点 |
|------|------|------|
| **Cursor** | OpenAI + Claude | IDE 集成，功能强大 |
| **Windsurf** | Claude (Codeium) | AI-first IDE |
| **GitHub Copilot** | OpenAI | 集成广泛 |
| **Tabnine** | 多种 | 老牌 AI 补全 |

---

## 📝 分析记录

### 2026-03-01

- 对比 OpenCode 和 Claude Code
- 分析功能差异和适用场景
- OpenCode 已迁移到 Crush 项目

---

## 📌 关注项目

- [Crush](https://github.com/charmbracelet/crush) - OpenCode 继任者
- [Claude Code](https://github.com/anthropics/claude-code) - 官方 AI 编程工具

---

*本仓库由 AI 助手维护，持续更新 AI 编程工具研究*
