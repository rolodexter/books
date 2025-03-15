# Workflow Rules & Automation Standards

This document outlines the standard workflows and automation rules for managing this repository.

## **1. GitHub Workflow Rules**
- **Branching Strategy:**
  - `main` → Production-ready content only.
  - `dev` → Active development, experimental changes.
  - `feature/*` → Used for new books, scripts, or structural updates.
- **Commit Messages:**
  - Use concise, structured messages: `[module] Description` (e.g., `[bibliography] Added new citations`)
  - Reference related issues when applicable.
- **Pull Requests:**
  - All PRs must be reviewed before merging into `main`.
  - AI-generated changes must be labeled **AI-Aided** for transparency.

## **2. GitHub Actions & Automation**
- **Auto-formatting:**
  - Run formatting checks on Markdown and script files.
- **Bibliography Updates:**
  - Auto-sync new citations with `master.bib` when a new book entry is added.
- **TOC Generation:**
  - Automatically generate/update Table of Contents for books.
- **CI/CD for eBook Exports:**
  - Future automation to convert books to `.epub` and `.pdf` formats.

## **3. AI-Agent Execution Policy**
- AI agents should confirm changes before execution.
- High-risk changes (e.g., refactoring) must be reviewed manually.
- AI-generated documentation updates must be logged and versioned.

## **4. Task & Issue Management**
- All tasks should be tracked via GitHub Issues or project boards.
- Bugs should be tagged with `bug` and assigned priority labels (`high`, `medium`, `low`).
- Documentation updates should have `documentation` labels.

This document will evolve as the repository grows. 