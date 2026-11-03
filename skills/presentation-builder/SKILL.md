---
name: presentation-builder
description: Turns a topic and rough notes into a slide outline with a story arc, a title and bullets for each slide, and speaker talking points. Use when you have something to present and a blank page, such as a team update, a pitch or a talk.
---

# Presentation builder

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

Turn a topic and some rough notes into a clear slide outline: a narrative that flows, one idea per slide, suggested titles and bullets, and speaker talking points you can actually say out loud.

## Purpose

This skill takes the messy pile in your head (a topic, a few notes, a deadline) and turns it into a structured slide outline. Not a finished deck, an outline. You get the story arc, a title and a few bullets per slide, and a short set of talking points for each one so you know what to say when the slide is up.

The hard part of a presentation is rarely the design. It is deciding what to say, in what order, and what to leave out. That is what this does. You take the outline into PowerPoint, a slide app, Keynote or Canva and build the visuals from there.

## When to use

Reach for this when you have something to present and a blank page is staring back at you. For example:

- A team update, project kickoff or status review.
- A sales or pitch deck for a prospect or investor.
- A training session or internal explainer.
- A conference talk or webinar.
- A board or leadership summary.

Do not use it when you already have a tight structure and just need wording help, or when the "presentation" is really a one page document in disguise. If nobody is standing up to talk through it, you may want a doc, not slides.

## Required inputs

You will get a far better result if you give it these. The more you bring, the less it has to guess.

- **Topic**: one sentence on what the presentation is about.
- **Audience**: who is in the room, and how much they already know. "Our exec team, finance background, no technical detail" is very different from "new starters on day one".
- **Goal**: what you want the audience to think, feel or do by the end. Approve the budget? Understand the new process? Sign up?
- **Time or slide count**: how long you have to present, or roughly how many slides you want. A rough number is fine.
- **Your notes**: any raw material. Bullet points, numbers, quotes, a paste of an email, half-formed thoughts. Dump it in.

Optional but useful: the tone you want (formal, friendly, energetic), any key message that must appear, and anything that must not be said.

## Safety checks

- **Facts and figures are yours to verify.** If you do not give the AI a number, it may invent a plausible one to fill the slide. Treat every statistic, date, name and quote in the output as a placeholder until you have confirmed it against a real source.
- **Do not paste confidential or personal data** into a tool you would not be comfortable sharing it with. Strip out client names, private figures or anything sensitive, or use a tool your organisation has approved for it.
- **The narrative is a suggestion, not the truth.** The AI will happily build a confident story around weak evidence. You are the one who knows whether the argument actually holds.
- **Keep your own voice.** If a talking point sounds nothing like how you speak, change it. Reading out a stranger's words on stage is worse than reading out your own rough ones.

## Process

The AI should follow these steps when building the outline:

1. Read all the inputs and restate, in one or two sentences, what the presentation is about, who it is for, and what it is meant to achieve. This is a quick alignment check before any slides exist.
2. Decide the narrative arc. Pick a structure that fits the goal, for example problem then solution then ask, or situation then complication then resolution, or a simple chronological walk-through. Name the structure chosen.
3. Set the slide count to fit the stated time. A rough guide is one slide per minute or two for spoken delivery, but follow the user's number if they gave one.
4. Map one idea to each slide. If a slide is carrying two ideas, split it. If two slides say the same thing, merge them.
5. For each slide, write a short, specific title (not a vague label), two to four bullet points of content, and two or three speaker talking points written as natural spoken language.
6. Mark clearly where a number, quote or fact is assumed rather than supplied, so the user knows what to check.
7. End with a single closing slide that restates the goal or call to action, then list any open questions or gaps the user should fill before building the deck.

## Copy-paste prompt

```
You are helping me build a slide outline for a presentation. I want a clear narrative, one idea per slide, suggested titles and bullets, and speaker talking points. Do not build a finished deck, just the outline.

Here are my inputs:

- Topic: [ONE SENTENCE ON WHAT THIS IS ABOUT]
- Audience: [WHO IS IN THE ROOM AND WHAT THEY ALREADY KNOW]
- Goal: [WHAT I WANT THEM TO THINK, FEEL OR DO BY THE END]
- Time or slide count: [E.G. "15 MINUTES" OR "ABOUT 10 SLIDES"]
- Tone: [E.G. FORMAL, FRIENDLY, ENERGETIC; LEAVE BLANK IF UNSURE]
- Must include: [ANY KEY MESSAGE THAT HAS TO APPEAR; OR "NOTHING SPECIFIC"]
- Must avoid: [ANYTHING THAT MUST NOT BE SAID; OR "NOTHING SPECIFIC"]

My raw notes:
[PASTE EVERYTHING YOU HAVE: BULLETS, NUMBERS, QUOTES, ROUGH THOUGHTS]

Please do the following:
1. First, restate in one or two sentences what this presentation is about, who it is for, and what it should achieve, so I can confirm you have it right.
2. Choose a narrative structure that fits the goal and name it.
3. Produce the outline, one slide per idea. For each slide give me:
   - Slide number and a specific, plain-language title
   - 2 to 4 bullet points for the slide content
   - 2 to 3 speaker talking points, written the way a person would actually say them out loud
4. Anywhere you have assumed a number, quote, date or fact that I did not give you, mark it clearly as [VERIFY] so I know to check it.
5. Finish with a closing slide that restates my goal or call to action.
6. After the outline, list any gaps or open questions I should fill before I build the deck.

Use plain language. Keep bullets short. Do not invent statistics and present them as fact; if you need a number to make a point, mark it [VERIFY].
```

## Expected output

You should get back, in this order:

- A one or two sentence restatement of the brief, so you can catch any misread before reading on.
- The chosen narrative structure, named in plain terms.
- A slide-by-slide outline. Each slide has a number, a specific title, a few content bullets, and a handful of natural talking points. Assumed facts are flagged with [VERIFY].
- A closing slide tied to your goal.
- A short list of gaps or open questions to resolve before you build.

It will read like a script you could hand to a colleague, not a finished, designed deck. That is the point. Building the visuals is the easy, fun part once the thinking is done.

## Review checklist

Before you trust the outline and start building, check:

- **Does the story actually flow?** Read the titles in order, top to bottom. They should tell the whole story on their own. If the thread breaks, reorder or rewrite.
- **One idea per slide?** If any slide is doing two jobs, split it. Crowded slides lose the room.
- **Did I verify every [VERIFY] tag?** And scan for any number, name, quote or date that slipped through without a tag. Confirm each against a real source.
- **Does it match the audience and the time?** Too much jargon for the room, or too many slides for the clock, means cutting now, not on the day.
- **Do the talking points sound like me?** Rewrite anything that would feel awkward to say out loud.
- **Is the ask clear?** By the closing slide, the audience should know exactly what you want them to do, think or feel. If it is fuzzy, sharpen it.
