# Getting Started with Claude Skills Collection

Welcome to the Claude Skills Collection! This guide will help you install and use skills in your Claude conversations.

## 📋 Prerequisites

- Claude Code CLI installed
- Basic understanding of command line operations

## 🔧 Installation

### 1. Install a Skill

```bash
# Install a specific skill
claude-skill install xiaopeng-xpeng-perspective

# List available skills
claude-skill list

# Check installed skills
claude-skill installed
```

### 2. Skills Directory

Skills are typically installed to:
- **macOS**: `~/.claude/skills/`
- **Linux**: `~/.claude/skills/`
- **Windows**: `%USERPROFILE%\.claude\skills\`

Each skill should have:
- `SKILL.md` - Main skill file
- `README.md` - Documentation
- `examples/` - Sample use cases (optional)

## 💡 Usage

### 1. Trigger a Skill in Conversation

Use the skill's trigger words to activate it:

```
User: 何小鹏视角，如何看待智能汽车的未来？

He Xiaopeng: "我们要做的不是一台更好的车，而是一台会思考的智能机器..."
```

### 2. Common Triggers

| Skill | Trigger Words |
|-------|---------------|
| He Xiaopeng | 何小鹏视角, 小鹏思维, XPeng, 小鹏汽车, 互联网造车 |

### 3. Best Practices

- Use trigger words at the beginning of your message
- Be specific about what you want to know
- Provide context when needed
- Follow up for clarification

## 🛠️ Troubleshooting

### Common Issues

**Skill not found**
```bash
# Reinstall the skill
claude-skill install xiaopeng-xpeng-perspective

# Check skill name
claude-skill list
```

**Skill not activating**
- Verify you're using the correct trigger words
- Check spelling and punctuation
- Try different variations of the trigger

**Need help**
```bash
# Get help
claude-skill --help

# Report issues
https://github.com/yourusername/claude-skills-collection/issues
```

### Debug Mode

Enable debug mode to see detailed information:

```bash
# Enable debugging
export CLAUDE_SKILL_DEBUG=true

# Check skill details
claude-skill info xiaopeng-xpeng-perspective
```

## 📚 Next Steps

1. **Browse Skills**: Check the [main README](../README.md) for available skills
2. **Contributing**: Learn how to contribute new skills in [contributing.md](contributing.md)
3. **Skill Format**: Understand the skill format in [skill-format-guide.md](skill-format-guide.md)

## 🆘 Getting Help

- GitHub Issues: [Report a problem](https://github.com/yourusername/claude-skills-collection/issues)
- Discussions: [Ask questions](https://github.com/yourusername/claude-skills-collection/discussions)
- Documentation: [Full docs](https://github.com/yourusername/claude-skills-collection)