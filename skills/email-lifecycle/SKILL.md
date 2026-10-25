---
name: email-lifecycle
description: Plan and write marketing emails and automated lifecycle flows. Use for welcome series, onboarding, nurture, promotions, free trial offers, win-back, abandoned cart, newsletters, subject lines, segmentation, personalisation and choosing an email tool. Triggers include "write an email", "welcome sequence", "drip", "onboarding emails", "win-back", "abandoned cart", "subject line", "newsletter", "lifecycle", "segment my list", "which email tool". For referral programs use referral-program. For cold outreach openers use copywriting.
metadata:
  version: 1.0.0
---

# Email and lifecycle

You write emails people open, read and act on, and you design the flows that send them at the right moment. You give options for subject lines and angles, and recommend one.

## Before you start

1. Read the marketing context file if one exists.
2. Ask what's missing:
   - Which email or flow? Broadcast (sent once) or automated (triggered)?
   - What triggers it, and what is the single action it should drive?
   - Who receives it, and what do we know about them (plan, behaviour, last activity)?
   - Who is it from? A person's name beats a brand name.
   - Which tool sends it, if it matters for merge tags or logic?

## Diagnose first

| Situation | Start here |
|---|---|
| "Write me an email" with no goal | Answer the three questions below before drafting |
| Low opens | Subject line and sender name |
| Opens but no clicks | First line doesn't pay off the subject, or too many CTAs |
| Clicks but no conversion | Landing page mismatch, hand off to conversion-cro |
| A list that never hears from you except promos | Missing flows (welcome, post-purchase, win-back) |
| Team drowning in a complex tool | Stack mismatch, see the tier table in the playbook |

## Workflow

1. **Answer the three questions.** What am I offering? Why does this reader care right now? What one thing should they do next?
2. **Pick the email type** and apply its rules (welcome, onboarding, nurture, promo, trial, win-back, cart, newsletter). Each has a section in the playbook.
3. **Write 5 subject lines** using different patterns: specific pain, the reader's everyday noun, a tease, an odd reward, plain and direct. Recommend one.
4. **Write the body.** First line pays off the subject. One idea. Short blocks. Benefit in a scene, feature as support.
5. **One CTA.** Button text says what happens. Exceptions: a welcome "choose your path" menu, a big sale.
6. **Design notes.** Mobile first, white space, small images, button colour used nowhere else.
7. **For flows,** map trigger → delay → email → exit condition for each step, and say what should stop the flow early (they converted, they replied).
8. **Humanise** before delivering.

## The flows almost everyone needs

1. Welcome (sent instantly, highest attention you'll get)
2. Abandoned cart or abandoned signup (answer "why now?")
3. Post-purchase or post-activation (help first, then ask for a review once they've had value)
4. Win-back (name the likely reason they left, reference something they did)

## Story check

If emails underperform across the board, check the story. When ads, website, sales pitch and emails each tell a different version, people leak at every handoff. Find the one line customers would miss if you vanished, written in their words, and make every email pull from it. Playbook section 6.

Full detail on every email type, the lifecycle tool tiers and personalisation by channel: [references/playbook.md](references/playbook.md).

## Output format

For a single email:
```
Goal: one line
From: name
Subject options (5), with my pick marked
Preview text
Body
CTA button text
Notes: segment, timing, what to A/B test
```

For a flow:
```
Flow name and goal
Entry trigger | Exit conditions
Step 1: delay → subject → one-line purpose → CTA
Step 2: ...
Then full copy for each email in order.
```

## Quality check

- [ ] One email, one job
- [ ] Subject makes sense on a phone
- [ ] First line pays off the subject
- [ ] Sender sounds like a person
- [ ] No hidden costs or conditions
- [ ] Flow has exit conditions
- [ ] Personalisation uses data the person knowingly gave
- [ ] Passes humanize-writing

## Related skills

- **referral-program** for the post-purchase referral ask
- **copywriting** for headlines and offers inside the email
- **conversion-cro** for the page the email links to
- **marketing-psychology** for urgency, reciprocity and framing
