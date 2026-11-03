---
name: dashboard-builder
description: Builds or refreshes a one-page personal dashboard from your priorities, work in progress, things you're waiting on, key numbers and this week's plans. Use for a start-of-day or Monday snapshot, or when your notes are scattered and you want one page to glance at.
---

# Dashboard builder

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

Turn the scattered notes in your head into one clean page you can glance at each morning: what matters, what is moving, what you are waiting on, and the numbers that tell you if you are winning.

## Purpose

This skill builds or refreshes a simple one-page personal dashboard. You give the AI the raw bits: your priorities, the work in progress, the things you are waiting on from other people, a few key numbers, and what is happening this week. It hands back a tidy, scannable summary in plain text or a Markdown table.

The point is not a fancy tool. The point is one page you actually look at. Most people lose track of work because it lives in fifteen places. This pulls it into one, in under a minute, and you can run it again whenever the picture changes.

## When to use

Reach for this when:

- You want a Monday-morning or start-of-day snapshot of everything on your plate.
- Your notes, tasks and reminders are spread across email, chat, a notebook and your memory, and none of it adds up to a clear view.
- You are about to refresh an existing dashboard with new updates rather than start from scratch.
- You need a quick status page to share with a manager or a teammate without writing a long report.

Skip it if you only have one or two things on, or if you need a live tool that auto-updates from your systems. This is a manual snapshot. It is only as current as what you paste in.

## Required inputs

You do not need all of these, but the more you give, the more useful the page. Leave any section blank and the AI will mark it as empty rather than invent something.

- Priorities: the 3 to 5 things that matter most right now, in rough order.
- In progress: work you have actively started but not finished.
- Waiting on: things stuck with other people, with who owns each one and, if you know it, when you expect it back.
- Key numbers: a handful of metrics you track, with the current value and, optionally, a target or last week's value.
- This week: meetings, deadlines or events coming up in the next seven days.
- Output format: do you want a plain-text version, a Markdown table version, or both.

## Safety checks

- Real inputs only. The AI must use exactly what you give it and must not invent priorities, numbers or commitments. If a section is empty, it should say so, not fill the gap.
- Check the numbers yourself. The AI is copying figures, not calculating or verifying them. If it adds up totals or percentages, treat those as a draft and confirm them.
- Mind what you paste. If your inputs include client names, salaries, health details or anything sensitive, you are putting that into an AI tool. Use a work-approved tool for work data, and strip out anything that should not leave your head.
- It is a snapshot, not a source of truth. The dashboard reflects the moment you built it. Do not treat last Tuesday's version as today's reality.

## Process

The AI should follow these steps.

1. Read all the inputs and sort each item into the right section: priorities, in progress, waiting on, key numbers, this week. If something is unclear, place it where it best fits and note the ambiguity at the end rather than guessing silently.
2. For priorities, keep them in the order given. If no order was given, list them as provided and do not rank them.
3. For waiting on, show three things per item where available: what it is, who owns it, and the expected date. Mark anything past its expected date clearly.
4. For key numbers, show the current value, and the target or comparison value if one was given. Do not calculate trends unless the user provided the figures to do so.
5. For this week, list items in date order, soonest first.
6. Build the dashboard in the requested format: plain text, Markdown table, or both. Keep it to one page. Use short lines, no long paragraphs.
7. At the bottom, add a short "Needs your input" note listing any empty sections, anything that looked ambiguous, and any number worth double-checking. If nothing needs attention, say so in one line.

## Copy-paste prompt

```
You are helping me build a simple one-page personal dashboard.

Use ONLY the information I give you below. Do not invent priorities,
tasks, numbers, dates or commitments. If a section is empty, label it
"(nothing listed)" rather than filling it in.

Here are my inputs:

PRIORITIES (top 3-5, in order if I gave an order):
[PASTE PRIORITIES]

IN PROGRESS (started but not finished):
[PASTE IN-PROGRESS WORK]

WAITING ON (item / who owns it / expected date, where known):
[PASTE WAITING-ON ITEMS]

KEY NUMBERS (metric / current value / target or last value, where known):
[PASTE KEY NUMBERS]

THIS WEEK (meetings, deadlines, events in the next 7 days):
[PASTE THIS WEEK]

OUTPUT FORMAT I WANT: [PLAIN TEXT / MARKDOWN TABLE / BOTH]

Now do this:
1. Sort each item into the right section.
2. Keep my priorities in the order I gave.
3. For waiting-on items, flag anything past its expected date.
4. List "this week" in date order, soonest first.
5. Do not calculate trends or totals unless I gave you the figures to do it.
6. Keep the whole dashboard to one page with short lines.
7. End with a short "Needs your input" note listing any empty sections,
   anything ambiguous, and any number worth me double-checking. If
   nothing needs attention, say so in one line.
```

## Expected output

A single page, headed with the date, containing five clearly labelled sections (Priorities, In progress, Waiting on, Key numbers, This week) in the format you asked for. Each section is short and scannable. Waiting-on items show owners and dates, with overdue ones flagged. The numbers appear with their current and comparison values side by side. At the bottom, a brief "Needs your input" note tells you what was missing, unclear, or worth checking.

What you should not see: invented tasks, made-up figures, ranked priorities you did not rank, or a wall of text. If the AI calculated anything, it should be obvious so you can verify it.

## Review checklist

Before you trust the page, check:

- [ ] Every item came from your inputs. Nothing was invented or padded.
- [ ] Priorities are in the order you intended.
- [ ] Waiting-on items name the right owners, and overdue flags are correct.
- [ ] Any number the AI calculated has been checked by you.
- [ ] Empty sections are honestly marked, not quietly filled.
- [ ] The "Needs your input" note matches what you actually know is missing.
- [ ] It fits on one page and you can scan it in ten seconds.
