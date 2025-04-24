# 🧠 Dev Terminal Cheatsheet

A growing list of useful commands and workflows as I learn software development.

---

## 🔧 Git Basics

### Clone a repo
```bash
git clone https://github.com/yourusername/repo-name.git
```

### Add, commit, and push
```bash
git add .
git commit -m "your message"
git push origin main
```

### One-liner fast push (Mac/Linux Only)
```bash
git add . && git commit -m "update" && git push
```

---

## 🛠 Terminal Commands

### See your current directory
```bash
pwd            # macOS/Linux
Get-Location   # PowerShell
```

### List files (including hidden ones)
```bash
ls -a              # macOS/Linux
dir -Force         # PowerShell
```

### Open current folder in VS Code
```bash
code .
```

---

## 🌐 GitHub Pages

### Enable GitHub Pages
1. Go to **Settings** → **Pages**
2. Source: `main` branch, `/ (root)` folder

Site will be published at:  
`https://yourusername.github.io/repo-name/`

---

## ⚙️ YAML Tips (`_config.yml`)

- Use spaces, not tabs
- Indent consistently
- Comment with `#`
- Structure matters!

---

_Add more as I go!_