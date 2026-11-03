---
name: meeting-prep
description: Turns a vague calendar invite into a one-page brief with context, an agenda, talking points, likely questions, questions worth asking and one clear outcome. Use before any meeting where the outcome matters, such as a client call, a senior stakeholder meeting or a negotiation.
---

# Meeting prep

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

Turn a vague calendar invite into a tight, one-page brief: the context, an agenda, your talking points, the questions you will likely get, the questions worth asking, and a single clear outcome.

## Purpose

Most meetings go sideways because nobody walked in with a plan. You spend the first ten minutes catching up and the last five realising you forgot the one thing you needed to raise. This skill fixes that. You give the AI what you know about the meeting, and it hands you back a short brief you can skim in the lift on the way in. The goal is not a 12-page dossier. It is a single page that makes you the most prepared person in the room.

## When to use

Use it before any meeting where the outcome matters and you would rather not wing it. Good fits:

- A sales or client call where you need to land a specific next step.
- A meeting with your boss or a senior stakeholder where you want to ask for something.
- A first meeting with someone new, where you do not yet know how the conversation will go.
- A negotiation, a performance chat, a budget discussion, or any meeting with a real decision on the table.
- A recurring meeting that has gone stale and needs you to steer it.

Skip it for casual catch-ups or meetings where you are just a listener. The prep is not worth it if there is nothing you need to get out of the room.

## Required inputs

You do not need all of these, but the more you give, the better the brief. At a minimum, give the first three.

- **The meeting.** Who is it with, what is it nominally about, and how long is it.
- **What you want.** The one thing you would call a win if it happened. Even a rough version is fine.
- **Who is in the room.** Names, roles, and anything you know about what they care about or worry about.
- **Background.** Recent emails, the last meeting's notes, a proposal, a contract, a project status, whatever is relevant. Paste it in.
- **The tricky bits.** Anything awkward: a late delivery, a budget cut, a disagreement, a favour you are about to ask for.
- **Your constraints.** A hard limit you cannot cross, a number you cannot go below, a thing you are not allowed to promise yet.

If you only have a calendar invite and a vague sense of dread, that is enough to start. The AI will tell you what it is guessing at.

## Safety checks

- **The AI is filling gaps with assumptions.** If you do not tell it what someone cares about, it will make a sensible guess. Sensible is not the same as true. Treat every claim about another person as a hypothesis, not a fact.
- **Do not paste anything you would not want leaked.** Salaries, legal matters, customer personal data, anything under an NDA. If the meeting is sensitive, strip the names and specifics before pasting, or keep that part out of the tool entirely. Check your own organisation's rules on what can go into AI tools.
- **The brief is a draft of your thinking, not a script.** If you read it out word for word you will sound like you are reading it out word for word. Use it to walk in clear, then talk like a human.
- **It cannot read the room for you.** Plans survive until the meeting starts. Be ready to bin the agenda if the conversation goes somewhere more useful.

## Process

1. Read the inputs and work out what kind of meeting this really is: a pitch, a decision, a relationship build, a problem to solve, a negotiation. Name it, because it changes everything else.
2. Restate the desired outcome in one plain sentence. If the user's version is fuzzy, sharpen it into something you could actually measure walking out the door.
3. Pull the relevant context into a few short bullets. Only what matters for this meeting. Flag anything you are assuming rather than reading from the inputs.
4. For each person in the room, note in a line what they likely want and what might make them push back.
5. Draft a tight agenda: three to five items, in a sensible order, with a rough sense of where the time goes. Put the thing that matters most early, not last.
6. Write the user's key talking points: the handful of things they must get across, phrased as plain spoken lines, not jargon.
7. List the questions the user is likely to be asked, especially the hard ones, with a short suggested angle for each.
8. List good questions for the user to ask: ones that move the meeting toward the outcome or surface what the other side actually thinks.
9. Add a short "if it goes off the rails" note: the one or two ways this meeting could stall, and how to recover.
10. Keep the whole thing to roughly one page. Cut anything that is not earning its place.

## Copy-paste prompt

```
You are helping me prepare for a meeting. Produce a tight, one-page brief I can
skim just before I walk in. Be specific and practical, not generic.

THE MEETING
- With: [WHO, e.g. our client Acme, two people]
- Topic: [WHAT IT IS NOMINALLY ABOUT]
- Length: [e.g. 30 minutes]
- When/where: [OPTIONAL]

WHAT I WANT OUT OF IT
- [THE ONE THING THAT WOULD MAKE THIS A WIN. Rough is fine.]

WHO IS IN THE ROOM
- [NAME, ROLE, AND ANYTHING I KNOW ABOUT WHAT THEY CARE ABOUT OR WORRY ABOUT.
   Repeat per person. Write "don't know much" if that's the truth.]

BACKGROUND (paste anything relevant)
- [RECENT EMAILS, LAST MEETING NOTES, PROPOSAL, STATUS, CONTRACT, ETC.
   Or write "none" if you have nothing.]

THE TRICKY BITS
- [ANYTHING AWKWARD: a late delivery, a budget cut, a favour I'm asking, a
   disagreement. Or "none".]

MY CONSTRAINTS
- [HARD LIMITS: a number I can't go below, a thing I can't promise yet, etc.
   Or "none".]

Now give me, in this order and no longer than about one page:
1. Meeting type, in a few words (pitch / decision / relationship / problem-solving
   / negotiation).
2. Desired outcome, rewritten as one clear sentence.
3. Context: 3 to 5 short bullets. Mark anything you're assuming with "(assumption)".
4. Each person: one line on what they likely want and what might make them push back.
5. Agenda: 3 to 5 items in a sensible order, with rough timing.
6. My key talking points: the few things I must get across, written as plain
   spoken lines.
7. Questions I'm likely to be asked, including the hard ones, each with a short
   suggested angle.
8. Good questions for me to ask.
9. If it goes off the rails: the one or two ways this could stall, and how I recover.

Use Australian English. No jargon. If you're guessing at something, say so.
```

## Expected output

A single page, structured roughly as: the meeting type and a one-line outcome at the top, then context, the people, an agenda, your talking points, likely questions, your questions to ask, and a short recovery note at the bottom. Talking points should read like things a person would actually say out loud. Assumptions should be flagged so you know which bits to sanity check. If the meeting is simple, the brief should be short. It should not pad to fill a page.

## Review checklist

Before you trust it, check:

- **Is the outcome actually what you want?** If the one-line outcome feels off, fix it first. Everything else hangs off it.
- **Are the assumptions about people fair?** Read the lines about what each person wants. If any feel like a stretch, soften them in your head or go and check.
- **Did it miss the tricky bit?** If you flagged something awkward, make sure the brief actually handles it and did not quietly skip it.
- **Can you say the talking points out loud?** Read them. If they sound like a press release, rewrite them in your own words.
- **Is anything in here you would not want said in the room?** Cut it.
- **Is it short enough to actually use?** If it is two pages, trim it. A brief you do not read is not a brief.
