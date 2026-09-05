# DevOps Task 4 – Version-Controlled Project with Git

## 📌 Objective
This repository demonstrates Git best practices as part of the DevOps Internship (Task 4), including branching, pull requests, tagging, and proper documentation.

## 🛠 Tools Used
- Git
- GitHub

## 🌳 Branching Strategy
- `main` – stable, production-ready code
- `dev` – integration branch for ongoing development
- `feature/*` – individual feature branches created off `dev`

## 🔄 Workflow
1. Created `main` branch and pushed initial commit.
2. Created `dev` branch from `main`.
3. Created `feature/add-script` branch from `dev` for new changes.
4. Added `hello.py` as a sample feature.
5. Opened a Pull Request to merge `feature/add-script` → `dev`.
6. Opened a Pull Request to merge `dev` → `main`.
7. Tagged the stable release as `v1.0`.

## 🏷 Tags
- `v1.0` – First stable release after merging dev into main.

## ✅ Outcome
Learned and applied Git version control workflows including branching, pull requests, conflict resolution, and tagging.