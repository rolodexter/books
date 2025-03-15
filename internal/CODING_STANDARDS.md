# Coding Standards & Best Practices

This document provides guidelines for maintaining clean, consistent, and readable code within the repository.

## **1. General Code Style**
- Use **consistent indentation** (4 spaces per level).
- Use **camelCase** for variable and function names.
- Use **snake_case** for filenames and JSON keys.
- Keep line length **under 80 characters** where possible.

## **2. Markdown Formatting**
- Use `#` headers in hierarchical order.
- Bold important terms with `**bold**`.
- Use `inline code blocks` for technical terms.
- Tables should use `|` alignment for readability.

## **3. Commenting Guidelines**
- Use **descriptive comments** for all functions and major sections.
- Keep comments **concise but informative**.
- Use **TODO:** or **FIXME:** for pending improvements.

## **4. AI-Generated Code Guidelines**
- AI-generated code **must be reviewed** before execution.
- Clearly mark AI-generated code with `# AI Generated - Review Required`.
- Any AI-suggested refactoring must be confirmed before applying changes.

## **5. Script Organization & File Naming**
- Place scripts in `/scripts/` with clear filenames (`update_bib.js`, `generate_toc.py`).
- Use `README.md` in script folders to document their purpose.

## **6. Versioning & Tracking**
- Use **semantic versioning** (`v1.0`, `v1.1`) for automation scripts.
- Always commit major script changes with detailed commit messages.

This document will be updated as new best practices are introduced. 