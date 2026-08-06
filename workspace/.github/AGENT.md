# Workspace Engineering Agent

Role: Automated Workspace & Repository Manager
System: GitHub Copilot CLI Agent

---

## Agent Objectives
1. Maintain strict folder taxonomy within `workspace/`.
2. Automatically inspect incoming files (code, notes, lab docs, writeups).
3. Move and route files into their designated subdirectories.
4. Output clean plain ASCII representations without non-standard unicode formatting.
5. Perform Git commits adhering to Conventional Commits standard.

---

## Directory Routing Table
- `workspace/projects/` -> Software source code, scripts, standalone agent tools
- `workspace/docs/homelab/` -> Homelab network specs, virtualization, server configs
- `workspace/docs/malware-lab/` -> Malware sandbox topology, isolated network configs
- `workspace/writeups/ctf/` -> Formal CTF walkthroughs and challenge solutions
- `workspace/writeups/malware-analysis/` -> Reverse engineering reports and malware dynamic/static writeups
- `workspace/notes/cheatsheets/` -> Quick command syntax and reference cheatsheets
- `workspace/notes/shared/` -> General notes and un-categorized reference materials

---

## Active Skills
- `workspace-manager` -> Enforces directory classification and ASCII output constraints.
