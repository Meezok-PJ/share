Local README — Conversation Summary & Heads-up

Summary of what was done in this session:
- Read and confirmed .github/AGENT.md (workspace-manager spec).
- Initialized workspace/ taxonomy (projects, docs/homelab, docs/malware-lab, writeups/ctf, writeups/malware-analysis, notes/cheatsheets, notes/shared) with .gitkeep placeholders.
- Added a GitHub Actions workflow (.github/workflows/workspace-manager.yml) to enforce the taxonomy.
- Created docs/test.md and workspace/progress.md (committed locally).
- Created GitHub repo Meezok-PJ/share and pushed a clean repo whose root contains the workspace/ directory.
- Removed vault/ and docs/test.md from the repo as requested.
- Ensured workspace/ contains gh-setup-fedora.md with Fedora setup notes.
- Created and then removed local backup archives from the repo; added .gitignore to prevent future backups from being tracked.
- Force-pushed to origin/main so the remote reflects the finalized workspace-only structure.

Heads-up for you (Meezok):
- The repository on GitHub is: https://github.com/Meezok-PJ/share
- The repo root contains a single top-level folder workspace/ with the taxonomy and notes.
- Backup archives are intentionally not tracked by git; a finalized backup file is placed locally in workspace/ (not committed).
- When moving to Fedora: follow workspace/gh-setup-fedora.md to install gh and authenticate.

Heads-up for the agent (instructions):
- Do not commit large archives into the repository. Respect .gitignore: workspace/*.tar.gz must remain ignored.
- Only enforce and commit workspace/ content and small metadata/docs.
- When creating backups, place them in workspace/ but do not add/commit them.

Location of finalized backup: workspace/AGY_final_backup_<timestamp>.tar.gz (created now in this session)

If anything else should be excluded or cleaned (sensitive files, large binaries), list them and the agent will remove them and force-push the cleaned history if requested.
