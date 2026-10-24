# Upload this project to GitHub

## Option A — GitHub website (no terminal)
1. Sign in to https://github.com and create a new repository (for example: `apparel-textiles-ux-report`).
2. Keep the repository Public or Private as required by your assignment.
3. Choose **Add file → Upload files**.
4. Upload `Apparel_Textiles_Frontend_Prototype_UX_Report.docx`, `README.md`, and the `figures` folder (upload the files inside it).
5. Add a commit message such as `Add Week 2 apparel UX report` and click **Commit changes**.

## Option B — Git command line
Install Git, then open a terminal in the folder containing the report files. Replace `YOUR-USERNAME` with your GitHub username.

```bash
git init
git add .
git commit -m "Add Week 2 apparel and textiles UX report"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/apparel-textiles-ux-report.git
git push -u origin main
```

If Git asks you to sign in, complete the GitHub browser authentication flow or use a GitHub personal access token when prompted. Do not put passwords or tokens directly into the command or repository.

If the repository already exists and contains a README, clone it first and copy these files into that cloned folder before running `git add`, `git commit`, and `git push`.
