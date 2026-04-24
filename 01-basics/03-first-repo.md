# Creating Your First Git Repository

## What is a Repository?

A repository (repo) is a folder where Git tracks your project.

---

## Steps to Create Repo

### 1. Create a folder

```bash
mkdir my-project
cd my-project
```

---

### 2. Initialize Git

```bash
git init
```

 This creates a hidden `.git` folder

---

### 3. Create a file

```bash
echo "Hello Git" > file.txt
```

---

### 4. Add file to staging

```bash
git add file.txt
```

---

### 5. Commit changes

```bash
git commit -m "First commit"
```

---

