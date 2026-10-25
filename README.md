# Journal Finder (Claude skill)

A tiny Claude skill. Paste your paper's title and abstract, and it gives you a ranked list of journals you can submit to, with links, open-access info and why each one fits.

## What you get
- 8-10 journals in three tiers: ambitious, good fit, safer
- A table: journal, publisher, fit, article type, open access/APC, link
- A top pick and any red flags
- Journals are looked up on the web each time, so the list stays current

## Install (Claude app)
1. Settings > Capabilities > turn on **Code execution and file creation**.
2. Customize > Skills > **+** > **Upload a skill** > choose a ZIP of the `journal-finder` folder.
3. Make sure the toggle is on.

## Use
Start a new chat and say:
> Where can I submit this paper? [paste title + abstract]

Other examples:
- "Suggest open-access journals for this abstract, APC under $2000."
- "My paper was rejected from X. Where next?"

## Install (Claude Code)
```
git clone https://github.com/sohrab-web/journal-finder-skill.git
mkdir -p ~/.claude/skills
cp -r journal-finder-skill/skills/journal-finder ~/.claude/skills/
```

## Notes
- Always confirm scope and fees on the journal's own website.
- This is a suggestion list, not an acceptance predictor.

## License
MIT
