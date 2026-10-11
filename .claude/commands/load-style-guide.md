---
description: Load the student's academic style guide into the shared style file all agents follow
argument-hint: <path to style guide file (PDF, DOCX, MD, TXT) or paste text after the command>
---
Load my academic style guide from: $ARGUMENTS

1. Read the source. For a PDF, use the Read tool with page ranges. For a DOCX, extract the text with `textutil -convert txt` into the scratchpad, never into this folder.
2. Extract every concrete, checkable rule and group the rules under: Citations & references, Structure & headings, Language & tone, Tense & person, Statistics reporting, Tables & figures, Formatting (font, spacing, margins), Word limits, Other.
3. Show me any rules that conflict with the APA 7 defaults currently in `00_thesis_profile/academic-style-guide.md`, and ask which rule wins.
4. After I confirm, rewrite `00_thesis_profile/academic-style-guide.md`: set STATUS to `LOADED (source: <file>, date)`, replace the "Student's style rules" section with the extracted rules, and keep the APA defaults only where my guide is silent.
5. Do NOT copy long passages verbatim. Write rules as short, checkable statements.
