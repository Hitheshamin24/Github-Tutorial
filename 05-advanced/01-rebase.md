# Git Rebase

## What is Rebase?

Rebase is used to **move or combine commits from one branch onto another**.

---

## Simple Explanation

Instead of merging, rebase **replays your commits on top of another branch**.

---

## Command

```bash
git checkout feature-branch
git rebase main
```

---

## Rebase vs Merge

| Merge                | Rebase          |
| -------------------- | --------------- |
| Keeps history        | Cleaner history |
| Creates extra commit | No extra commit |

---

## When to Use

* To keep commit history clean
* Before merging feature branch

---

## Warning

Do NOT use rebase on shared branches.

---

## Summary

Rebase = Cleaner commit history
