# AI Assistant Project Guidelines
---

These guidelines outline the standards for collaboration, documentation, and project structure for the HTML & CSS bootcamp projects. Adhering to these principles ensures consistency, readability, and maintainability across all project contributions.

---

## 1. Project Structure and Naming Conventions
---

* **Repository Organization:**
    * Maintain a clear and logical folder structure (e.g., `html-documents/`, `css/`, `images/`, `javascript-examples/`).
    * Group related files within appropriate directories.
* **File and Folder Naming:**
    * Use **kebab-case** (e.g., `my-new-file.html`, `image-assets/`) for all file and folder names. This ensures cross-platform compatibility and readability.
    * Avoid spaces, underscores, or camelCase in names.

---

## 2. Code Standards
---

* **HTML:**
    * Always include the `<!DOCTYPE html>` declaration.
    * Ensure proper indentation (e.g., 2 or 4 spaces consistently).
    * Use semantic HTML5 elements where appropriate (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`, `aside`).
    * Maintain correct nesting of elements.
    * Include a `<meta charset="utf-8">` tag in the `<head>` for proper character encoding.
    * Place `<title>` tags within the `<head>` element, providing a descriptive title for each page.
    * For JavaScript, place `<script>` tags just before the closing `</body>` tag to ensure HTML content loads quickly and is available for script manipulation without render-blocking.
* **CSS:** (Anticipated future additions for CSS best practices)
* **JavaScript:** (Anticipated future additions for JavaScript best practices)
* **Comments:** Use comments judiciously to explain complex logic, non-obvious choices, or sections of code that might require future clarification.
    * **HTML Comments:** Use `` for developer notes within HTML files.
    * **In-Code Documentation for Live Pages:** For notes meant to be visible in the source code but *not* rendered on the live webpage, use `<script type="text/plain">Your developer note here</script>`.

---

## 3. Documentation Standards
---

This project utilizes two primary documentation files to provide comprehensive information: `README.md` and `ASSIGNMENT_INDEX.md`.

### 3.1. General Markdown Formatting
---

* **Headings:** Use appropriate Markdown heading levels (`#`, `##`, `###`, `####`) to structure content hierarchically.
* **Horizontal Rules:** Use three hyphens (`---`) to create horizontal rules for clear visual separation after major section headings (e.g., after `### Section Name`).
* **Lists:** Use Markdown for unordered (`*` or `-`) and ordered (`1.`) lists.
* **Code Blocks:** Use backticks for inline code (`<code>`) and triple backticks with language specification for code blocks (````html`, ````css`, ````javascript`).
* **Bold Keywords:** Use double asterisks (`**bold text**`) to highlight keywords for emphasis and readability.

### 3.2. `README.md` (`Course Progress & Overview - HTML & CSS Projects`)
---

* **Purpose:** Provides a **high-level overview** of the entire project. It highlights key learning objectives, major project outcomes, and implemented best practices. It's designed for quick consumption by anyone wanting to understand the project at a glance.
* **Main Title:** The very first line should be `# Course Progress & Overview - HTML & CSS Projects`.
* **Content Focus:** Focus on **what was achieved** and **what was learned**, rather than granular details of individual steps.
* **Assignment/Step Headings (`####`):**
    * Follow the format: `#### [Number]. ALL CAPS ASSIGNMENT NAME - Brief Description` (e.g., `#### 1. NOTEPAD++ ASSIGNMENT - Basic HTML Setup`).
    * For entries that are not explicit "assignments" (e.g., independent exercises, challenges, participation activities), use the format: `#### [Number]. ACTIVITY NAME (Context/Activity Type)` (e.g., `#### 13. CREATING A FUNCTION (Independent Exercise)`).
    * **Do not include verbose course step details** (e.g., `(Section 1 Subsection B Step 24)`) in the `README.md` headings to maintain conciseness.
* **Cross-Referencing:** Include a direct link to the corresponding entry in the `ASSIGNMENT_INDEX.md` at the end of each assignment/activity block for detailed information (e.g., `[View full details in Assignment Index](#anchor-to-step)`).
* **Overall Flow:** Maintain a narrative flow that explains the progression of your learning and project development.

### 3.3. `ASSIGNMENT_INDEX.md` (`Course Assignment Index - HTML & CSS Projects`)
---

* **Purpose:** Serves as the **detailed, step-by-step log** and tracker of all coding assignments and course activities. It provides granular information, specific course steps, relevant file paths, and in-depth reflections on each task.
* **Main Title:** The very first line should be `# Course Assignment Index - HTML & CSS Projects`.
* **Content Focus:** Detail the **objectives, core concepts, outcomes, relevant files, and reflections/learning notes** for each individual step.
* **Assignment/Step Headings (`####`):**
    * Follow the format: `#### Step [Number]: ALL CAPS ASSIGNMENT NAME - Brief Description` (e.g., `#### Step 24: NOTEPAD++ ASSIGNMENT - Basic HTML Setup`).
    * For entries that are not explicit "assignments," use the format: `#### Step [Number]: ACTIVITY NAME (Context/Activity Type)` (e.g., `#### Step 120: CREATING A FUNCTION (Independent Exercise)`).
* **Cross-Referencing:** Link back to the main `README.md` at the top for a broader project overview.

---

## 4. Git and Version Control
---

* **Commit Messages:** Write clear, concise, and descriptive commit messages. Aim for messages that explain *what* was changed and *why*.
* **Branching Strategy:** (Anticipated future additions for branching strategy)
* **Regular Commits:** Commit frequently with small, logical changes.

---

## 5. Collaboration Guidelines
---

* **Communication:** Maintain open and clear communication.
* **Conflict Resolution:** (Anticipated future additions for conflict resolution)