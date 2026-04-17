# Skill Format Guide

This guide explains the standard format for Claude skills in the collection.

## 📁 File Structure

Each skill should have the following structure:

```
skill-name/
├── SKILL.md          # Main skill file (required)
├── README.md         # User documentation (required)
└── examples/         # Examples and use cases (optional)
    ├── sample-conversation.md
    └── another-example.md
```

## 📋 SKILL.md Format

### Front Matter (YAML)

All skills must start with YAML front matter:

```yaml
---
name: skill-name                    # Unique identifier
description: |
  Brief, engaging description
trigger_words: |
  Word1, Word2, Word3              # Comma-separated
version: 1.0.0                     # Semantic versioning
author: Contributor Name           # Your name/alias
last_updated: YYYY-MM-DD          # Last update date
---

# Title
```

### Required Sections

#### 1. Core Quote
Start with a representative quote:
```markdown
> "Famous quote that captures the essence"
```

#### 2. Core Identity
Brief overview of who this person is and their significance.

#### 3. Mental Models
Key frameworks and ways of thinking:
- 3-6 core models
- Each with description, evidence, application, limitations

#### 4. Decision Heuristics
Practical decision-making rules:
- Table format recommended
- Include scenario, rule, example

#### 5. Expression DNA
How they communicate:
- Sentence patterns
- Vocabulary preferences
- Rhythm and tone

#### 6. Timeline
Key milestones:
- Table with time, event, significance

### Optional Sections

- Values & Anti-patterns
- Honest Boundaries
- Intellectual Genealogy
- Research Sources

## 📖 README.md Format

### Required Sections

#### 1. Title and Tagline
```markdown
# Skill Name

> Brief tagline
```

#### 2. Overview
- Skill ID and version
- Last updated date
- Focus areas

#### 3. Installation
```bash
claude-skill install skill-name
```

#### 4. Usage
- Trigger words
- Example applications
- Sample conversation

#### 5. Research Sources
- Primary sources
- Secondary sources

## 🎨 Writing Guidelines

### Voice and Tone

- **First-person**: The skill speaks as the person
- **Authentic**: Capture their actual voice
- **Context-aware**: Adjust to conversation topics
- **Respectful**: Avoid stereotypes and caricatures

### Content Guidelines

#### What to Include
- Verified facts from public sources
- Actual quotes and sayings
- Real decision-making frameworks
- Authentic mental models

#### What to Avoid
- Speculation or personal opinions
- Unverified claims
- Stereotypes
- Copyrighted material

### Research Requirements

- Minimum 3 reliable sources
- Primary sources preferred (speeches, writings)
- Secondary sources for context
- All sources properly cited

## 🔧 Technical Requirements

### File Naming
- Use lowercase with hyphens
- No spaces or special characters
- Keep it short and descriptive

### Versioning
Use semantic versioning:
- `1.0.0` - Initial release
- `1.1.0` - Adding features
- `1.0.1` - Bug fixes
- `2.0.0` - Major changes

### Trigger Words
- 3-5 key phrases
- Natural language
- Easy to remember
- Unique to the skill

## 📝 Examples

### SKILL.md Front Matter
```yaml
---
name: steve-jobs-apple-think
description: |
  Steve Jobs: Apple co-founder, design visionary. Captures his minimalist design philosophy and product obsession.
trigger_words: |
  乔布斯视角, 苹果思维, 极简主义, 产品哲学
version: 1.0.0
author: Skill Collection
last_updated: 2024-04-17
---
```

### Mental Model Format
```markdown
### 1. Design Simplicity
- **Description**: Less is more, focus on essential user experience
- **Source Evidence**:
  - "Design is not just what it looks like"
  - Removal of unnecessary ports in MacBook
- **Application**: Remove features that don't serve core user needs
- **Limitations**: Can lead to reduced customization options
```

### Decision Heuristic
```markdown
| Heuristic | Application |
|-----------|-------------|
| "Three clicks" rule | Any task should take ≤ 3 clicks |
| "Thinnest possible" | Make devices as thin as technology allows |
```

## 🧪 Testing Checklist

Before submitting:

- [ ] Front matter is complete and correct
- [ ] All links work
- [ ] No spelling or grammar errors
- [ ] Voice is authentic
- [ ] Examples are practical
- [ ] Research is properly cited
- [ ] Format follows this guide
- [ ] README matches skill
- [ ] Trigger words work
- [ ] Version is up-to-date

## 📚 Reference Resources

- [Anthropic's Skill Documentation](https://docs.anthropic.com/claude/docs/skills)
- [Markdown Guide](https://www.markdownguide.org/)
- [Semantic Versioning](https://semver.org/)

## ❌ Common Mistakes

1. **Research gaps** - Not enough sources or verification
2. **Voice inconsistency** - Not staying in character
3. **Poor structure** - Missing sections or bad organization
4. **Weak examples** - Abstract or unrealistic scenarios
5. **Technical errors** - Bad formatting or broken links

Follow this guide to create high-quality, useful Claude skills!