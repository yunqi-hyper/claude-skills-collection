# 快速开始指南

欢迎使用何小鹏思维技能！本指南将帮助您安装和使用技能。

## 📋 前置条件

- 已安装 Claude Code CLI
- 基本的命令行操作知识

## 🔧 安装

### 1. 安装技能

```bash
# 安装特定技能
claude-skill install xiaopeng-xpeng-perspective

# 列出可用技能
claude-skill list

# 查看已安装技能
claude-skill installed
```

### 2. 技能目录

技能通常安装在以下位置：
- **macOS**: `~/.claude/skills/`
- **Linux**: `~/.claude/skills/`
- **Windows**: `%USERPROFILE%\.claude\skills\`

每个技能应包含：
- `SKILL.md` - 主要技能文件
- `README.md` - 文档说明
- `examples/` - 示例用例（可选）

## 💡 使用方法

### 1. 在对话中激活技能

使用触发词激活技能：

```
你: 何小鹏视角，如何看待智能汽车的未来？

何小鹏: "我们要做的不是一台更好的车，而是一台会思考的智能机器..."
```

### 2. 常见触发词

| 技能 | 触发词 |
|------|--------|
| 何小鹏 | 何小鹏视角, 小鹏思维, XPeng, 小鹏汽车, 互联网造车 |

### 3. 最佳实践

- 在消息开头使用触发词
- 明确说明你想了解的内容
- 必要时提供背景信息
- 后续提问以获得更详细的解答

## 🛠️ 故障排除

### 常见问题

**技能未找到**
```bash
# 重新安装技能
claude-skill install xiaopeng-xpeng-perspective

# 检查技能名称
claude-skill list
```

**技能未激活**
- 验证是否使用了正确的触发词
- 检查拼写和标点
- 尝试不同的触发词变体

### 获取帮助
```bash
# 获取帮助
claude-skill --help

# 报告问题
https://github.com/yunqi-hyper/he-xiaopeng.skill/issues
```

### 调试模式

启用调试模式查看详细信息：

```bash
# 启用调试
export CLAUDE_SKILL_DEBUG=true

# 查看技能详情
claude-skill info xiaopeng-xpeng-perspective
```

## 📚 下一步

1. **浏览技能**: 查看 [主README](../README.md) 了解技能详情
2. **贡献**: 学习如何贡献新技能，请参考 [贡献指南](contributing.md)
3. **技能格式**: 了解技能格式规范，请参考 [技能格式指南](skill-format-guide.md)

## 🆘 获取帮助

- GitHub Issues: [报告问题](https://github.com/yunqi-hyper/he-xiaopeng.skill/issues)
- Discussions: [提问讨论](https://github.com/yunqi-hyper/he-xiaopeng.skill/discussions)
- 文档: [完整文档](https://github.com/yunqi-hyper/he-xiaopeng.skill)