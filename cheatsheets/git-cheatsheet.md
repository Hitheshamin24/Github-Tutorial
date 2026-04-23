# Git Cheatsheet

## Basic Commands

```bash
git init
git add .
git commit -m "message"
git status
git log
```

---

## Branching

```bash
git branch
git checkout -b feature-name
git merge branch-name
```

---

## Remote

```bash
git remote add origin <url>
git push -u origin main
git pull
git fetch
```

---

## Advanced

```bash
git rebase main
git stash
git stash pop
git cherry-pick <id>
git reset --hard HEAD~1
git revert <id>
```

---

## Tags

```bash
git tag v1.0
git push origin v1.0
```

---

## Quick Workflow

```bash
git add .
git commit -m "message"
git push
```

---

