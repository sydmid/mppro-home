# AI Agent Operational Instructions for Daily Scheduled Tasks

This document contains guidelines and procedures for AI Agents running scheduled daily execution tasks on the **MPPRO** codebase according to `DAILY_EXECUTION_PLAN.md`.

---

## 1. Daily Execution Protocol

For each scheduled daily execution run, the AI Agent must follow this 5-step procedure:

1. **Identify the Target Day**:
   - Determine which day of the 14-day schedule (`DAILY_EXECUTION_PLAN.md`) is being executed.
   - Read the corresponding section in `DAILY_EXECUTION_PLAN.md` to get the target files, objectives, and specific prompts.

2. **Inspect Existing Files**:
   - Use `read_file` to review the target files (e.g., `index.html`, `css/style.css`, etc.) to understand current structure and formatting conventions.

3. **Perform the Code / Content Changes**:
   - Apply edits using targeted search-and-replace (`replace_with_git_merge_diff`) or new file creation (`write_file`).
   - Follow RTL (Right-to-Left) layout conventions and Persian language content quality standards.
   - Use existing UI design system classes (`btn-fourteen`, `card-style-three`, `title-style-five`, `font-irsans`, `tx-dark`).

4. **Verify Your Work**:
   - Use `read_file` to inspect modified or newly created files to confirm edits were applied accurately without syntax errors or missing HTML closing tags.
   - Run syntax or link integrity checks via bash tools if applicable.

5. **Commit & Record**:
   - Run pre-commit checks and submit changes using descriptive git commit messages following the convention: `feat(day-X): description of changes`.

---

## 2. Design System & Code Quality Guidelines

- **Typography & Font**: Ensure all primary heading and text elements preserve standard classes (e.g. `font-irsans`, `fw-bold`, `tx-dark`).
- **Text Direction**: Preserve `dir="rtl"` attributes on container elements, headers, accordions, and text blocks.
- **Responsive Layout**: Utilize Bootstrap 5 grid system classes (`col-lg-*`, `col-md-*`, `col-12`) and flex utilities (`d-flex`, `align-items-center`, `justify-content-between`).
- **Icons**: Utilize existing theme icons in `images/icon/` or Bootstrap Icons (`bi bi-*`) / FontAwesome (`fa-solid fa-*`).

---

## 3. Pre-Commit Verification Rules

Before finalizing any daily execution step, the AI Agent MUST:
1. Verify that HTML markup contains properly closed tags and valid attributes.
2. Confirm that newly added links route correctly relative to root.
3. Ensure no existing styles or JavaScript theme initializers are broken.
4. Verify that mobile navigation drawer and responsive views function correctly.
