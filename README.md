<div align="center">

# 📝 changelog-from-git

**Polished release notes and CHANGELOG entries from git history. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/changelog-from-git)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/changelog-from-git?style=social)](https://github.com/milad-ahmd/changelog-from-git)
![Category](https://img.shields.io/badge/category-Git%20&%20Workflow-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/changelog-from-git/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- changelog-from-git
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/changelog-from-git /tmp/changelog-from-git
mkdir -p ~/.claude/skills && cp -r /tmp/changelog-from-git/skills/changelog-from-git ~/.claude/skills/
```

**Per project:** copy `skills/changelog-from-git` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/changelog-from-git/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Write release notes since the last tag
Draft the GitHub release for v2.0
```

The full workflow, rules and output format are in [`SKILL.md`](skills/changelog-from-git/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
