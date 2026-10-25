---
name: journal-finder
description: Suggests journals where a research paper can be submitted. Use whenever the user shares a paper title, abstract, draft or topic and asks where to publish, which journal fits, where to submit, or wants a list of target journals, even if they don't say "journal finder". Also use for "alternative journals after rejection".
---

# Journal Finder

Give the user a short, honest list of journals their paper could be submitted to.

## Step 1: Understand the paper
From the title, abstract or draft, note:
- Field and subfield (e.g. deep learning for single-cell biology)
- Paper type: original research, review/survey, short letter, dataset/benchmark
- Contribution: new method, application, benchmark, theory

If the user gave only a vague topic, ask ONE question: "Can you paste the title and abstract?"
Ask about constraints only if missing: open access needed? APC budget? speed? Rejected from a journal already?

## Step 2: Search for real, current journals
Use web search. Do not rely on memory for scope, indexing, fees or speed.
- Search for journals that recently published similar papers (search the paper's key terms).
- For each candidate, open the journal's own "Aims & Scope" or "Author guidelines" page.
- Check: scope match, article types accepted, open access/APC, indexing (SCI/SCIE/Scopus), peer-review speed if stated.

Never invent impact factors, quartiles, APCs or acceptance rates. If you cannot verify a number, write "check on journal site".

## Step 3: Output a ranked list
Give 8 to 10 journals in three tiers:
- **Ambitious** (2-3): higher prestige, lower chance
- **Good fit** (3-4): best match for scope and quality
- **Safer** (2-3): broader scope or faster, higher chance

Use this table:

| Journal | Publisher | Why it fits | Article type | Open access / APC | Link |
|---|---|---|---|---|---|

Always include a working link to each journal's author-guidelines or home page. A table without links is incomplete.

If the user's constraints (for example no APC) leave fewer than 8 journals, still give 8 to 10: first the journals that meet every constraint, then a second group labelled "Close alternatives" that break one constraint, saying which one. Keep the three tiers within each group.
Then add 2-3 lines: your top pick and why, plus any red flag (scope mismatch, paper too short, missing benchmark).

## Rules
- Only suggest journals that exist and match the paper. Skip predatory or unknown publishers; if unsure, say so.
- If the user is a student, mention that supervisor approval and institutional requirements (e.g. required indexing for graduation) may limit the choice.
- Remind once: confirm current rules on the journal's own site before submitting. Do not claim to guarantee acceptance.
- Keep the answer short. No long essays.

## After rejection
If the user says they were rejected: ask for the reviewer comments, list the journals one tier lower or with a closer scope, and note which reviewer points to fix first.
