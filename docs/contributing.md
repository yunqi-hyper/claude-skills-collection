# Contributing to Claude Skills Collection

We welcome contributions! This guide will help you add new skills and improve existing ones.

## 🤝 Contribution Guidelines

### Types of Contributions

1. **New Skills**: Add skills representing notable individuals
2. **Improvements**: Enhance existing skills
3. **Documentation**: Fix or improve documentation
4. **Bug Fixes**: Correct errors in skill files

### Skill Quality Standards

#### Research Quality
- Based on publicly available information
- Multiple sources verified
- No speculation or personal opinions
- Properly cited and referenced

#### Structure
- Follows the standard skill format
- Clear sections and organization
- Practical examples included
- Decision heuristics where applicable

#### Authenticity
- Captures the individual's voice and style
- Accurate representation of their thinking
- Context-appropriate responses
- No stereotyping or oversimplification

## 📝 Adding a New Skill

### 1. Skill Structure

Create a new skill in `skills/[skill-name]/`:

```
skills/new-skill/
├── SKILL.md
├── README.md
└── examples/
    └── sample-conversation.md
```

### 2. SKILL.md Format

```yaml
---
name: skill-name
description: |
  Brief description of the skill
trigger_words: |
  Word1, Word2, Word3
version: 1.0.0
author: Your Name
last_updated: YYYY-MM-DD
---

# Skill Name

> "Famous quote"

## Core Identity
...

## Mental Models
...

## Decision Heuristics
...
```

### 3. README.md Template

```markdown
# Skill Name

> Brief description

## Overview
- **Skill ID**: `skill-name`
- **Version**: 1.0.0
- **Last Updated**: YYYY-MM-DD

## Installation
```bash
claude-skill install skill-name
```

## Usage
### Triggers
- Trigger1
- Trigger2

### Example
```
User: Question
Skill: Response
```

## Research Sources
- Source 1
- Source 2
```

### 4. Example Conversation

Show real-world applications of the skill.

## 🔄 Contribution Workflow

### 1. Fork the Repository

```bash
# Fork the repo on GitHub
git clone https://github.com/YOUR_USERNAME/claude-skills-collection.git
cd claude-skills-collection
```

### 2. Create a Branch

```bash
# Create a feature branch
git checkout -b feature/add-new-skill
```

### 3. Add Your Skill

Create the skill files following the structure above.

### 4. Test Your Skill

- Verify all links work
- Check formatting
- Test trigger words
- Review examples

### 5. Commit and Push

```bash
git add .
git commit -m "feat: Add [Skill Name] skill"
git push origin feature/add-new-skill
```

### 6. Create a Pull Request

- PR title: `feat: Add [Skill Name] skill`
- PR description:
  - What the skill does
  - Research methodology
  - Key features
  - Testing performed

## 📋 Review Criteria

Skills will be reviewed based on:

### Research Accuracy (40%)
- Multiple verified sources
- No factual errors
- Proper citations
- Up-to-date information

### Structure (20%)
- Correct file format
- Clear organization
- Complete sections
- Easy to understand

### Authenticity (30%)
- True to individual's voice
- Accurate thinking patterns
- Context-appropriate
- No stereotyping

### Practicality (10%)
- Useful examples
- Clear triggers
- Easy to use
- Good documentation

## 🎯 Skills We Want

### Priority Areas
1. **Entrepreneurs**: Tech founders, business leaders
2. **Scientists**: Researchers, innovators
3. **Artists**: Creators, designers
4. **Thinkers**: Philosophers, writers

### Quality Indicators
- Substantial public record
- Clear thinking patterns
- Unique insights
- Educational value

## ❌ What to Avoid

- Speculation or unverified claims
- Stereotypes or caricatures
- Copyrighted material
- Poor research quality
- Incomplete skills

## 📞 Getting Help

- GitHub Discussions: [Ask questions](https://github.com/yourusername/claude-skills-collection/discussions)
- GitHub Issues: [Report problems](https://github.com/yourusername/claude-skills-collection/issues)
- Email: [your-email@example.com]

## 🏆 Recognition

Contributors will be acknowledged in:
- Skill metadata
- Contributors list
- Release notes

Thank you for helping build the best Claude skills collection!