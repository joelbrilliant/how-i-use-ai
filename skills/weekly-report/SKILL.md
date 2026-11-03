---
name: weekly-report
description: Turns a week of rough notes, messages and numbers into a short weekly update with wins, blockers and next steps. Use when a recurring weekly report is due.
---

# Weekly report

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

Turn a week of messy notes, done items and numbers into a tidy status report your boss or team will actually read.

## Purpose

Most of us finish the week with a scatter of evidence: a few notes, a to-do list with things crossed off, a couple of numbers, some emails. Writing that up into a clean report is fiddly and easy to put off. This skill does the assembly for you. You hand the AI your raw week, it gives you back a structured report with highlights, progress against your goals, risks or blockers, and a plan for next week. You stay the editor. It does the typing.

## When to use

- You send a weekly update to a manager, client or team and want it to read well without spending half an hour on it.
- You keep loose notes through the week and need them pulled into something presentable.
- You are juggling several projects and want one clear status across all of them.
- You want a consistent format week to week so people can scan it quickly.

Skip it if your update is one line, like "shipped the thing, nothing blocking". Just send the one line.

## Required inputs

You do not need all of these, but the more you give, the better the report. Paste whatever you have.

- **Your raw activity.** Notes, a list of done items, meeting takeaways, anything you scribbled during the week.
- **Your goals or priorities.** What you said you would focus on this week or this quarter. This is what progress gets measured against.
- **Any numbers.** Metrics, sales, hours, tickets closed, signups, whatever you track. Include last week's number too if you have it, so the report can show the change.
- **Known risks or blockers.** Anything stuck, late, waiting on someone, or worrying you.
- **Audience and tone.** Who reads this, like a manager, a client, or your whole team, and how formal it should be.

If you are missing a piece, say so in the prompt. The AI should flag the gap, not paper over it.

## Safety checks

- **Do not invent.** The biggest risk here is the AI smoothing over thin evidence with confident-sounding filler. Tell it plainly: if something is not in the inputs, leave it out or mark it as unknown.
- **Numbers must come from you.** The AI should only report figures you actually provided. It should never estimate, round generously, or guess a metric. If a number is missing, the report should say "not tracked this week", not make one up.
- **Check before sharing wide.** A report that goes to a client or leadership carries weight. Read it fully before sending. The AI drafts. You are accountable for what goes out.
- **Mind what is sensitive.** If your notes contain confidential names, salary figures, or unannounced plans, decide whether they belong in a report that may be forwarded.

## Process

1. Read all the inputs and sort each item into one of four buckets: highlights, progress against goals, risks or blockers, next week.
2. For highlights, pick the three to five things that genuinely mattered. Lead with outcomes, not activity. "Closed the Acme deal" beats "had four calls with Acme".
3. For progress, line each goal up against what actually happened this week. Mark each as on track, at risk, or done. If a goal had no activity, say so honestly rather than hiding it.
4. For metrics, show the number and the change from last week where that is available. Do not invent comparisons.
5. For risks or blockers, name the issue, why it matters, and what is needed to clear it. If a blocker needs someone else to act, say who.
6. For next week, list three to five concrete priorities. Keep them specific enough to be checkable next Friday.
7. Flag anything thin: where evidence was missing, where a goal had no update, where a number was not provided. Surface these as a short "gaps" note rather than hiding them.
8. Write it in the requested tone, keep it scannable, and stay brief. A weekly report should be read in under two minutes.

## Copy-paste prompt

```
You are helping me write my weekly status report. Use only the
information I provide below. Do not invent facts, numbers, or progress.
If something is missing or unclear, leave it out or mark it as unknown,
and list it under "Gaps" at the end. Never estimate or guess a metric.

AUDIENCE: [who reads this, e.g. my manager / a client / my whole team]
TONE: [e.g. friendly and plain / formal / brief and factual]
REPORTING PERIOD: [e.g. week of 9 June]

MY GOALS OR PRIORITIES THIS PERIOD:
[paste your goals, one per line]

WHAT I ACTUALLY DID (raw notes, done items, meeting takeaways):
[paste everything, messy is fine]

NUMBERS / METRICS (include last period's figure if you have it):
[e.g. Signups: 142 this week, 118 last week. Tickets closed: 31.]

KNOWN RISKS OR BLOCKERS:
[anything stuck, late, or waiting on someone; write "none" if none]

Now write the report with these sections:
1. Highlights: the 3 to 5 things that mattered most, outcomes first.
2. Progress against goals: each goal marked on track / at risk / done,
   with a one-line update. If a goal had no activity, say so.
3. Metrics: each number with the change from last period where I gave one.
4. Risks and blockers: the issue, why it matters, and what is needed
   to clear it (and who, if it needs someone else).
5. Next week: 3 to 5 specific, checkable priorities.
6. Gaps: anything you could not report because the input was missing
   or unclear.

Keep it scannable and short enough to read in under two minutes.
After the report, ask me up to 3 questions if anything important
was unclear.
```

## Expected output

A short, structured report with the six sections above. Highlights and next-week items read as concrete outcomes, not vague activity. Goals each carry a clear status. Metrics show movement where you supplied a comparison. The "Gaps" note tells you honestly where the report is thin, and the follow-up questions give you a chance to fill those holes before you send it.

It should feel like a tidy draft you can lightly edit and forward, not a wall of text you have to rewrite.

## Review checklist

- Every fact and number traces back to something you actually provided. Nothing was invented.
- Highlights lead with outcomes, and they are genuinely the important ones, not just the easy wins.
- Each goal has an honest status, including any that stalled.
- Metric changes match the figures you pasted. No guessed comparisons.
- Blockers say clearly what is needed and from whom.
- Next-week priorities are specific enough to check off next Friday.
- The "Gaps" note is empty only if your inputs were genuinely complete.
- Nothing confidential is sitting in a report that might get forwarded.
- It reads in your voice and the right tone for the audience.
