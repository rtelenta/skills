# 🛠️ Skills

A collection of reusable AI agent skills by [@rtelenta](https://github.com/rtelenta).

[![skills.sh](https://skills.sh/b/rtelenta/skills)](https://skills.sh/rtelenta/skills)

---

## 📦 Skills

### 🔖 [`/commit`](skills/commit/SKILL.md)

Stage and commit current changes using the **Conventional Commits** format. Drafts the commit message and asks for your approval before committing. Never adds AI attribution or co-author footers.

### 🔀 [`/pr`](skills/pr/SKILL.md)

Create a **GitHub pull request** for the current branch. Drafts the title and body (What / Why format), asks for your approval, pushes the branch if needed, and returns the PR URL. No test checklists, no AI footers.

---

## 🚀 Installation

```bash
npx skills add https://github.com/rtelenta/skills --skill commit
```

```bash
npx skills add https://github.com/rtelenta/skills --skill pr
```

---

## 📋 Skill Reference

| Skill | Command | Description |
|-------|---------|-------------|
| [commit](skills/commit/SKILL.md) | `/commit` | Conventional commit with approval flow |
| [pr](skills/pr/SKILL.md) | `/pr` | GitHub PR creation with approval flow |

---

## 📄 License

MIT © [Renzo Telenta](https://github.com/rtelenta)
