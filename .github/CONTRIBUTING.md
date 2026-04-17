# Contributing to Claude Skills Collection

Thanks for your interest in contributing! This project thrives on community contributions.

## 🚀 Quick Start

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-skill`)
3. Commit your changes (`git commit -m 'feat: Add amazing skill'`)
4. Push to the branch (`git push origin feature/amazing-skill`)
5. Open a Pull Request

## 📋 Pull Request Process

### PR Checklist

Before submitting your PR:

- [ ] Read the [contribution guide](../docs/contributing.md)
- [ ] Skill follows the [format guide](../docs/skill-format-guide.md)
- [ ] All tests pass (if applicable)
- [ ] Documentation is complete
- [ ] Update README if adding a new skill
- [ ] PR follows our format below

### PR Format

```markdown
## Type: feat | fix | docs | style | refactor | test

### Summary
Brief description of changes

### Changes Made
- Added new skill for [Person]
- Updated research sources
- Fixed formatting issues

### Testing
- Verified trigger words work
- Tested examples
- Checked links

### Related Issues
Closes #[issue number]
```

## 🤝 Code of Conduct

This project follows a Code of Conduct. Please:

- Be respectful and inclusive
- Focus on what is best for the community
- Show empathy towards other community members

## 📞 Getting Help

- **GitHub Discussions**: [General questions](https://github.com/yourusername/claude-skills-collection/discussions)
- **GitHub Issues**: [Bugs and features](https://github.com/yourusername/claude-skills-collection/issues)
- **Email**: [maintainers@example.com](mailto:maintainers@example.com)

## 🎯 Development Workflow

### Local Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/claude-skills-collection.git
cd claude-skills-collection

# Install dependencies (if any)
npm install  # or pip install, etc.

# Create new skill
mkdir -p skills/new-skill
```

### Testing Skills

```bash
# Test skill installation
./test-skills.sh install

# Test skill triggers
./test-skills.sh triggers

# Run all tests
./test-skills.sh all
```

## 📝 Pull Request Template

```markdown
## PR Title Format
- feat: add [skill-name] skill
- fix: correct [issue] in [skill]
- docs: update documentation
- style: formatting changes

## Description
What does this PR do? Why is it needed?

## Changes
- [ ] Added new skill
- [ ] Updated existing skill
- [ ] Fixed documentation
- [ ] Other changes

## Testing
Describe how you tested these changes

## Checklist
- [ ] I have read the [contribution guide](../docs/contributing.md)
- [ ] My changes follow the [skill format guide](../docs/skill-format-guide.md)
- [ ] I have updated the README if needed
- [ ] I have added tests for my changes
- [ ] My PR is ready for review

## Additional Context
Any other context or screenshots
```

## 🏆 Recognition

Contributors will be recognized in:
- The skill metadata
- Contributors list
- Release notes

Thank you for helping build the best Claude skills collection!