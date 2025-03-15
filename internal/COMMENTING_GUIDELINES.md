# Commenting Guidelines

This document provides best practices for commenting within code and documentation files.

## **1. General Commenting Principles**
- **Keep comments clear and concise**.
- **Avoid redundant comments** that simply restate the code.
- **Use comments to explain intent**, not just functionality.

## **2. Code Commenting Best Practices**
- Use **inline comments** (`#` for Python, `//` for JavaScript) for small clarifications.
- Use **block comments** (`/* */` or `""" """`) for explaining complex logic.
- **Tag important comments**:
  - `TODO:` - Something that needs to be completed.
  - `FIXME:` - A known issue that requires fixing.
  - `NOTE:` - Important observations about the code.

## **3. Markdown Documentation Commenting**
- Use `> Blockquotes` for **notes and callouts**.
- Use `<!-- HTML Comments -->` for **internal comments that shouldn't be displayed**.

## **4. AI-Generated Code Comments**
- Any AI-generated code **must be labeled** with `# AI Generated - Review Required`.
- AI-suggested optimizations **must be confirmed** before being added.

## **5. Best Practices for Multi-Contributor Environments**
- Include **initials or timestamps** for critical comments when necessary.
- When modifying another person's code, **preserve original comments** and add clarifications instead of deleting them.

This document will be periodically updated as new commenting standards evolve. 