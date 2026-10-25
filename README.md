# marketing-guru

**Marketing skills for your AI agent. It gives you the angles. You do the thinking.**

marketing-guru is a pack of 16 marketing skills for Claude Code, Claude and any agent that reads `SKILL.md` files. Ask it to fix a headline, plan a launch, audit a landing page or figure out why your LinkedIn posts are not landing. It works out what the real problem is, looks at it from a few different marketing angles, and hands you options with a clear pick.

It will not do your thinking for you. That is on purpose. You know your customer better than any model does. This pack makes your next move obvious.

Everything inside is written from scratch in plain words. It is built from the marketing newsletters, growth playbooks and books I keep going back to, rewritten as frameworks, checklists and examples you can use straight away.

---

## How the skills work together

```
                      marketing-context
              (your product, audience, voice, proof)
                              │
                       every skill reads it
                              │
                       marketing-guru
              (diagnoses the problem, routes the task)
                              │
   ┌──────────┬──────────┬────┴─────┬──────────┬──────────┐
 words      pages      channels    strategy   systems
   │          │          │           │           │
copywriting conversion  email       positioning ai-marketing
            -cro        social      growth      -workflows
                        seo         psychology
                        paid ads
                        influencers
                        referrals
                        launches
                              │
                      humanize-writing
               (final pass on everything it writes)
```

Run `marketing-context` once. It saves a short file about your business, so every other skill starts informed and asks fewer questions.

---

## The skills

| Skill | Use it for |
|---|---|
| **marketing-guru** | The front door. Not sure which skill fits? Start here. It routes, pressure-tests and gives you angles. |
| **marketing-context** | Saving your product, audience, customer language, proof and voice in one file every skill reads. |
| **copywriting** | Headlines, value props, taglines, hero sections, product descriptions, ad angles. |
| **conversion-cro** | Landing page audits, checkout, pricing pages, reviews, onboarding and activation. |
| **email-lifecycle** | Welcome series, nurture, promos, win-back, abandoned cart, subject lines, segmentation. |
| **referral-program** | Refer-a-friend programs, rewards, swipe copy and the timing of the ask. |
| **social-content** | LinkedIn and X posts, hooks, content calendars, Reddit and communities, DMs, lead magnets. |
| **seo-ai-search** | Keyword plans, page types, content audits, and showing up in AI answers (AEO). |
| **paid-ads** | Diagnosing ad accounts, picking hooks and formats, test plans, budgets, measurement. |
| **influencer-marketing** | Finding creators, briefs, agreements, ambassador programs and tracking. |
| **product-launch** | Launch plans, launch-day run sheets, waitlists and launch platforms. |
| **positioning-and-brand** | Positioning, point of view, mission, story, voice and rebrand decisions. |
| **growth-strategy** | Why growth is stuck, flywheels vs boosters, PLG, pricing tiers, B2B go-to-market. |
| **marketing-psychology** | The behavioural levers behind persuasion, pricing and retention, used honestly. |
| **ai-marketing-workflows** | Turning repeat work into skills, team AI systems, small marketing tools, your stack. |
| **humanize-writing** | Making any text read like a person wrote it. Every other skill ends with this pass. |

Each skill has its own `SKILL.md` (when to use it, what to ask first, the workflow, the output format and a quality check). Most also have a `references/` folder with the deeper playbook.

---

## Try these

Copy any of these into your agent once the pack is installed:

1. `Rewrite the hero section of my homepage. Here is the current copy: ...`
2. `Audit this landing page and tell me the one thing to fix first: [URL]`
3. `Write a 5-email welcome sequence for people who just signed up for our free plan.`
4. `Give me 5 hooks for a LinkedIn post about how we lost our biggest client and what we changed.`
5. `Our Meta ads stopped working. Here are the numbers. What is actually broken?`
6. `Build a keyword plan for a project management tool for small architecture firms.`
7. `Why does ChatGPT never recommend us when people ask for tools in our category?`
8. `We sound like every competitor. Help me find a point of view.`
9. `Plan our launch on a launch platform 4 weeks from now. We have 600 people on our list.`
10. `Design a referral program for a meal subscription brand.`
11. `Which psychology levers should I use on our pricing page, honestly?`
12. `Turn our webinar transcript into a week of posts, one newsletter and three emails.`
13. `This post sounds like AI wrote it. Fix it.`

---

## Install

### Option 1: Claude Code plugin (recommended)

```
/plugin marketplace add Ayush-Kumar-Mktg/marketing-guru
/plugin install marketing-guru@marketing-guru
```

### Option 2: Skills CLI

```
npx skills add Ayush-Kumar-Mktg/marketing-guru
```

Add `--skill copywriting` (or any skill name) to install just one.

### Option 3: Copy the folders

```
git clone https://github.com/Ayush-Kumar-Mktg/marketing-guru.git
cp -r marketing-guru/skills/* ~/.claude/skills/
```

For a single project, copy them into `.claude/skills/` inside that project instead.

### Option 4: Claude on the web or desktop

1. Download the ZIP for the skill you want from the [`zips`](zips/) folder. Start with `marketing-guru.zip`, `marketing-context.zip` and `humanize-writing.zip`, then add the specialists you need.
2. In Claude, open the Skills section in Settings and upload each ZIP.
3. Start a chat and ask for what you need.

---

## How it writes

Every skill finishes with the `humanize-writing` pass by default. Want the raw draft instead? Say "skip humanize". You can also run `humanize-writing` on its own to clean up any text you already have. With the pass on, what you get back:

- has no long dashes, no "delve", no "unlock", no "seamless"
- skips "Great question!" and "I hope this helps"
- does not invent stats, testimonials or results (it leaves a placeholder for you to fill)
- never attacks a competitor by name
- takes a position instead of hiding behind "it depends"

---

## Contributing

Spotted something wrong or have a framework that belongs here? Open an issue. I read all of them. Only I can merge changes, so suggestions go through issues.

---

## License

MIT. Use it, change it, share it. See [LICENSE](LICENSE).

---

## About

Made by Ak, a B2B marketer. I write about how brands get people to notice what they built.

[LinkedIn](https://www.linkedin.com/in/ayushkumar-marketing/) · [Instagram](https://www.instagram.com/akbrandlab/) · [GitHub](https://github.com/Ayush-Kumar-Mktg)
