# 🤝 Contributing to AI Workflow Templates

Thank you for your interest in contributing to **AI Workflow Templates**.

This repository aims to provide high-quality, reusable workflow templates, automation blueprints, and AI-powered solutions for platforms such as n8n, Make.com, OpenAI, Claude, Gemini, OpenRouter, Grok, and other automation tools.

Your contributions help make this repository more useful for the global automation community.

---

## 🚀 Ways to Contribute

You can contribute by:

- Adding new workflow templates
- Improving existing workflows
- Fixing bugs
- Improving documentation
- Reporting issues
- Suggesting new workflow ideas
- Adding screenshots and examples
- Sharing automation best practices

---

## 📋 Before You Contribute

Please ensure that:

- The workflow has been tested successfully.
- No API keys, passwords, tokens, or secrets are included.
- Documentation is included.
- Screenshots are provided where applicable.
- Naming conventions are followed.
- The workflow serves a clear purpose.

---

## 📁 Workflow Folder Structure

Each workflow should follow this structure:

```text
workflow.json (or blueprint.json)
README.md
screenshot.png
config-example.json (optional)
```

Example:

```text
n8n/
└── ai-blog-writer/
    ├── workflow.json
    ├── README.md
    ├── screenshot.png
    └── config-example.json
```

---

## 🏷️ Naming Convention

Use clear and descriptive names.

### Good Examples

```text
n8n-ai-blog-writer
n8n-lead-generator
n8n-customer-support-agent
make-content-calendar
make-instagram-automation
make-email-followup-system
```

### Avoid

```text
workflow1
workflow2
test
sample
new-workflow
automation
myworkflow
```

---

## 📖 Documentation Requirements

Every workflow should include:

- ✅ README.md
- ✅ Workflow File
- ✅ Setup Instructions
- ✅ Required Integrations
- ✅ Screenshot
- ✅ Configuration Notes

---

## 🔐 Security Guidelines

Never commit:

- API Keys
- Passwords
- Access Tokens
- Private Certificates
- Database Credentials
- Personal Information

Use placeholder values instead.

Example:

```json
{
  "OPENAI_API_KEY": "YOUR_API_KEY_HERE",
  "CLAUDE_API_KEY": "YOUR_API_KEY_HERE"
}
```

---

## 🔄 Contribution Process

### Step 1: Fork the Repository

Fork the repository to your GitHub account.

### Step 2: Create a New Branch

```bash
git checkout -b feature/my-workflow
```

### Step 3: Make Your Changes

Add or update workflows, documentation, or examples.

### Step 4: Commit Your Changes

```bash
git add .
git commit -m "Added AI blog writer workflow"
```

### Step 5: Push Changes

```bash
git push origin feature/my-workflow
```

### Step 6: Open a Pull Request

Create a Pull Request describing:

- What was added
- Why it was added
- Any dependencies required
- Testing performed

---

## ✅ Pull Request Checklist

Before submitting a Pull Request, verify:

- [ ] Workflow tested successfully
- [ ] Documentation included
- [ ] Screenshot included
- [ ] No secrets included
- [ ] Folder structure followed
- [ ] Naming convention followed
- [ ] README completed
- [ ] Configuration documented

---

## 🐛 Reporting Issues

If you discover a bug or problem:

1. Open a GitHub Issue
2. Describe the issue clearly
3. Include screenshots if possible
4. Include error messages
5. Provide reproduction steps

---

## 🌟 Quality Standards

We aim to maintain a repository of production-ready workflows.

Preferred contributions:

- Well documented
- Easy to deploy
- Reusable
- Business focused
- Secure
- Tested

---

## 📜 Code of Conduct

Please be respectful, constructive, and professional when interacting with other contributors.

---

## 🙏 Thank You

Thank you for helping improve **AI Workflow Templates**.

Happy Automating! 🚀
