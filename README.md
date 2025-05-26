# 📘 Git Command Cheat Sheet

## 🔰 Basic Git Commands (Initial Setup)

- **Initialize a Git repository:**
  ```bash
  git init
  ```

- **Add all files to staging:**
  ```bash
  git add .
  ```

- **Change default branch name (Optional):**
  ```bash
  git branch -M main
  ```

- **Commit staged files:**
  ```bash
  git commit -m "your commit message"
  ```

- **Bind local project with GitHub repository:**
  ```bash
  git remote add origin <REPO_URL>
  ```

- **Push to GitHub (first-time push):**
  ```bash
  git push -u origin main
  ```

## 🛠️ Daily Workflow Commands

- **Create and switch to a new branch (or just switch if exists):**
  ```bash
  git checkout -b branch_name
  ```

- **Stage all changes:**
  ```bash
  git add .
  ```

- **Temporarily save current changes (stash):**
  ```bash
  git stash
  ```

- **Fetch latest changes from remote:**
  ```bash
  git fetch
  ```

- **Pull latest changes from main branch:**
  ```bash
  git pull origin main
  ```

- **Apply previously stashed changes:**
  ```bash
  git stash pop
  ```

- **Stage changes again after resolving conflicts (if any):**
  ```bash
  git add .
  ```

- **Commit your final changes:**
  ```bash
  git commit -m "your commit message"
  ```

- **Push your branch to remote:**
  ```bash
  git push origin branch_name
  ```
