---
name: humanize-writing
description: Edit marketing writing so it reads like a specific person wrote it, not a language model. Removes machine-writing tells (inflated importance, buzzwords, "it's not X, it's Y", forced threes, long dashes, chatbot openers and closers, vague authorities, filler, even rhythm) and adds voice, specificity and rhythm. Use as the final pass on any copy, post, email, page or document, or when asked to "make this sound human", "this sounds like ChatGPT", "remove the AI tells", "edit this", "tighten this", "match my voice". Every other skill in this pack ends with this pass.
metadata:
  version: 1.0.0
---

# Humanize writing

You edit text until a reader would believe a thoughtful person wrote it. That means removing the patterns that make writing feel generated and putting back the things that make it feel alive: a view, specifics, varied rhythm and a real voice. Meaning stays intact.

## On by default, easy to skip

Every skill in this pack runs this pass automatically before delivering text. If the user says "skip humanize", "raw draft", "don't edit the wording" or similar, the calling skill delivers its draft as is. The user can also call this skill on its own to clean up any text, written by a person or a model.

## Before you start

1. If the user gave a sample of their own writing (or the marketing context file has a voice section), read it first. Note sentence length, word choice, punctuation habits, how they open paragraphs and any phrases they repeat. Match that voice. Don't "upgrade" their plain words into fancier ones.
2. Note the format and register: a LinkedIn post, a landing page, a cold email and a report each allow different levels of informality.
3. If the user has their own banned-word list or style rules, those take priority over this skill's defaults.

## Workflow

1. **Scan** for patterns in six groups: content (inflated importance, vague authorities, fake-depth "-ing" endings), language (buzzwords, "serves as", "not X but Y", forced threes, synonym cycling), style (dashes, semicolons, decorative bold, title case, emojis), conversation residue (chatbot openers and closers, cutoff hedges, unprompted both-sides framing), filler (wordy phrases, stacked hedges, signposting, summaries) and rhythm (every sentence the same length).
2. **Rewrite** each problem. Cut first. Most tells add nothing, and deleting them fixes the sentence.
3. **Add a pulse.** Anchor abstract claims in a number, name, time or scene. Vary sentence length. Take a position. Use "you" and "I" where the format allows.
4. **Self-check.** Ask "what still makes this sound generated?" List the remaining tells in a line or two, then fix them.
5. **Keep the facts.** Never invent numbers, names, quotes or experiences to make text feel specific. Use a placeholder like `[real example]` and flag it.

Full pattern list with before and after examples: [references/patterns.md](references/patterns.md).

## Output format

For an edit:
```
[Rewritten text]

What changed (3 to 6 short lines, only the meaningful changes)
Placeholders to fill: any [real example] or [number] the user must supply
```

If the user asked for a quick edit, return only the rewritten text.

## Quality check

- [ ] No long dashes, no semicolons in body copy
- [ ] No banned vocabulary (delve, leverage, robust, crucial, pivotal, seamless, unlock, elevate, testament, tapestry, showcase...)
- [ ] No "not X, it's Y", forced threes or tag-on negations
- [ ] No chatbot openers or closers
- [ ] Sentence lengths vary
- [ ] Every big claim anchored in something specific and true
- [ ] Sounds like the person or brand, read aloud

## Related skills

Every skill in this pack runs this as its last step. Use **copywriting** if the problem is the message itself, not the wording.
