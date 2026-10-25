---
name: conversion-cro
description: Audit and improve pages and flows that should turn visitors into signups, buyers or booked demos. Use for landing page audits, homepage structure, product pages, checkout, pricing pages, review strategy, signup forms, onboarding and activation. Triggers include "why isn't this page converting", "audit my landing page", "CRO", "conversion rate", "checkout drop-off", "pricing page", "onboarding", "activation", "aha moment", "people sign up but don't use it". For the words alone use copywriting. For bias-level persuasion detail use marketing-psychology.
metadata:
  version: 1.0.0
---

# Conversion and CRO

You find where a page or flow leaks and tell the user what to fix first. Every recommendation names the problem, the fix and the reason, so the user can judge it against what they know about their traffic.

## Before you start

1. Read the marketing context file if one exists (`.agents/marketing-context.md` or `marketing-context.md`).
2. Get the asset: a URL, screenshot, pasted copy or a description of the flow. If you can open the page, do it. Check it at phone width too.
3. Ask only what's missing:
   - What counts as a conversion here?
   - Where does the traffic come from (ad, search, email, social)? The page has to match the promise that brought them.
   - Rough numbers if known: visitors, conversion rate, the step where people drop.
   - What has already been tested?

## The conversion equation

> Conversion = desire − effort − confusion

Before suggesting anything, decide which of the three is broken. Most pages fail on confusion first.

## Workflow

### For a landing page or homepage
Run the seven-step audit in order and stop to report the first big failure:
1. **Five-second test.** Can a stranger say what it is, who it's for and why they'd care?
2. **Headline and subheadline pair.** Claim, then logic. Never a restatement.
3. **Proof next to the claim.**
4. **CTA says what happens.**
5. **Friction count.** Every field, step and decision before value.
6. **Phone check.** Hero fits, CTA visible, proof renders.
7. **Speed.** Under two seconds. Delete before you optimise.

Then check section order against the buyer's questions: what is it → can I trust you → how does it work → what do I get → do people like me love it → what if it fails → final CTA.

### For checkout
Walk it as the buyer's gut feeling, in three moments: before they start (does this look safe?), while filling in (should I stop?), at the end (how do I feel?). Surprise costs and forced accounts are the top two killers.

### For onboarding and activation
1. Define the aha moment as an action plus a result ("connected their calendar and saw next week's free slots").
2. Compare retained users with churned users to find the early action that separates them.
3. List every step before that moment. Mark each as needed now, later or never.
4. Classify friction: don't know what to do, takes too long, don't believe it's worth it, it breaks.
5. Never show an empty product. Use sample data or templates.

### For pricing pages
Highlight one plan, say who it's for, default to the most common choice and make changing it quiet but easy.

Full detail for every flow, plus reviews and small psychological levers: [references/playbook.md](references/playbook.md).

## Output format

```
Verdict: the single biggest leak, in one sentence

Fix first (highest impact, lowest effort)
1. Problem → Fix → Why
2. ...

Fix next
...

Test ideas
- Hypothesis: if we [change], then [metric] moves because [reason]

Leave alone: things that already work and should not be touched
```

Rank by impact on the conversion, not by how easy the fix is to describe. Give rewritten copy only where copy is the problem.

## Quality check

- [ ] Did I identify which force (desire, effort, confusion) is broken?
- [ ] Is every recommendation tied to a reason?
- [ ] Did I check mobile?
- [ ] Did I say what to leave alone?
- [ ] Are test ideas written as hypotheses with a metric?

## Related skills

- **copywriting** for hero and section copy
- **marketing-psychology** for persuasion and pricing biases
- **email-lifecycle** for activation emails after signup
- **paid-ads** when the problem is ad-to-page mismatch
