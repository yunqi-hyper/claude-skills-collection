# 贡献指南

感谢您对何小鹏思维技能的贡献！本指南将帮助您添加新技能和改进现有技能。

## 🤝 贡献准则

### 贡献类型
1. **新技能**: 添加代表杰出人物的技能
2. **改进**: 增强现有技能
3. **文档**: 修复或改进文档
4. **Bug修复**: 修正技能文件中的错误

### 技能质量标准
#### 研究质量
- 基于公开可得的信息
- 多个来源验证
- 无推测或个人观点
- 正确引用和参考

#### 结构
- 遵循标准技能格式
- 清晰的章节和组织
- 包含实际示例
- 决策启发式（如适用）

#### 真实性
- 捕捉个人的声音和风格
- 准确代表其思维方式
- 语境适当的回答
- 避免刻板印象或过度简化

## 📝 添加新技能

### 1. 技能结构
在 `skills/` 目录创建新技能：
```
skills/new-skill/
├── SKILL.md
├── README.md
└── examples/
    └── sample-conversation.md
```

### 2. SKILL.md 格式
```yaml
---
name: skill-name
description: |
  技能简短描述
trigger_words: |
  触发词1, 触发词2, 触发词3
version: 1.0.0
author: 你的名字
last_updated: YYYY-MM-DD
---

# 技能名称

> "名言警句"

## 核心身份
...

## 心智模型
...

## 决策启发式
...
```

### 3. README.md 模板
```markdown
# 技能名称

> 简短描述

## 概览
- **技能ID**: `skill-name`
- **版本**: 1.0.0
- **最后更新**: YYYY-MM-DD

## 安装
```bash
claude-skill install skill-name
```

## 使用方法
### 触发词
- 触发词1
- 触发词2

### 示例
```
用户: 问题
技能: 回答
```

## 研究来源
- 来源1
- 来源2
```

### 4. 示例对话
展示技能的实际应用。

## 🔄 贡献工作流

### 1. Fork 仓库
```bash
# 在GitHub上fork仓库
git clone https://github.com/YOUR_USERNAME/he-xiaopeng.skill.git
cd he-xiaopeng.skill
```

### 2. 创建分支
```bash
# 创建功能分支
git checkout -b feature/add-new-skill
```

### 3. 添加技能
按照上述结构创建技能文件。

### 4. 测试技能
- 验证所有链接正常
- 检查格式
- 测试触发词
- 检查示例

### 5. 提交并推送
```bash
git add .
git commit -m "feat: 添加[技能名]技能"
git push origin feature/add-new-skill
```

### 6. 创建 Pull Request
- PR标题: `feat: 添加[技能名]技能`
- PR描述:
  - 技能的功能
  - 研究方法
  - 主要特性
  - 测试情况

## 📋 审查标准

技能将根据以下标准审查：

### 研究准确性 (40%)
- 多个已验证来源
- 无事实错误
- 正确引用
- 信息最新

### 结构 (20%)
- 正确的文件格式
- 清晰的组织
- 完整章节
- 易于理解

### 真实性 (30%)
- 符合个人声音
- 准确的思维方式
- 语境适当
- 无刻板印象

### 实用性 (10%)
- 有用的示例
- 清晰的触发词
- 易于使用
- 好的文档

## 🎯 我们需要的技能

### 优先领域
1. **企业家**: 科技创始人、商业领袖
2. **科学家**: 研究人员、创新者
3. **艺术家**: 创作者、设计师
4. **思想家**: 哲学家、作家

### 质量指标
- 丰富的公开记录
- 清晰的思维模式
- 独特的见解
- 教育价值

## ❌ 避免事项

- 推测或未经证实的声明
- 刻板印象或 caricatures
- 受版权保护的材料
- 研究质量差
- 不完整的技能

## 📞 获取帮助

- GitHub Discussions: [提问](https://github.com/yunqi-hyper/he-xiaopeng.skill/discussions)
- GitHub Issues: [报告问题](https://github.com/yunqi-hyper/he-xiaopeng.skill/issues)
- 邮箱: [your-email@example.com]

## 🏆 致谢

贡献者将在以下地方获得认可：
- 技能元数据
- 贡献者列表
- 发布说明

感谢您帮助构建最好的何小鹏思维技能！