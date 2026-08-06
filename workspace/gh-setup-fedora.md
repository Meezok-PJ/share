# GitHub CLI setup on Fedora

1. Install gh:
   sudo dnf install gh

2. Authenticate:
   gh auth login
   - Choose GitHub.com
   - HTTPS
   - Authenticate with web browser

3. Verify:
   gh auth status

4. Push existing repo:
   git remote add origin https://github.com/YOUR_USERNAME/REPO.git
   git push -u origin main

Notes:
- If you prefer SSH, generate a key with `ssh-keygen` and add it to your GitHub account.
- Use `gh repo create` to create repos from the CLI.
