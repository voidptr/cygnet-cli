# **The Symbiont Initiative \- Project Management Guide**

This document outlines the project management philosophy and workflow for our multi-agent development team.

## **1\. Our Tool: The GitHub Project Board**

All work for this project is tracked and managed using GitHub's native "Projects" board. This provides a single, centralized source of truth for all tasks, priorities, and statuses. The DEV\_JOURNAL.md is for logging the *process* of work; the Project Board is for tracking the *state* of work.

The board will use a standard Kanban-style layout:

* **Backlog:** The prioritized list of all approved tasks.  
* **To Do:** Tasks that are ready to be worked on in the current cycle.  
* **In Progress:** The task an agent is actively working on.  
* **In Review:** The task's Pull Request is open and awaiting review.  
* **Done:** The task has been successfully merged and deployed.

## **2\. The Role of the Product Manager**

The **Product Manager** agent is the sole owner and manager of the Project Board. Its responsibilities include:

* Writing clear, well-defined Issues with acceptance criteria.  
* Prioritizing the backlog to ensure the team is always working on the most valuable tasks.  
* Monitoring the board to identify blockers and facilitate communication.

## **3\. Project Zero: The Bootstrapping Plan**

We face a classic "chicken-and-egg" problem: our agents need tools to manage the project, but those tools must be built as part of the project. We will solve this with a temporary, file-based system.

1. **The Seed Backlog:** The initial set of tasks is defined in the INITIAL\_BACKLOG.md file.  
2. **The First Task:** The very first task for the Core Logic Developer is **Task 1: Build the GitHub API Integration tool**.  
3. **The Great Migration:** Once that tool is built and delivered, the very first task for the newly-empowered Product Manager agent is to programmatically read the rest of the INITIAL\_BACKLOG.md and migrate every single task into the official GitHub Project Board as a new Issue.  
4. **Deprecation:** Once the migration is complete, the INITIAL\_BACKLOG.md file will be formally archived, and the GitHub Project Board becomes the single source of truth for all future work.