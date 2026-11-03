---
name: inbox-triage
description: Sorts a pasted batch of email into groups, ranks what needs you, drafts replies for routine messages and sets aside anything sensitive for you to handle. Use after leave or a long meeting block, or for a daily morning sort. It never sends anything.
---

# Inbox triage

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

A reusable skill that sorts a full inbox into groups, ranks what matters, drafts replies for the routine stuff, and flags anything sensitive for you to handle yourself.

## Purpose

A full inbox is mostly noise with a few important things buried in it. This skill does the sorting for you. You paste in your messages, and the AI groups them, tells you what actually needs you, drafts replies for the easy ones, and sets aside anything risky so you decide on it personally.

The goal is to get you from "100 unread, no idea where to start" to "here are the 6 that need me, here are 20 drafted replies I just need to skim, and here are 3 I should look at carefully" in one pass.

It does not send anything. It sorts and drafts. You stay in control of every send.

## When to use

Use it when:

- You have come back from leave, a long meeting block, or a weekend, and the inbox is overflowing.
- You want a daily morning sort so you start with a plan instead of scrolling.
- You triage messages on behalf of someone else (an executive, a shared team inbox, a support queue) and need a fast first pass.

Do not use it as your only filter for anything where a miss is expensive. It is a strong first pass, not a replacement for your own eyes. Always read the drafts before they go out.

## Required inputs

You will need to provide:

1. **The messages.** Copy and paste the sender, subject, date, and the body (or a fair chunk of it) for each message. The more text you give it, the better the sort. Sender and subject alone is a weak signal.
2. **Who you are and your role.** For example, "I run operations for a 30 person agency" or "I'm an EA triaging my CEO's inbox". This tells the AI what "important to me" actually means.
3. **What counts as urgent for you.** Client escalations? Anything from your manager? Money in or out? Be specific.
4. **Your reply style.** Short and direct, or warmer and longer. Paste one or two of your real past replies if you have them, so the drafts sound like you.
5. **Anything to always escalate, never auto-handle.** For example, legal, HR, anything involving a specific person, or anything mentioning money over a threshold.

If you skip the role and urgency inputs, the AI will guess, and the ranking will be generic. Two minutes spent here is worth it.

## Safety checks

- **Nothing gets sent.** This skill only produces drafts and a sorted list. You do the sending, after you read.
- **Sensitive messages get flagged, not drafted.** Anything touching legal matters, HR, complaints, terminations, contracts, payments, passwords, or personal data is set aside for you to handle. The AI should not write a reply to these on autopilot.
- **Watch for impersonation and scams.** Ask the AI to flag messages that pressure you to act fast, change bank details, get gift cards, or click an unfamiliar link. These are common attacks. Treat any "urgent payment" or "change of bank account" message as suspect until you verify it through a separate channel, like a phone call to a known number.
- **Privacy.** You are pasting real messages into an AI tool. Do not paste anything you are not allowed to share with that tool, for example client data under a confidentiality agreement, or health and financial records, unless your workplace has cleared the tool for that. When in doubt, redact names and numbers first.
- **The AI can misread tone and stakes.** A short angry email can look routine. The escalation list and your own review are the backstop.

## Process

The AI follows these steps:

1. **Read every message** and note the sender, the apparent intent (a question, a request, an FYI, a complaint, a newsletter, a meeting), and any deadline or date mentioned.
2. **Group the messages** into clear buckets, for example: needs you personally, can be a quick reply, waiting on someone else, FYI only, and noise or unsubscribe candidates.
3. **Rank within each bucket** using your stated urgency rules. Put time-sensitive and high-stakes items first.
4. **Flag the sensitive and risky ones** into a separate set-aside list, with a one-line reason for each. Do not draft replies for these.
5. **Identify the routine ones** that are safe to draft, meaning low stakes, clear intent, no sensitive content.
6. **Draft a reply for each routine message** in your voice and style. Keep each draft short and ready to skim. Leave a clear placeholder where a fact is needed that the AI does not have, for example [confirm the delivery date].
7. **Produce a top of inbox summary:** the few things that genuinely need you today, in priority order, each with a one-line reason.
8. **List anything it was unsure about** rather than guessing, so you can make the call.

## Copy-paste prompt

```
You are my inbox triage assistant. Sort and prioritise the messages below.
Do not send anything. You only sort and draft. I do all the sending.

ABOUT ME
- My role: [YOUR ROLE, e.g. operations lead at a 30 person agency]
- What counts as urgent for me: [YOUR URGENCY RULES, e.g. client escalations,
  anything from my manager Sam, anything about money in or out]
- My reply style: [e.g. short, direct, friendly. Sample of my voice: PASTE A
  PAST REPLY OR TWO HERE]
- Always escalate to me, never draft a reply for: [e.g. legal, HR, complaints,
  contracts, payments over $1000, anything mentioning a specific named person]

THE MESSAGES
[PASTE EACH MESSAGE WITH SENDER, SUBJECT, DATE, AND BODY. SEPARATE EACH ONE
WITH A LINE OF DASHES.]

WHAT I WANT BACK, IN THIS ORDER
1. TOP OF INBOX: the few messages that genuinely need me today, ranked, each
   with a one-line reason.
2. SENSITIVE / RISKY (HANDLE YOURSELF): any message that is legal, HR, money,
   a complaint, a possible scam, or pressures me to act fast or change payment
   details. One line each saying why. Do NOT draft replies for these.
3. GROUPS: sort the rest into buckets (quick reply, waiting on someone, FYI
   only, noise / unsubscribe). Just list them, no drafts needed except below.
4. DRAFTED REPLIES: for the routine, low-stakes messages only, write a short
   reply in my voice. Use clear [placeholders] wherever you need a fact I have
   not given you. Label each draft with the message it answers.
5. UNSURE: anything you could not confidently classify. Ask me, do not guess.

Be honest. If a message is ambiguous, say so rather than forcing it into a box.
```

## Expected output

You should get back five clearly labelled sections:

- **Top of inbox:** a short ranked list of what needs you, each with a reason. This is the part you read first.
- **Sensitive or risky:** a set-aside list with no drafts, each line saying why it was flagged.
- **Groups:** the rest of the inbox sorted into buckets so the bulk of it is off your plate.
- **Drafted replies:** ready-to-skim replies for the routine messages, in your voice, with placeholders where a fact is missing.
- **Unsure:** anything the AI did not want to guess on.

A good output is honest about ambiguity and conservative about what it drafts. If it has flagged a few things as sensitive and left a couple in the unsure pile, that is the tool doing its job, not failing.

## Review checklist

Before you trust or send anything, check:

- [ ] **Did the top of inbox list miss anything?** Skim the groups for a minute or two to confirm nothing important got buried in "FYI only".
- [ ] **Read every draft before sending.** The AI does not know facts it was not told. Check dates, names, numbers, and commitments. Fill in every [placeholder].
- [ ] **Do the drafts sound like you?** Adjust tone if they feel off. They get more accurate the more samples of your voice you gave it.
- [ ] **Look at the sensitive pile yourself.** These are the ones that matter most. The AI parked them for you on purpose.
- [ ] **Sanity-check anything urgent or money-related.** If a message asks you to pay, change bank details, or act immediately, verify it through a separate channel before doing anything, even if the draft looks reasonable.
- [ ] **Did it over-draft?** If it wrote a confident reply to something stakes-heavy, do not send it. Move that one to your own pile.
