---
name: safety-governance-checker
description: Runs a pre-flight check on an AI workflow or automation, covering the data it touches, the permissions it needs, what could go wrong and where a human should stay in the loop, and ends with a go, hold or fix-first verdict. Use before connecting a tool to real accounts or letting anything run on its own.
---

# Safety and governance checker

Using a chat app? Copy only the block under "Copy-paste prompt". The rest is notes for you.

A pre-flight check you run on any AI workflow or automation before you connect it, trust it, or let it run on its own.

## Purpose

Before you hand a job to an AI tool, especially one that touches your accounts, your data, or other people, it pays to stop and think about what could go wrong. This skill does that thinking with you. You describe the workflow you are about to set up, and the AI walks through it like a careful colleague. It looks at what data it touches, what permissions it needs, what could go wrong, and where a human should stay in the loop. You end with a clear go, hold, or fix-first verdict and the reasons behind it.

The goal is not to scare you off automation. It is to catch the obvious problems early, when fixing them is cheap, instead of after they have already sent the wrong email to the wrong person.

## When to use

Run this check before you:

- Connect an AI tool to an account that holds real data (email, calendar, files, CRM, bank, payroll).
- Give an AI permission to act on its own, like sending messages, posting, paying, scheduling, or deleting.
- Set up an automation that runs on a schedule or trigger without you watching each time.
- Let an AI handle anything involving customers, staff, money, contracts, or personal information.
- Share a workflow with your team and want a plain record of the risks you considered.

You do not need it for low-stakes, read-only tasks where the AI just drafts something you read and send yourself. If nothing happens without your click, and no sensitive data leaves your control, the risk is small. Use your judgement.

## Required inputs

Have these ready before you start. The more honest you are here, the more useful the check.

- A plain description of what the workflow does, start to finish.
- The tools or services involved (for example, the AI assistant plus your email and a spreadsheet).
- The data it will read or write, and whether any of it is personal, financial, or confidential.
- The actions it can take on its own versus the actions that need your approval.
- Who is affected if it goes wrong (just you, your team, customers, the public).
- Any rules you have to follow (company policy, privacy law, client contracts).

If you do not know some of these yet, say so. "I am not sure what permissions it asks for" is a valid input, and the check will tell you to go find out before proceeding.

## Safety checks

A few ground rules so the check itself stays trustworthy.

- The AI assesses risk. It does not give you legal or compliance advice. For anything involving the law, a regulator, or a binding contract, treat its output as a prompt to ask a qualified person, not a final answer.
- Never paste real passwords, API keys, or secrets into the prompt. Describe the access in words instead ("it logs in to my email").
- The AI only knows what you tell it. If you leave out that the data includes customer records, it cannot flag that risk. Be complete.
- A "go" verdict is the AI's read, not a guarantee. You own the final decision and what happens after.
- When in doubt, the safe default is hold. It is always cheaper to check than to undo.

## Process

The AI follows these steps in order.

1. Restate the workflow in its own words, so you can confirm it understood before assessing anything.
2. List the data the workflow touches, and tag each item as public, internal, personal, financial, or confidential.
3. List the permissions and access it needs, and flag any that are broader than the task requires (for example, full account access when read-only would do).
4. Identify what could go wrong: wrong recipient, wrong data exposed, an action that cannot be undone, an action taken at the wrong time, or the AI acting on a bad instruction.
5. Rate each risk by how likely it is and how bad the impact would be, in plain words (low, medium, high), with a one-line reason for each.
6. Decide where a human checkpoint is needed, and name the specific moment (for example, "a person approves before anything sends to a customer").
7. Recommend the smallest changes that would lower the risk, such as narrowing permissions, adding an approval step, or starting in test mode.
8. Give a single verdict: go, go with changes, or hold, with the two or three reasons that drove it.

## Copy-paste prompt

```
You are a careful, practical safety and governance reviewer. I am about to set
up an AI workflow or automation and I want a clear-eyed risk check before I
trust it. You assess risk in plain language; you do not give legal advice.

Here is the workflow:

WHAT IT DOES: [describe the workflow start to finish, in plain words]
TOOLS / SERVICES INVOLVED: [e.g. AI assistant + your email + a spreadsheet]
DATA IT READS OR WRITES: [list it; note anything personal, financial, or confidential]
ACTIONS IT TAKES ON ITS OWN: [e.g. sends emails, posts, schedules, pays, deletes]
ACTIONS THAT NEED MY APPROVAL: [list, or write "none yet" if undecided]
WHO IS AFFECTED IF IT GOES WRONG: [just me / my team / customers / the public]
RULES I MUST FOLLOW: [company policy, privacy law, client contracts, or "none I know of"]
ANYTHING I AM UNSURE ABOUT: [e.g. "not sure what permissions it asks for"]

Do this, in order:
1. Restate the workflow in your own words so I can confirm you understood it.
2. List the data it touches and tag each item: public, internal, personal,
   financial, or confidential.
3. List the permissions and access it needs. Flag any that are broader than the
   task requires.
4. List what could realistically go wrong (wrong recipient, sensitive data
   exposed, an action that cannot be undone, wrong timing, the AI acting on a
   bad instruction).
5. Rate each risk as low, medium, or high for likelihood and for impact, with a
   one-line reason for each.
6. Tell me where a human checkpoint is needed, naming the exact moment.
7. Recommend the smallest changes that would lower the risk.
8. End with a single verdict: GO, GO WITH CHANGES, or HOLD, and the two or three
   reasons behind it.

If I have left out something you need to judge a risk, say so plainly and tell
me to find out before proceeding. When you are unsure, lean towards caution.
```

## Expected output

You should get back, in this rough shape:

- A one-paragraph restatement of your workflow. Read this first. If it is wrong, your inputs were unclear and the rest of the check is built on sand.
- A tagged list of the data involved, so you can see at a glance whether anything sensitive is in play.
- A permissions list with any over-broad access flagged.
- A short, ranked list of what could go wrong, each with a likelihood and impact rating and a plain reason.
- A clear statement of where, if anywhere, a human needs to stay in the loop.
- A few concrete, small changes that would make the workflow safer.
- A single verdict (go, go with changes, or hold) with its reasons.

A good output is specific to your situation, not a generic lecture about AI safety. If it reads like a brochure, push back and ask it to name the actual risks in your actual workflow.

## Review checklist

Before you trust the verdict and act on it, check:

- Did the restatement match what you actually plan to do?
- Did it catch the data that worries you most? If you have customer or financial data and it did not mention it, you may have under-described your inputs. Add them and run it again.
- Are the flagged risks real and specific, or vague filler? Discard the filler and act on the specifics.
- Does any "go" verdict still leave an action that cannot be undone running with no human checkpoint? If so, treat it as a hold regardless of what it said.
- Are the suggested changes things you can actually do, like narrowing a permission or adding an approval step?
- For anything touching the law, money, or a contract, have you decided who to ask before you proceed? The AI is not that person.
- Are you comfortable being the one who signs off? You own the decision, not the tool.
