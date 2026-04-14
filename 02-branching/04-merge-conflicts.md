# Merge Conflicts

## What is Conflict?

When two branches modify the same file or line.

---

## Example

```
Branch A: Hello World
Branch B: Hello Git
```

Git cannot decide which change to keep.

---

## How to Resolve

1. Open conflicted file
2. You will see:

```
<<<<<<< HEAD
Hello World
=======
Hello Git
>>>>>>> feature
```

3. Edit manually
4. Save file

---

## Final Steps

```bash
git add .
git commit -m "Resolved conflict"
```

---

## Summary

Conflict = Same line edited in multiple branches
