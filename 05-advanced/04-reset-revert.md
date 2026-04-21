# Git Reset vs Revert

## Git Reset

Moves HEAD and removes commits.

```bash
git reset --hard HEAD~1
```

---

## Git Revert

Creates a new commit to undo changes.

```bash
git revert <commit-id>
```

---

## Difference

| Reset           | Revert        |
| --------------- | ------------- |
| Deletes history | Keeps history |
| Risky           | Safe          |

---

## When to Use

* Reset → local changes
* Revert → shared code

---

## Summary

Reset = Remove history
Revert = Undo safely
