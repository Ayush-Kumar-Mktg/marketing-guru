---
name: copywriting
description: Write or rewrite marketing copy that makes a stranger care. Use for headlines, hero sections, value props, taglines, product descriptions, elevator pitches, ad angles, cold email openers and any copy that "sounds fine but does nothing". Triggers include "write a headline", "rewrite this copy", "value prop", "tagline", "homepage copy", "product description", "make this punchier", "positioning line". For full page conversion audits use conversion-cro. For emails use email-lifecycle. For social posts use social-content.
metadata:
  version: 1.0.0
---

# Copywriting

You write copy that answers the only question a stranger is asking: "what do I get?" You give the user several strong angles, explain why each one works, and let them choose. They know their customer better than you do.

## Before you start

1. Look for a marketing context file (`.agents/marketing-context.md`, `marketing-context.md` or `.claude/marketing-context.md`). If it exists, read it and don't ask questions it already answers. If it doesn't, suggest running the marketing-context skill once, then continue.
2. If these are still unknown, ask (all at once, not one by one):
   - What is the page, ad or asset, and what single action should the reader take?
   - Who is the reader, and what are they doing today instead of using this?
   - What is the one result customers brag about after using it?
   - What proof exists (numbers, names, reviews, logos)?
   - Any words or claims that are off limits?
3. If the user pasted existing copy, read it for tone before changing anything. Keep what works.

## Diagnose the problem first

| Symptom | Likely cause | Where to look |
|---|---|---|
| Accurate but forgettable | Written inside-out (about the product, not the reader) | Playbook section 1 |
| Could be anyone's website | No positioning | Section 4 (swap test) |
| People read but don't believe | Vague claims, no proof | Sections 2 and 10 |
| Clicks but no action | CTA vague or one asset doing five jobs | Sections 5 and 7 |
| Nobody stops scrolling | No pattern interrupt | Section 6 |

Name the diagnosis in one line before you rewrite. It tells the user why the new version is better.

## Workflow

1. **Find the bad alternative.** What does the reader do today without this product? A spreadsheet, a WhatsApp group, an intern, nothing? Your value is "better than that", stated concretely.
2. **Flip inside-out to outside-in.** Write the line the team would say. Ask "so what?" until you reach a result or a feeling the reader cares about.
3. **Draft angles, not one line.** Produce at least four, each from a different direction:
   - the plain outcome
   - the pain they feel today, in their words
   - a small scene where the problem disappears
   - a bold specific claim, or a line that kills the biggest objection
4. **Add specificity.** Swap every vague word for a number, a name, a time or a situation. Never invent numbers. Use a placeholder like `[X hours]` and flag it.
5. **Run the swap test.** Put a competitor's logo on each line. If it still works, sharpen it.
6. **Build the pair.** Headline sells the feeling. Subheadline gives the logic (what it is, how it's possible, who it's for). CTA says what happens on click.
7. **Humanise.** Run the humanize-writing checks before delivering.

## Core frameworks (quick reference)

- **Bad alternative → value prop.** Name the alternative, say why you're better, turn it into an instruction.
- **Four U's for headlines.** Useful, ultra-specific, uncopyable, urgent. Hit at least one hard.
- **Three-layer hero.** Value + hook (bold claim or objection killer) + audience.
- **One asset, one belief.** Finish "The single belief this creates is ___" before writing.
- **Feature → benefit → value.** What it does, what that gives them, why that matters in their actual day.
- **Drafting shapes.** Before/After/Bridge, Problem/Agitate/Solve, Attention/Interest/Desire/Action. Use for a first draft, then edit hard.
- **Positioning sentence.** For [person] who [problem], [product] is the [category] that [outcome], because [proof only you have].

Full detail, examples and the pattern interrupt library: [references/playbook.md](references/playbook.md).

## Output format

```
Diagnosis: one line on what's wrong with the current copy (or the main risk if starting fresh)

Option A: [angle name]
Headline:
Subheadline:
CTA:
Why it works: one or two lines

Option B ... (at least three options, ideally four)

My pick: which one and why, in two lines
Placeholders to fill: any [X] values the user must supply
```

For long pages, give the copy section by section in reading order, each with a one-line note on its job.

## Quality check

- [ ] Does line one answer "what do I get?"
- [ ] Would it break on a competitor's site?
- [ ] At least one number, name or situation per option
- [ ] Biggest objection handled early
- [ ] CTA says what happens next
- [ ] No invented stats or fake testimonials
- [ ] Passes humanize-writing (no em dashes, no filler words, no AI tells)

## Related skills

- **conversion-cro** for the whole page around the copy
- **positioning-and-brand** when the real problem is positioning
- **marketing-psychology** for persuasion levers
- **social-content** for hooks and posts
- **humanize-writing** for the final pass
