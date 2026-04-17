# 贡献指南

感谢您对何小鹏思维技能的兴趣！本项目欢迎社区贡献。

## 🚀 快速开始

1. Fork 仓库
2. 创建功能分支 (`git checkout -b feature/amazing-skill`)
3. 提交更改 (`git commit -m 'feat: 添加惊人技能'`)
4. 推送到分支 (`git push origin feature/amazing-skill`)
5. 创建 Pull Request

## 📋 Pull Request 流程

### PR 检查清单

提交 PR 前：

- [ ] 阅读 [贡献指南](../docs/contributing.md)
- [ ] 技能遵循 [格式指南](../docs/skill-format-guide.md)
- [ ] 所有测试通过（如适用）
- [ ] 文档完整
- [ ] PR 遵循以下格式

### PR 格式

```markdown
## 类型: feat | fix | docs | style | refactor | test

### 概述
简要描述更改

### 所做更改
- 添加了 [人物] 的新技能
- 更新了研究来源
- 修复了格式问题

### 测试
- 验证了触发词有效
- 测试了示例
- 检查了链接

### 相关问题
关闭 #[issue 编号]
```

## 🤝 行为准则

本项目遵循行为准则。请：

- 相互尊重和包容
- 专注于对社区最好的事
- 对其他社区成员表示同理心

## 📞 获取帮助

- **GitHub Discussions**: [一般问题](https://github.com/yunqi-hyper/he-xiaopeng.skill/discussions)
- **GitHub Issues**: [错误和功能](https://github.com/yunqi-hyper/he-xiaopeng.skill/issues)
- **邮箱**: [maintainers@example.com](mailto:maintainers@example.com)

## 🎯 开发工作流

### 本地设置

```bash
# Clone 你的 fork
git clone https://github.com/YOUR_USERNAME/he-xiaopeng.skill.git
cd he-xiaopeng.skill

# 安装依赖（如果有）
npm install  # 或 pip install 等

# 创建新技能
mkdir -p skills/new-skill
```

### 测试技能

```bash
# 测试技能安装
./test-skills.sh install

# 测试技能触发
./test-skills.sh triggers

# 运行所有测试
./test-skills.sh all
```

## 📝 Pull Request 模板

```markdown
## PR 标题格式
- feat: 添加 [技能名] 技能
- fix: 修复 [技能] 中的 [问题]
- docs: 更新文档
- style: 格式更改

## 描述
这个 PR 做了什么？为什么需要？

## 更改
- [ ] 添加了新技能
- [ ] 更新了现有技能
- [ ] 修复了文档
- [ ] 其他更改

## 测试
描述你如何测试这些更改

## 检查清单
- [ ] 我已阅读 [贡献指南](../docs/contributing.md)
- [ ] 我的更改遵循 [技能格式指南](../docs/skill-format-guide.md)
- [ ] 我已在需要时更新 README
- [ ] 我已为我的更改添加测试
- [ ] 我的 PR 已准备好审查

## 其他上下文
任何其他上下文或截图
```

## 🏆 认可

贡献者将在以下地方获得认可：
- 技能元数据
- 贡献者列表
- 发布说明

感谢您帮助构建最好的何小鹏思维技能！