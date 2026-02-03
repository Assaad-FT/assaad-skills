# How to Set Up This Repository on GitHub

## Step 1: Create the Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `assaad-skills`
3. Description: `Financial analysis frameworks — 48 legendary investors`
4. Select **Private** (this is your intellectual property)
5. Check **Add a README file**
6. Click **Create repository**

## Step 2: Upload the Files

### Option A: GitHub Web Interface (Easiest)

1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop the entire contents of the `assaad-skills` folder
3. Click **Commit changes**

Note: GitHub web upload doesn't preserve folder structure well.
Better to upload folder by folder:

1. Click **Add file** → **Create new file**
2. Type `master/analyst-frameworks.md` (this creates the folder automatically)
3. Paste the file contents
4. Click **Commit changes**
5. Repeat for each file

### Option B: Claude Code (Recommended)

Open Claude Code in the `assaad-skills` folder and say:

```
Initialize a git repository, add all files, and push to GitHub 
as a private repo called assaad-skills
```

Claude Code will run:
```bash
git init
git add .
git commit -m "Initial commit: 48 analyst frameworks"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/assaad-skills.git
git push -u origin main
```

### Option C: GitHub Desktop App

1. Download GitHub Desktop from https://desktop.github.com
2. Sign in with your GitHub account
3. File → Add Local Repository → select the `assaad-skills` folder
4. It will offer to create a repository — click Create Repository
5. Click **Publish repository** → set to Private → Publish

## Step 3: Verify

Go to `https://github.com/YOUR_USERNAME/assaad-skills`

You should see:
```
master/
  analyst-frameworks.md
  fixed-income-frameworks.md
  investing-principles.md
claude/
  analyst-frameworks.yaml
  fixed-income-frameworks.md
  investing-principles.md
gemini/
  system-instructions.md
chatgpt/
  custom-gpt-instructions.md
README.md
```

## Step 4: Connect to the Financial Analyst App

In the app settings, set the GitHub repo path to:
```
YOUR_USERNAME/assaad-skills/main
```

The app will pull skills from:
```
https://raw.githubusercontent.com/YOUR_USERNAME/assaad-skills/main/master/analyst-frameworks.md
https://raw.githubusercontent.com/YOUR_USERNAME/assaad-skills/main/master/fixed-income-frameworks.md
https://raw.githubusercontent.com/YOUR_USERNAME/assaad-skills/main/master/investing-principles.md
```

## Important: Private Repository Access

If your repository is **private** (recommended), the raw GitHub URLs won't work 
without authentication. You have two options:

### Option 1: Make the repo Public
Simplest. The raw URLs work immediately. Your frameworks are visible to anyone though.

### Option 2: Use a GitHub Personal Access Token
1. Go to https://github.com/settings/tokens
2. Generate new token (classic)
3. Select `repo` scope
4. Copy the token
5. The app would need to include this token in fetch headers

For personal use, Option 1 (public) is fine — the frameworks are synthesized 
from publicly available research. No proprietary data is exposed.
