---
name: research-brief
description: Turns a question into a sourced brief with a short answer, key findings tied to sources, what's uncertain and next steps, flagging anything unverified. Use when you need to understand something before you decide, such as sizing up a vendor, checking a claim or getting up to speed.
---

# Research brief

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

Hand the AI a question, get back a tidy, sourced brief: the short answer, what the evidence says, what is still uncertain, and what to do next.

## Purpose

This skill turns "go find out about X" into a structured answer you can actually trust. Instead of a wall of confident-sounding text, you get a brief with a clear shape: the question, a short answer up top, the key findings each tied to a source, an honest list of what is uncertain, and a few recommended next steps.

The whole point is sourcing. An AI can sound just as sure when it is right as when it is making things up, so the rule here is simple. Every factual claim either carries a source or gets flagged as unverified. No exceptions. You end up with something you can skim in a minute, defend in a meeting, or pass to someone else without having to redo the work.

## When to use

Use this when you need to understand something before you decide or act, and you want the reasoning shown, not just an answer.

Good fits:
- Sizing up a market, a competitor, a vendor or a tool before a decision.
- Getting up to speed on a topic that is new to you.
- Checking whether a claim you heard is actually true.
- Prepping for a meeting, a proposal or a piece of writing where you will be asked "how do you know that".

Not a great fit:
- Anything where being wrong is expensive or risky on its own: legal, medical, tax, financial or safety questions. Use this to get oriented, then check with a qualified human.
- Very recent or fast-moving events, if your AI tool cannot browse the live web. Without web access it is working from memory with a cutoff date, so treat its "facts" as starting points, not final answers.
- Questions about your own private documents or data, unless you paste that material in. The AI cannot see your files, inbox or systems by default.

## Required inputs

You only really need the first one. The rest make the brief sharper.

- The question. State it plainly and specifically. "Should we use X or Y for team scheduling" beats "tell me about scheduling tools".
- Why you are asking and the decision behind it. This helps the AI prioritise what matters to you.
- Any constraints. Your region, budget, industry, team size, timeframe, must-haves and deal-breakers.
- Recency needs. If only the last year or two counts, say so.
- Length and depth. A quick scan or a thorough dig.

If you leave gaps, the AI should ask you a couple of clarifying questions before charging off. A good brief starts with a good question.

## Safety checks

- Sources are not optional. If the AI cannot point to where a fact came from, it must label it clearly as unverified rather than slip it in as established truth.
- Watch for invented sources. AI tools sometimes produce realistic-looking citations, titles, authors or links that do not exist. If you are going to rely on a source, open it and confirm it says what the brief claims. Do not trust a link just because it looks tidy.
- Mind the cutoff. If your tool cannot browse the web, anything "recent" is a guess from training data. Numbers, prices, versions and "latest" anything are the usual suspects. Verify them.
- Separate fact from opinion. Recommendations and interpretations are the AI's reasoning, not evidence. They belong in their own section, not mixed into the findings.
- One source is a lead, not a conclusion. For anything that matters, look for a second source that agrees before you treat it as settled.

## Process

1. Restate the question in one sentence so we both agree on what is being answered. If anything important is missing, ask up to three clarifying questions before going further.
2. Plan the angles. Break the question into the few sub-questions that actually need answering, and note what kind of evidence would settle each one.
3. Gather what you can. Pull together the relevant facts, figures and viewpoints. If you have web access, search and read real sources. If you do not, work from training knowledge and say so plainly.
4. Tag every claim. For each factual statement, attach a source (name it, and link it if you can). If there is no source, mark the claim as unverified.
5. Weigh the evidence. Note where sources agree, where they conflict, and which look more reliable. Do not paper over disagreement; surface it.
6. Write the short answer first. Two to four sentences that answer the question directly, with the confidence level stated honestly.
7. List the key findings, each with its source. Keep them concrete and skimmable.
8. Be honest about gaps. Spell out what is uncertain, contested, out of date, or simply not found.
9. Recommend next steps. A few concrete actions, including what to verify and where to look next.
10. Do a final honesty pass. Confirm nothing factual is sitting there unsourced and unflagged. If it is, fix it or flag it.

## Copy-paste prompt

```
You are my research assistant. Produce a structured, sourced research brief.

MY QUESTION:
[State the question plainly and specifically]

WHY I'M ASKING / THE DECISION BEHIND IT:
[e.g. choosing a tool, prepping a proposal, checking a claim]

CONSTRAINTS:
- Region/market: [e.g. Australia]
- Budget / size / timeframe: [optional]
- Must-haves and deal-breakers: [optional]

RECENCY: [How recent does the information need to be? e.g. last 2 years]
DEPTH: [Quick scan / thorough]

RULES YOU MUST FOLLOW:
1. If anything important is unclear, ask me up to 3 clarifying questions
   BEFORE researching. Otherwise begin.
2. Every factual claim must carry a source (name it, and link it if you
   can). If you cannot source a claim, label it clearly as UNVERIFIED.
3. Do not invent sources, titles, authors or links. If you are unsure a
   source is real, say so.
4. If you cannot browse the live web, state that plainly and tell me which
   facts are from training data and may be out of date.
5. Keep your recommendations separate from the evidence.

RETURN THE BRIEF IN THIS EXACT STRUCTURE:

## Question
[One-sentence restatement of what you're answering]

## Short answer
[2 to 4 sentences answering directly. State your confidence: high / medium / low, and why.]

## Key findings
- [Finding]. Source: [name + link, or UNVERIFIED]
- [Finding]. Source: [name + link, or UNVERIFIED]
(continue as needed)

## What's uncertain or contested
- [Gaps, conflicting sources, out-of-date info, things you couldn't find]

## Recommended next steps
- [Concrete actions, including what I should verify myself and where to look]

## Sources used
[List each source once, with its link if available]
```

## Expected output

A short brief, usually under a page, that follows the structure above. The short answer sits at the top so you get the conclusion before the working. Each finding is tied to a named source, and anything the AI could not back up is plainly marked unverified rather than hidden. The uncertainty section is real, not a token line: if sources disagree or the data is thin, you will see that. The next steps tell you what to check and where to go.

If you asked a vague question, expect a couple of clarifying questions first instead of a brief. That is the tool working as intended.

## Review checklist

Before you trust or forward the brief, check:

- Does the short answer actually answer your question, and does the stated confidence match the strength of the evidence.
- Does every factual claim have a source or an unverified flag. Be suspicious of any confident statement with neither.
- Did you open the two or three sources that matter most and confirm they exist and say what the brief claims.
- Are recommendations kept separate from facts, so opinion is not dressed up as evidence.
- For anything cost, date, version or "latest" related, did you check it against a current, live source.
- Does the uncertainty section feel honest. A brief with zero uncertainty on a real question is a warning sign, not a win.
- For high-stakes decisions, have you planned to run this past a qualified human before acting.
