# 🚀 Git Workflow Guide

> Standard workflow for all developers to ensure consistency and clean collaboration.

---

## 📌 1. Before Starting Work (Important)

Whenever you start any task, always pull the latest code from `main` first.

```bash
git checkout main
git pull origin main
```

---

## 🌿 2. Create a New Branch

After pulling the latest code, create a new branch for your task.

```bash
git checkout -b type/task-name
```

### 🏷️ Branch Naming

| Type      | Example                     |
|----------|---------------------------|
| feature  | feature/add-login          |
| fix      | fix/navbar-issue           |
| refactor | refactor/auth-service      |
| docs     | docs/update-readme         |

### ⚠️ Rules

- One branch = one task  
- Do not mix multiple features  
- Never work directly on `main`  

---

## 🛠️ 3. Work on Feature

- Work only inside your branch  
- Keep changes clean and focused  
- Avoid unrelated code  

---

## 🧾 4. Commit Guidelines

### 📌 Format

```bash
git commit -m "type: short message"
```

### 🧠 Types

`feat` | `fix` | `refactor` | `docs` | `style` | `test` | `chore`

### 💡 Examples

```bash
git commit -m "feat: add login api"
git commit -m "fix: resolve navbar issue"
```

### ✅ Rules

- 5–10 words  
- Clear and meaningful  
- Small & frequent commits  
- ❌ Avoid: "update", "changes", "final"  

---

## 🚀 5. Push Branch

```bash
git push origin branch-name
```

---

## 🔀 6. Create Pull Request

- Open GitHub repo  
- Click **Compare & pull request**  
- Select correct base branch  
- Add title & description  
- Assign reviewer  

### 📝 PR Title

```
type: short summary
```

---

## 👀 7. Review Process

### Reviewer checks:
- Code quality  
- Logic & functionality  
- Task completion  

### Developer:
- Fix requested changes  
- Push updates  
- Wait for approval  

---

## ✅ 8. Merge Rules

- No merge without review  
- Only approved PRs  
- Code must be tested  

---

## 🔁 9. Workflow Summary

```txt
Start Work → Pull Latest Code → Create Branch → Work → Commit → Push → PR → Review → Merge
```

---

## ⚡ Important Notes

- 🚫 Never commit directly to `main`  
- 🌿 Always use feature branches  
- ✨ Keep commits clean  
- 🤝 Follow same workflow across team  
