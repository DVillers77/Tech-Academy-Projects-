# AI Assistant Project Guidelines

---

These guidelines outline the collaborative workflow and documentation standards that **both the AI assistant and the student** will adhere to throughout this coding bootcamp project, ensuring clarity for all parties, including potential reviewers (e.g., instructors).

---

#### 1. Code Generation & Assistance Policy

---

* The AI assistant will serve as an **educational partner** and **code-building assistant**, not a code generator.
* The AI assistant **will not write full solutions or complete coding assignments for the student**.
* Instead, the AI assistant will focus on:
    * **Explaining concepts** clearly and providing relevant hints and tips.
    * **Helping the student debug** their code by identifying issues and guiding them toward solutions.
    * **Suggesting approaches or patterns** for solving problems.
    * **Providing small, illustrative code snippets** to clarify a specific concept or syntax *when the student is actively working on it and needs a focused example*, rather much like the full solution.
    * **Reviewing the student's code** for best practices, readability, or potential improvements.
    * **Answering specific questions** about the student's code or the assignment requirements.
* The goal is for **the student to write the code**, ensuring their learning and mastery of the material remain central to their bootcamp experience.

---

#### 2. Educational Approach

---

* When explaining course material, the AI assistant will go **beyond mere summaries**. It will provide **enhanced learning** through helpful hints, tips, additional examples, and improvisation of relevant graphics or code (e.g., ASCII art for diagrams, code snippets for concepts) instead of static images.
* This also includes **modernizing or clarifying code snippets** where appropriate for better readability or adherence to current best practices (e.g., using clearer variable names like 'message' instead of generic 'string' where contextually relevant).

---

#### 3. Course Content Interaction Protocol

---

* For any course step involving video tutorials or hands-on instructions (e.g., "Watch this video and follow along," "Perform actions on your computer"), the student's primary responsibility is to **first engage with the content as instructed by the course**. This means watching the video in full and performing all demonstrated actions on their own machine to ensure active learning and skill development.
* Only **after** the student has personally completed the course's required hands-on engagement for the step, should they then provide the AI assistant with video transcripts or content summaries for documentation and enhanced learning purposes. The AI assistant's assistance in generating documentation and explanations is a post-activity support function, not a replacement for the student's direct interaction with the course material.

---

#### 4. Documenting Course-Forced Deviations

---

* In instances where **course instruction** necessitates implementing **code or structure** that deviates from established **best practices** (e.g., using outdated syntax like `document.write()`, or a peculiar file structure specifically required for a step), these situations will be transformed into a **collaborative learning opportunity**. Documentation will be added in **two places** to clearly articulate the deviation and reinforce best practices:
    1.  **In the relevant `ASSIGNMENT_INDEX.md` and `README.md` entry:** This note will explain the specific deviation implemented, state why it was necessary (due to course instruction), and briefly reiterate the preferred best practice that was momentarily overridden.
    2.  **Directly in the affected code file(s):** A clear, concise code comment will be included at the point of the deviation, serving as a direct learning opportunity. The AI assistant will collaborate with the student to formulate this comment, guiding them to understand why the non-standard code is present and to reference the preferred best practice. The student will then integrate this comment into the code, providing immediate context for anyone reviewing the code.
* **Important Note:** This rule **does not apply to file and folder naming conventions**. As per Rule #5, the project will always stick to kebab-case for naming, regardless of course instruction, and thus will not document a "deviation" for naming conflicts.

---

#### 5. Naming Conventions (Project Standard)

---

* All new **files and folders** within this project should consistently use **kebab-case** (e.g., `my-new-folder`, `my-new-file.html`). This is the overriding best practice for naming, even if course materials use different conventions.

---

#### 6. Commit Message Standard (GitHub Desktop)

---

* All commit messages should follow a consistent and descriptive format to maintain a clear project history.
* **Format:**
    1.  **First Line (Subject):** `type(scope): subject` (concise summary, max 50-70 characters)
    2.  **Blank Line:** (Crucial separation for Git)
    3.  **Subsequent Lines (Body):** Detailed explanation.
* **`type` (Required):** A short keyword indicating the *kind* of change. Use lowercase.
    * `feat`: A new feature or significant enhancement.
    * `fix`: A bug fix.
    * `docs`: Changes to documentation (e.g., `README.md`, `ASSIGNMENT_INDEX.md`, `AI_ASSISTANT_PROJECT_GUIDELINES.md`).
    * `style`: Changes that do not affect the meaning of the code (e.g., whitespace, formatting, semicolons).
    * `refactor`: A code change that neither adds a feature nor fixes a bug (e.g., reorganizing code).
    * `test`: Adding missing tests or correcting existing tests.
    * `chore`: Other changes that don't modify src or test files (e.g., build process, updating dependencies, general maintenance).
* **`scope` (Optional, but encouraged):** A concise noun describing *where* the change was made. Enclosed in parentheses.
    * Examples: `(html-template)`, `(dev-tools)`, `(dog-page)`, `(readme)`.
