# The skills rule

This is the section of my agents' contract that keeps the skills folder alive.

## Skill upkeep

- Check the skill index before a task and load any skill that covers it. Any agent may create, improve and push shared skills without asking.
- A workflow likely to recur gets a skill. Skip one-offs and chat, and extend a close skill rather than duplicate it. When a run proves a better method or finds a wrong step, fix the skill before finishing and add a dated one-line entry to its `CHANGELOG.md`. Record only steps that worked, in the house format, with no personal context, customer data or secrets.

## A real skill

This is my brief-back skill, whole.

```
---
name: brief-back
description: >-
  Use before handing a fuzzy research, comparison or build ask from the user to
  another bot or a cloud agent. Restate it in one line and get a nod first.
---
# Brief-back

## When
Before you send a research, comparison or build job to another bot or a cloud agent, and the user's ask is open-ended, spoken quickly, or could reasonably mean more than one deliverable.

Skip it when the ask is already specific (a named file, a fixed change, a clear yes/no lookup), when it's a routine's saved job, or when the user said to just go.

## Steps
1. Write one line back to the user: the question you'll answer and the deliverable you'll hand back. Example: "So: a one-page comparison of Obsidian vs your current setup, and whether you should switch. No build. Right?"
2. Name the size. Say whether it's a short answer, a memo or something built, and say so if other bots or a cloud agent would be involved.
3. Wait for a nod before handing it off. A short "yep" is enough. If the user is away, do the smallest safe read-only part yourself and hold the hand-off.
4. Hand off with that one line as the brief, word for word, so the receiving bot builds exactly that.
5. If the scope grows mid-job (a repo, a cloud agent, a second deliverable), stop and brief back again before growing it.

## Don't
- Don't turn this into a questionnaire. One line, one question.
- Don't brief back on every small ask; it's for fuzzy work that fans out.
```
