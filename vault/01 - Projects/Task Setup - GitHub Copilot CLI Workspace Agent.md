---
title: Task Setup - GitHub Copilot CLI Workspace Agent
date: 2026-08-06
tags:
  - project
  - workspace
  - setup
  - copilot-cli
type: project-task
status: completed
---

# Task Setup: GitHub Copilot CLI Workspace Agent

> [!info] Summary
> Configured and bootstrapped the complete **GitHub Copilot CLI Workspace Agent** structure and skills configuration inside the Obsidian Vault under `01 - Projects/`.

---

## Workspace Structure Created

The core workspace has been initialized in `workspace/` with standard folder taxonomy:

```text
workspace/
|-- projects/
|-- docs/
|   |-- homelab/
|   `-- malware-lab/
|-- writeups/
|   |-- ctf/
|   `-- malware-analysis/
|-- notes/
|   |-- cheatsheets/
|   `-- shared/
`-- .github/
    |-- copilot-instructions.md
    `-- skills/
        `-- workspace-manager/
            `-- SKILL.md
```

---

## Component Details

### 1. Copilot Agent Instructions
- File: `workspace/.github/copilot-instructions.md`
- Purpose: Defines system rules for Copilot CLI, directory taxonomy enforcement, and clean Git commit rules.

### 2. Workspace Manager Skill
- File: `workspace/.github/skills/workspace-manager/SKILL.md`
- Purpose: Custom skill instructions for automatic routing of incoming files into designated folders.

---

## Next Steps & Maintenance

1. Integrate upcoming security tools into `workspace/projects/`.
2. Save raw research notes into `workspace/notes/` before processing into formal writeups.
3. Link related investigation notes in Obsidian using standard `[[wikilinks]]`.