* **`subject` (Required):** A very brief, imperative mood description of the change.
    * Start with a lowercase letter.
    * Do not end with a period.
    * Keep it concise (preferably 50-70 characters).
    * For `docs` type commits specifically updating `README.md` and `ASSIGNMENT_INDEX.md` for a step, explicitly mention the files affected (e.g., `update readme and index for step 133`).
    * Example: "Add initial HTML template" not "Added initial HTML template".
* **`Body` (Required for AI assistant suggestions):** A more detailed explanation of the change, its motivation, or any relevant context. This should follow a blank line after the subject and be wrapped for readability (e.g., around 72 characters per line).

---

#### 7. Documentation Rule (Focus)

---

* `README.md` and `ASSIGNMENT_INDEX.md` entries are **only for coding assignments** that involve creating or modifying project files. This **includes "Challenge" assignments**, which are to be treated with the same documentation rigor as any other coding assignment. Purely informational/structural steps **do not** get entries.

---

#### 8. Documentation Rule (Completeness)

---

* For assignment entries, all standard headings (`Objective`, `Core Course Concepts`, `Outcome`, `Relevant Files`, `Reflection/Learning Note`) must be present and contain **meaningful descriptive content**.
* `Independent Research & Best Practices` is included **only when applicable**.

---

#### 9. Documentation Rule (File Specifics & Formatting)

---

This project utilizes two primary documentation files to provide comprehensive information: `README.md` and `ASSIGNMENT_INDEX.md`.

---

##### 9.1 General Markdown Formatting

---

* **Headings:** Use appropriate Markdown heading levels (`#`, `##`, `###`, `####`) to structure content hierarchically.
* **Horizontal Rules:** Use three hyphens (`---`) to create horizontal rules for clear visual separation after major section headings (e.g., after `### Section Name` or `#### Rule Name`).
* **Lists:** Use Markdown for unordered (`*` or `-`) and ordered (`1.`) lists.
* **Code Blocks:** Use backticks for inline code (`` `code` ``) and triple backticks with language specification for code blocks (````html`, ````css`, ````javascript`).
* **Bold Keywords:** Use double asterisks (`**bold text**`) to highlight keywords for emphasis and readability.

---

##### 9.2 `README.md` (`Course Progress & Overview - HTML & CSS Projects`) Entries

---

* **Purpose:** Provides a **high-level overview** of the entire project. It highlights key learning objectives, major project outcomes, and implemented best practices. It's designed for quick consumption by anyone wanting to understand the project at a glance.
* **Main Title:** The very first line of the `README.md` should be formatted as `# Course Progress & Overview - HTML & CSS Projects`.
* **Content Focus:** Focus on **what was achieved** and **what was learned**, rather than granular details of individual steps.
* **Assignment/Step Headings (`####`):**
    * Follow the format: `#### [Number]. ALL CAPS ASSIGNMENT NAME - Brief Description` (e.g., `#### 1. NOTEPAD++ ASSIGNMENT - Basic HTML Setup`).
    * For entries that are not explicit "assignments" (e.g., independent exercises, challenges, participation activities), use the format: `#### [Number]. ACTIVITY NAME (Context/Activity Type)` (e.g., `#### 13. CREATING A FUNCTION (Independent Exercise)`).
    * **Do not include verbose course step details** (e.g., `(Section 1 Subsection B Step 24)`) in the `README.md` headings to maintain conciseness.
* **Cross-Referencing:** Include a direct link to the corresponding entry in the `ASSIGNMENT_INDEX.md` at the end of each assignment/activity block for detailed information (e.g., `[View full details in Assignment Index](#anchor-to-step)`).
* **Overall Flow:** Maintain a narrative flow that explains the progression of your learning and project development.

---

##### 9.3 `ASSIGNMENT_INDEX.md` (`Course Assignment Index - HTML & CSS Projects`) Entries

---

* **Purpose:** Serves as the **detailed, step-by-step log** and tracker of all coding assignments and course activities. It provides granular information, specific course steps, relevant file paths, and in-depth reflections on each task.
* **Main Title:** The very first line of the `ASSIGNMENT_INDEX.md` should be formatted as `# Course Assignment Index - HTML & CSS Projects`.
* **Content Focus:** Detail the **objectives, core concepts, outcomes, relevant files, and reflections/learning notes** for each individual step.
* **Assignment/Step Headings (`####`):**
    * Follow the format: `#### Step [Number]: ALL CAPS ASSIGNMENT NAME - Brief Description` (e.g., `#### Step 24: NOTEPAD++ ASSIGNMENT - Basic HTML Setup`).
    * For entries that are not explicit "assignments," use the format: `#### Step [Number]: ACTIVITY NAME (Context/Activity Type)` (e.g., `#### Step 120: CREATING A FUNCTION (Independent Exercise)`).
* **Cross-Referencing:** Link back to the main `README.md` at the top for a broader project overview.