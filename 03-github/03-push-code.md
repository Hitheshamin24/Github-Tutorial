# Pushing Code to GitHub

## Connect Local Repo to GitHub

```bash
git remote add origin https://github.com/username/repo-name.git
```

---

## Push Code

```bash
git push -u origin main
```

---

## Explanation

* origin → remote repo name
* main → branch name

---

## First Push Workflow

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <repo-url>
git push -u origin main
```

---

## Summary

Push = Upload local code to GitHub
