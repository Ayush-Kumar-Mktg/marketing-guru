---
name: marketing-context
description: Create or update a single marketing context file (product, audience, customer language, proof, voice, competitors) that every other marketing-guru skill reads first, so you never re-explain your business. Use at the start of any new project, or when the user says "set up my marketing context", "remember my product", "here's my company", "update my ICP", "our positioning changed". Run this before other skills when no context file exists.
metadata:
  version: 1.0.0
---

# Marketing context

Every marketing task needs the same background: what you sell, to whom, why they buy and how you sound. This skill captures it once in a file, so every other skill starts informed and asks fewer questions.

## Where the file lives

Save to `.agents/marketing-context.md` in the project. If the project uses a `.claude/` folder instead, save to `.claude/marketing-context.md`. Other skills look in both places, then for `marketing-context.md` at the root.

If a file already exists, read it, show the user what's there and ask what changed. Update only those parts and add a dated line to the change log at the bottom.

## How to fill it

1. **Pull before you ask.** If the user gives a website, deck, docs or past copy, read them first and draft as much as you can. Mark anything you inferred with `(check)`.
2. **Ask the gaps in one batch.** Don't run a 30-question interview. Ask the 5 to 8 things you truly couldn't find.
3. **Use customer words.** Where possible, fill the language sections with real quotes from reviews, sales calls, support tickets or community posts. Customer words beat marketing words every time.
4. **Never invent proof.** If there are no numbers, leave the field empty and say so.
5. **Show the draft** and ask the user to correct it before saving.

## Template

```markdown
# Marketing context
Last updated: YYYY-MM-DD

## The product
- One sentence, plain (how an encyclopedia would describe it):
- Category people put it in:
- Price and model:
- Stage (pre-launch, early, growing, scaling):

## Who buys
- Primary buyer (role, company type, size):
- Who else is involved in the decision:
- Who it is NOT for:
- What they use today instead (the bad alternative):

## Why they buy
- The problem in their words (2 to 5 real quotes):
- The outcome they brag about afterwards:
- What they'd miss most if we vanished tomorrow:
- What almost stopped them from buying (top objections):

## Proof
- Numbers we can stand behind:
- Named customers or logos we can use:
- Reviews, ratings, awards:
- Proof we do NOT have yet:

## Positioning
- For [person] who [problem], we are the [category] that [outcome], because [proof only we have]:
- What we do differently (that competitors can't honestly copy):
- Main competitors and alternatives (for internal use, never attacked by name in copy):

## Voice
- We always sound like:
- We never sound like:
- Words we use:
- Words we avoid:
- Example of copy we love (paste):

## Channels
- Where the audience spends time:
- Channels working today:
- Channels tried and dropped (and why):

## Change log
- YYYY-MM-DD: created
```

## Output

Save the file, then reply with a three-line summary: who you sell to, the one-line story, and the biggest gap in the file (usually proof or customer language) with a suggestion for filling it.

## Related skills

Every other skill in this pack reads this file first. Start with **marketing-guru** if you're not sure which skill to use next.
