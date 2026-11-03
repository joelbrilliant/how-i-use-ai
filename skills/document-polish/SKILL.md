---
name: document-polish
description: Tightens a draft you've already written so it reads cleanly in one consistent voice, without adding facts or changing your meaning, and flags claims you haven't backed up. Use when a real draft needs a second pass before someone important reads it.
---

# Document polish

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

Tighten and clarify a draft so it reads cleanly, keeps one consistent voice, and says exactly what you meant, without changing the meaning or inventing facts.

## Purpose

This skill takes a draft you have already written and makes it sharper and easier to read. It improves the structure, cuts the waffle, swaps jargon for plain words, and steadies the tone so the whole thing sounds like one person wrote it.

What it does not do matters just as much. It will not add new facts, new figures or new claims. It will not change your meaning or your decisions. If something in your draft reads like a claim you have not backed up, it flags that for you rather than quietly fixing it or making something up. You stay the author. The AI is the editor sitting next to you.

## When to use

Reach for this when you have a real draft in hand and you want it to land better. Good fits include:

- An email or update that feels clunky and you want it crisp before you hit send.
- A proposal, report or memo where the ideas are right but the writing is messy.
- A policy, process note or FAQ that needs to read clearly for people outside your team.
- Anything you wrote in a hurry that now needs a second pass before someone important reads it.

Do not use this for a blank page. If you have only notes or a rough idea, write the draft first, even a bad one, then polish it. Also skip it for legal, medical or financial wording where the exact phrasing carries weight. There, an editor changing a single word can change the meaning, so a human expert should make the call.

## Required inputs

You need to provide:

1. The full draft text. Paste the whole thing, not a fragment, so the AI can keep the voice consistent across it.
2. The audience. Who reads this? For example "our exec team", "new customers", "the whole company".
3. The goal. What do you want the reader to think, feel or do after reading it?
4. The voice you want. A few words is enough, for example "warm and plain", "formal", "direct and confident".

Optional but helpful:

- Any hard constraints, such as a length limit, words you must or must not use, or a house style.
- Things that must not change, such as a quote, a name, a number or a specific sentence you are happy with.

## Safety checks

- Meaning is locked. The polish must not change what you are actually saying. If a sentence is unclear, the AI should ask or flag it, not guess a new meaning.
- No new facts. The AI must not add figures, dates, names, claims or examples that were not in your draft. Tightening words is fine. Inventing content is not.
- Claims get flagged, not fixed. If a line reads like an unsupported claim, for example "we are the market leader" with nothing behind it, the AI should list it for your review, not soften it into something that sounds true. You decide what to do.
- You verify before you send. The output is a suggestion. Read it against your original before you trust it, especially any numbers, names or commitments.

## Process

1. Read the whole draft first to understand the point, the audience and the intended voice before changing anything.
2. Fix the structure. Put the main point near the top. Group related ideas. Add or tidy headings only if they help the reader.
3. Improve clarity. Shorten long sentences, cut filler, and remove repetition. Keep every original idea.
4. Run a plain language pass. Replace jargon and buzzwords with words the stated audience would actually use. Explain any necessary technical term in plain words the first time it appears.
5. Steady the voice. Keep the tone consistent from start to finish and match the voice the user asked for.
6. Protect the facts. Do not add, remove or alter any fact, figure, name, quote or decision. If meaning is unclear, leave it and flag it.
7. Build a flag list. Note anything that reads as an unsupported claim, anything ambiguous, and anything that might be a fact the user should double-check.
8. Return the polished draft plus the flag list and a short summary of the main changes. Do not return a rewritten document with new claims baked in.

## Copy-paste prompt

```
You are my editor. Polish the draft below. Improve structure, clarity,
plain language and a consistent voice. Do NOT change my meaning, and do
NOT add any new facts, figures, names, examples or claims.

CONTEXT
- Audience: [WHO WILL READ THIS]
- Goal: [WHAT I WANT THE READER TO THINK, FEEL OR DO]
- Voice I want: [E.G. WARM AND PLAIN / FORMAL / DIRECT AND CONFIDENT]
- Constraints: [LENGTH LIMIT, WORDS TO USE OR AVOID, HOUSE STYLE, OR "NONE"]
- Must not change: [QUOTES, NAMES, NUMBERS OR SENTENCES TO LEAVE AS-IS, OR "NONE"]

RULES
- Keep my meaning exactly. If a sentence is unclear, leave it and flag it
  instead of guessing.
- Do not invent or add facts. Tighten the words I already wrote.
- Explain any necessary jargon in plain language the first time it appears.
- If a line reads like a claim I have not backed up, list it in FLAGS for
  my review. Do not soften it or make it sound proven.

RETURN, in this order:
1. SUMMARY: 3 to 5 bullet points on the main changes you made and why.
2. POLISHED DRAFT: the full edited version.
3. FLAGS: a list of (a) anything that reads as an unsupported claim,
   (b) anything ambiguous you left alone, and (c) any facts or numbers
   I should double-check. If there are none, say "No flags".

DRAFT:
[PASTE YOUR FULL DRAFT HERE]
```

## Expected output

You should get back three clearly separated parts:

1. A short summary of the main changes, so you can see what moved and why without comparing line by line.
2. The polished draft, same meaning as yours, easier to read, in one consistent voice.
3. A flags list calling out unsupported claims, anything ambiguous, and any facts worth checking. If nothing needs flagging, it should say so plainly.

If the AI hands back something longer, more confident or more impressive than your original, treat that as a warning sign. Polish should make your words clearer, not bigger.

## Review checklist

Before you trust and send the result, check:

- [ ] The meaning matches your original. Nothing now says something you did not mean.
- [ ] No new facts, figures, names or claims have appeared that you did not write.
- [ ] Every number, date, name and quote is unchanged and correct.
- [ ] The voice sounds like you, or like the voice you asked for, all the way through.
- [ ] Anything in the flags list has been read and dealt with by you, not ignored.
- [ ] It actually reads better. If it just reads differently, go back and ask for another pass.
