---
description: Start a new thesis research task through the orchestrator pipeline
argument-hint: <describe the task, e.g. "draft Chapter 4 methodology">
---
Start a new task by following the Workflow section of CLAUDE.md.

Task: $ARGUMENTS

Steps:
1. Read `00_thesis_profile/thesis-profile.md` and `00_thesis_profile/academic-style-guide.md`.
2. Create the task workspace and write `00_brief.md`.
3. Tell me: the task type, the stages you will run (from the stage table), the agents you will use, and whether Stage 0 is needed because the RQs are DRAFT.
4. Wait for my confirmation before invoking any agent.
