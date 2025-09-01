# **The Symbiont Initiative \- Archiving Guide**

This document defines the formal, mandatory process for archiving historical documents. Our goal is to preserve the project's history and institutional memory without creating confusion for agents who are looking for the current, canonical version of a document.

**PRIME DIRECTIVE:** Do not simply delete an outdated file. Follow this process.

## **The Archiving Workflow**

1. **Identify the Outdated Document:** You have identified a document (e.g., OLD\_PLAN.md) that is no longer the current source of truth.  
2. **Find its Replacement:** Locate the current, canonical document or section that has superseded the old one. If one does not exist, you must create it first.  
3. **Create the Status Header:** At the very top of the outdated document, add the following standardized markdown header. This is the "plaque" that immediately contextualizes the file for any agent who opens it.  
   \---  
   \*\*STATUS:\*\* Superseded  
   \*\*DATE:\*\* \[YYYY-MM-DD of archiving\]  
   \*\*REASON:\*\* \[A brief, one-sentence explanation of why this document is outdated.\]  
   \*\*REPLACED\_BY:\*\* \[Link to the new, canonical document or section.\]  
   \---

   (The original content of the document follows below this header.)

4. **Move the File:** Move the outdated file into the /ARCHIVES directory. If it belongs in a specific subdirectory (e.g., /ARCHIVES/past\_conversations/), place it there.  
5. **Update the Manifest:** The final, crucial step is to update the master index. Open the /ARCHIVES/manifest.md file and add a new entry for the document you just archived.  
   | Document Link                 | Status       | Summary                                         | Replaced By                            |  
   | \----------------------------- | \------------ | \----------------------------------------------- | \-------------------------------------- |  
   | \`\[OLD\_PLAN.md\](./OLD\_PLAN.md)\` | \`Superseded\` | "The initial, flawed project plan from week 1." | \`\[PROJECT\_BOARD.md\](../PROJECT\_BOARD.md)\` |

6. **Update Links:** If any other active documents link to the old file, update them to point to the new, canonical version.

By following this process, we ensure that our project's history is preserved in a structured and non-confusing way.