<div align="center">

# 🌍 EverySkill

### *You don't need an Agent, you need Skills*

**Bridging the last mile between professional AI Skills and free Chat platforms**

---

Ever wondered why paid AI tools seem "smarter"?  
It's not because they have better models—it's because they have **professional Skills**.

Now, **everyone** can have them.

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/SPA3K/EverySkill)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Standalone](https://img.shields.io/badge/standalone-HTML-orange.svg)](skill-preview-tool.html)

**📖 [Quick Start](#-quick-start) | 🎬 [3-Min Tutorial](#-usage-demo) | 💡 [Examples](#-examples) | ❓ [FAQ](#-faq)**

[中文文档](README.md)

</div>

---

## 💥 In One Sentence

**EverySkill** converts professional AI tool Skills into prompt templates that work with **any free AI Chat** like Kimi, ChatGPT, Claude, Tongyi Qianwen, and Wenxin Yiyan.

> 🎯 **Core Philosophy**: Agents are powerful but complex—designed for developers. What everyday users need are proven, reusable **Skills**.

### 🎓 Built-in Celebrity Skills

**EverySkill** comes with [**Zhang Xuefeng's Career Advisory Skillset**](https://github.com/Eric-Yibo-Shen/zhangxuefeng-skillset)!

Now you can use free AI to:
- 🎯 Get professional college major recommendations based on scores and interests
- 📊 Analyze career prospects and development paths
- 💼 Understand professional career trajectories

**Even better**: You can add **any celebrity's** methodology!
- 🎤 Luo Yonghao's product thinking?
- 💰 Warren Buffett's investment philosophy?
- 🎨 Steve Jobs' design principles?

As long as someone packages their methodology into a Skill, EverySkill can help free AI provide "celebrity-level" consulting!

---

## 🤔 Why Skills, Not Agents?

|  | Agent | Skill |
|---|---|---|
| **Purpose** | Complex autonomous decision-making system | Focused, single-capability module |
| **Barrier** | Requires configuration, debugging, workflow understanding | Plug-and-play, one-click generation |
| **Cost** | Usually requires paid API or subscription | Works with free AI Chat |
| **Learning Curve** | Steep (need to understand Agent frameworks) | Gentle (just copy-paste) |
| **Use Case** | Enterprise, developers, complex tasks | Daily use, quick problem-solving |

**Simply put**:
- ❌ Agent is a luxury sports car—powerful but needs license and maintenance
- ✅ Skill is a shared bike—simple but sufficient, ready to ride

---

## 🎯 What Problems Does It Solve?

### 😫 You Might Have Encountered These

1. **"This AI tool's XX feature is great, but it costs money..."**
   - ✅ EverySkill: Convert paid tool Skills into prompts for free AI

2. **"I don't know how to write prompts for professional code reviews..."**
   - ✅ EverySkill: Built-in professional Skills, generate standard prompts with one click

3. **"Describing requirements every time is too tedious..."**
   - ✅ EverySkill: Skills are reusable prompt templates, just fill in the blanks

4. **"AI responses are too generic, not professional enough..."**
   - ✅ EverySkill: Skills include role definitions, execution standards, output formats—guaranteed quality

### 🎁 What You Get

- 🆓 **Zero-cost professional capabilities**: No need to subscribe to paid tools
- ⚡ **Learn and use instantly**: 3 minutes to get started, no configuration needed
- 🎨 **Rich Skill library**: Code review, Git commits, TDD, architecture design, **Zhang Xuefeng career advice**...
- 🌟 **Celebrity Skill expansion**: Add any celebrity's methodology
- 🔒 **Privacy-focused**: Completely offline, no data upload
- 📱 **Anytime, anywhere**: Single HTML file, works on phone or computer

---

## ✨ How Does It Work?

```
┌─────────────────┐      ┌──────────────┐      ┌─────────────────┐
│ Professional    │ ───▶ │ EverySkill   │ ───▶ │ Standard Prompt │
│ Skill Package   │      │ (Convert)    │      │ (Copy & Paste)  │
└─────────────────┘      └──────────────┘      └─────────────────┘
                                                         │
                                                         ▼
                                               ┌─────────────────┐
                                               │ Free AI Chat    │
                                               │ (Any Platform)  │
                                               └─────────────────┘
```

**3 Steps:**
1. 📦 Choose a Skill (e.g., `code-reviewer`)
2. ✍️ Fill in your requirements (e.g., "Review Python code security")
3. 🚀 Generate prompt, paste into any free AI Chat

---

## 🚀 Quick Start

### 1️⃣ Download

```bash
# Clone repository
git clone https://github.com/SPA3K/EverySkill.git

# Or download single file (recommended)
wget https://raw.githubusercontent.com/SPA3K/EverySkill/main/skill-preview-tool.html
```

### 2️⃣ Open

Double-click `skill-preview-tool.html` or open in browser:
```
file:///path/to/skill-preview-tool.html
```

### 3️⃣ Use

1. Select a Skill from the left panel
2. Fill in requirements on the right
3. Click generate, copy the prompt
4. Paste into any free AI Chat

**That's it!** 🎉

---

## 🎬 Usage Demo

### 💡 Core Value: Give Free AI Professional-Grade Capabilities

#### Step 1️⃣: Open Tool, Select Skill

![Interface Screenshot](snapshot.png)
*👆 Clean interface - Skill library on left, workspace on right*

#### Step 2️⃣: Fill Requirements, Generate Prompt

![Input Comparison](inputVS.png)
*👆 **Key Comparison**: Left is your simple input, right is the generated professional prompt template*

You only need to:
- ✍️ Briefly describe requirements (doesn't need to be professional)
- 📎 Optional: Upload relevant files (code, configs, etc.)

EverySkill automatically generates:
- ✅ Professional role definitions
- ✅ Detailed execution instructions
- ✅ Structured output formats
- ✅ Quality control standards

#### Step 3️⃣: Copy & Paste to Free AI Chat

![Output Effect](outputVS.png)
*👆 Used in Tongyi Qianwen - AI provides professional structured suggestions based on Skill guidance*

**Amazing Results**:
- ❌ Without Skill: AI gives generic, unprofessional responses
- ✅ With EverySkill: AI becomes an expert, outputs professional, structured, actionable advice

---

## 📖 Examples

### 🔍 Example 1: Code Review (Turn Free AI into Your Code Reviewer)

**Choose Skill**: `code-reviewer`

**Fill Requirements**:
```
Project: Python Flask API
Focus areas: Security, performance, code standards
```

**Upload Files**: `app.py`, `requirements.txt`

**Generate Prompt** → Paste into Kimi/ChatGPT/Claude

**Result**: AI acts like a senior engineer, providing:
- 🔒 Security vulnerability analysis (SQL injection, XSS, etc.)
- ⚡ Performance optimization suggestions (query optimization, caching strategies)
- 📏 Code standard issues (PEP8, naming, structure)
- ✅ Modification suggestions and example code

**Value**: Professional code reviews that would require GitHub Copilot or CodeRabbit—now free!

---

### 💬 Example 2: Git Commit Messages (Say Goodbye to "update", "fix bug")

**Choose Skill**: `commit`

**Fill Requirements**:
```
Changes:
- Fixed SQL injection vulnerability in user login
- Added parameter validation
- Updated unit tests

Scope: auth module
```

**Generate Prompt** → Paste into any AI Chat

**Result**: AI generates Conventional Commits compliant message:
```
fix(auth): prevent SQL injection in login endpoint

- Add parameterized queries for user authentication
- Implement input validation for username/password
- Update auth tests to cover injection scenarios

BREAKING CHANGE: Login API now requires Content-Type header
```

**Value**: Professional Git standards without memorizing formats—AI writes them for you!

---

### 🧪 Example 3: TDD Development (Test-Driven Development Guide)

**Choose Skill**: `tdd-guide`

**Fill Requirements**:
```
Feature: Shopping cart system
- Add items
- Modify quantities
- Calculate total
- Apply coupons

Language: Python
Framework: pytest
```

**Generate Prompt** → Paste into AI Chat

**Result**: AI becomes your TDD coach, providing:
1. 📝 Test case design (Red phase)
2. ✅ Implementation code (Green phase)
3. 🔧 Refactoring suggestions (Refactor phase)
4. 🎯 Edge cases and exception handling

**Value**: Enterprise-level development process—free AI as your technical mentor!

---

### 🎓 Example 4: Zhang Xuefeng Career Advisor (College Major Selection)

**Choose Skill**: `zhangxuefeng-major-advisor` (built-in)

**Fill Requirements**:
```
Gaokao Score: 580
Province: Shandong
Category: Science
Interests: Computer Science, Finance
Family Expectations: Employment priority, considering postgraduate
```

**Generate Prompt** → Paste into any AI Chat

**Result**: AI responds like Zhang Xuefeng, providing:
- 🎯 Suitable major recommendations (sorted by admission probability)
- 📊 Career prospects analysis (salary, industry trends)
- 🏫 Recommended schools and cities (considering regional advantages)
- 💡 Major selection precautions (pitfall avoidance guide)
- 🔮 Future development paths (bachelor's employment vs. postgraduate)

**Value**: Professional college consulting that costs thousands—now free with AI providing Zhang Xuefeng-style advice!

**Extension Ideas**:
- Create "Luo Xiang's Legal Skill"
- Create "Li Yongle's Math Skill"
- Create "Warren Buffett's Investment Skill"
- **Any celebrity's methodology can become your free AI advisor!**

---

## 🎨 Interface Preview

![EverySkill Main Interface](snapshot.png)

**Interface Description:**
- **Left**: Skill library, searchable, filterable, add custom
- **Right**: Parameter input area, supports file upload
- **Bottom**: Generated complete prompt, one-click copy
- **Top**: Theme toggle (dark/light mode)

---

## 🛠️ Technical Features

- 🎯 **Single-file design**: One HTML file contains all functionality
- 📦 **Completely offline**: No internet needed after initial load
- 💾 **Local storage**: All data stored in browser, not uploaded to servers
- 🎨 **Modern UI**: Responsive layout, supports mobile
- ⚡ **Lightning fast**: No backend dependencies, instant load
- 🔒 **Privacy-focused**: Open source auditable, no data leaks

### Tech Stack
- Pure frontend: HTML5 + CSS3 + Vanilla JavaScript
- Dependencies (CDN): JSZip, js-yaml, marked
- Storage: LocalStorage

---

## 📚 Skill Format

Supports standard Claude Code Skill format (.zip package):

```
your-skill.zip
├── skill.md          # Required: Main Skill file
├── icon.svg          # Optional: Icon
└── additional/       # Optional: Additional resources
```

### skill.md Example

```markdown
---
name: my-skill
description: An awesome skill
version: 1.0.0
---

You are a professional {{role}}.

## Task
{{user_input}}

## Output Format
1. Analysis
2. Suggestions
3. Code
```

---

## ❓ FAQ

### Q1: Why Skills instead of Agents?

**A:** Agents are complex autonomous systems requiring configuration, debugging, and workflow understanding—usually paid. Skills are focused capability modules, plug-and-play, work with free AI Chat. For 99% of daily tasks, Skills are sufficient and simpler.

### Q2: How is this different from ChatGPT's GPTs?

**A:** 
- GPTs require ChatGPT Plus ($20/month) and only work in ChatGPT
- EverySkill is completely free, generated prompts work in any AI Chat

### Q3: Does it require internet?

**A:** 
- Initial load: Yes, to download dependencies
- After that: Completely offline

### Q4: Which AIs are supported?

**A:** Any AI Chat with text input:
- ✅ Kimi (Moonshot)
- ✅ Wenxin Yiyan (Baidu)
- ✅ Tongyi Qianwen (Alibaba)
- ✅ Doubao (ByteDance)
- ✅ ChatGPT (OpenAI)
- ✅ Claude (Anthropic)
- ✅ Any other LLM

### Q5: Is it safe?

**A:** 
- ✅ Data stored in browser locally
- ✅ No content uploaded to servers
- ✅ Open source code auditable
- ✅ Can be used completely offline

### Q6: How to add new Skills?

**A:** Two ways:
1. **Upload existing**: Click "➕ Add Skill", upload .zip package
2. **Create yourself**: Follow [Zhang Xuefeng Skillset](https://github.com/Eric-Yibo-Shen/zhangxuefeng-skillset) format, create any celebrity Skill

### Q7: What celebrity Skills can be added?

**A:** Any celebrity with clear methodology! Examples:
- 📚 **Education**: Zhang Xuefeng (major selection), Li Yongle (math), Luo Xiang (law)
- 💼 **Business**: Lei Jun (products), Luo Yonghao (marketing), Dong Mingzhu (management)
- 💰 **Investment**: Warren Buffett (value investing), Charlie Munger (mental models)
- 🎨 **Design**: Steve Jobs (product design), Kenya Hara (aesthetics)
- 🏋️ **Lifestyle**: Liu Genghong (fitness), Li Ziqi (life aesthetics)

Just organize their thinking and methodologies into Skill format, and free AI can provide "celebrity-level" advice!

---

## 🗺️ Roadmap

- [x] **v1.0** - Basic features
  - [x] Skill parsing and display
  - [x] Prompt generation
  - [x] Local storage
  
- [ ] **v1.1** - Enhanced experience
  - [ ] Skill editor
  - [ ] History management
  - [ ] One-click sharing
  
- [ ] **v1.2** - Ecosystem building
  - [ ] Official Skill marketplace
  - [ ] Community voting and ratings
  - [ ] Chrome/Firefox extensions
  
- [ ] **v2.0** - Platform
  - [ ] Multi-AI platform optimization
  - [ ] API interface
  - [ ] Desktop app

---

## 🤝 Contributing

Welcome to contribute Skills or improve code!

1. Fork repository
2. Create branch: `git checkout -b feature/AmazingFeature`
3. Commit changes: `git commit -m 'Add AmazingFeature'`
4. Push branch: `git push origin feature/AmazingFeature`
5. Submit Pull Request

---

## 📄 License

MIT License - Free to use, modify, distribute

---

## 🙏 Acknowledgments

- [JSZip](https://stuk.github.io/jszip/) - ZIP file processing
- [js-yaml](https://github.com/nodeca/js-yaml) - YAML parsing
- [marked](https://marked.js.org/) - Markdown rendering
- [Zhang Xuefeng Career Advisory Skillset](https://github.com/Eric-Yibo-Shen/zhangxuefeng-skillset) - First celebrity Skill example
- All developers who contribute Skills

---

<div align="center">

## 🌍 EverySkill

**You don't need an Agent, you need Skills**

Bridging the last mile between professional AI Skills and free Chat platforms

---

Made with ❤️ for everyone | Making AI capabilities truly universal

[⭐ Star](https://github.com/SPA3K/EverySkill) | [🐛 Report Bug](https://github.com/SPA3K/EverySkill/issues) | [💡 Request Feature](https://github.com/SPA3K/EverySkill/issues)

</div>
