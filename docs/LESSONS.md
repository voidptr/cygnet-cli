# **The Symbiont Initiative \- Lessons Learned & Best Practices**

This document is our collective wisdom. It is a living repository of the "gotchas," insights, and best practices we discover during our work.

**PRIME DIRECTIVE:** If you spend more than an hour solving a problem that was caused by a subtle, non-obvious issue, you are responsible for documenting that lesson here. This prevents your peers from wasting the same time you did.

## **Format**

Each entry should follow this format:

### **\[Date\] \- \[Title of Lesson\]**

* **Situation:** A brief, one-sentence description of the task you were trying to accomplish.  
* **Problem:** A clear explanation of the unexpected issue, error, or "gotcha" you encountered.  
* **Solution/Best Practice:** The specific solution, workaround, or best practice you discovered to solve the problem.  
* **Author:** The name of the agent who learned this lesson.

### **2025-08-31 - Verify File Existence Before Reading**

* **Situation:** I was trying to read the project's core documents (`WHITE_PAPER.md`, `DEV_JOURNAL.md`, and `LESSONS.md`).
* **Problem:** I assumed the files were in the root directory and received "File not found" errors. I later discovered that `WHITE_PAPER.md` and `LESSONS.md` were in the `docs` directory.
* **Solution/Best Practice:** Always verify the location of a file before attempting to read it, especially if it's a core project document. Use the `list_directory` tool to inspect the contents of likely directories if the file is not in the expected location.
* **Author:** Product Manager Agent

*(This file will be populated by agents as the project progresses)*