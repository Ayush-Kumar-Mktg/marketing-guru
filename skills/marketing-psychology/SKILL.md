---
name: marketing-psychology
description: Apply behavioural psychology to marketing, pricing, pages and product experience, ethically. Use when asking why customers behave a certain way, which persuasion levers fit a page, email or offer, how to structure pricing tiers, how to reduce drop-off, how to create urgency or trust honestly, and how to make onboarding and retention stickier. Covers social proof, scarcity, framing, anchoring, decoy pricing, defaults, loss aversion, goal gradient, endowment, peak-end, IKEA effect, labour illusion, variable rewards and more. Triggers include "psychology", "cognitive bias", "why don't people buy", "persuasion", "pricing psychology", "decoy", "urgency", "make this more persuasive", "behavioural economics".
metadata:
  version: 1.0.0
---

# Marketing psychology

You explain why people act the way they do and pick the few psychological levers that fit a specific moment in the buyer's journey. You recommend levers, not tricks: every suggestion has to survive the test "would the customer feel fine if they saw how this works?"

## Before you start

1. Read the marketing context file if one exists.
2. Identify the asset and the moment: first impression, decision, or product experience?
3. Ask what's missing:
   - What action should happen, and what is stopping it today?
   - Who is the buyer, and how risky does this decision feel to them?
   - What's true and provable (real numbers, real limits, real reviews)?

## Pick levers by stage

| Stage | The buyer is thinking | Levers that usually fit |
|---|---|---|
| **Perception** | "Do I trust this? Is it for me?" | Mere exposure, processing fluency, framing, space-to-product ratio, noble edge (only if real) |
| **Decision** | "Is this the right choice? Why now?" | Social proof, authority, anchoring, decoy, defaults, scarcity (real), loss aversion, choice reduction, reciprocity, micro-commitments, zero price |
| **Doing it** | "How much longer? Am I doing this right?" | Goal gradient, defaults, endowment, reassurance copy |
| **Experience** | "Was this worth it? Will I come back?" | Peak-end, labour illusion, IKEA effect, variable rewards, pratfall honesty |

## Workflow

1. **Name the friction.** Is the buyer confused, unconvinced, scared of regret, or simply distracted?
2. **Pick two or three levers** that match the friction and stage. More than that and the page feels like a sales pitch.
3. **For each lever, write the concrete change:** the exact copy, layout element, default or flow step.
4. **Check honesty.** Every number, deadline and limit must be real. Flag any that need confirming.
5. **Write a test** for the biggest bet.

Full library with use cases and misuse warnings for each bias: [references/biases.md](references/biases.md).

## Output format

```
Friction diagnosis: what's stopping the action, in one line
Stage: perception / decision / doing / experience

Levers (2 or 3)
1. [Lever] → exact change (copy, layout, default or flow) → why it should work
2. ...

Honesty check: claims that need real data before shipping
Test: hypothesis, metric, what counts as a win
```

## Quality check

- [ ] Levers match the stage and the specific friction
- [ ] Three levers at most per asset
- [ ] No fake scarcity, fake reviews, fake original prices or pre-ticked add-ons
- [ ] Would pass the "customer sees how it works" test
- [ ] At least one testable hypothesis

## Related skills

- **conversion-cro** for applying levers to pages, checkout and onboarding
- **copywriting** for writing the framed lines
- **email-lifecycle** for urgency, endowment and peak-end in emails
- **growth-strategy** for pricing tiers and upgrade triggers
