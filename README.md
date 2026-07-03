# gefei-perspective-skill

A Claude Code Skill distilled from 哥飞's 15K+ Jike posts and 11 key longform articles.

This is a thinking aid, not an impersonation tool. It should cite source `post_id`s when using 哥飞's views, and it should mark uncertain or out-of-scope answers as inference instead of presenting them as his position.

## What it does

When you're working on overseas SaaS, SEO, AdSense, indie tool sites, paid traffic ROI, or AI product monetization, this skill provides:

- **Mental Models** — core beliefs and frameworks
- **Heuristics** — "when X, then Y" decision rules
- **Anti-patterns** — things 哥飞 explicitly says NOT to do
- **Signature Phrases** — recurring expressions that signal his judgment style
- **Honest Limits** — areas he admits he doesn't know well

All perspectives include verbatim quotes and source post IDs.

## Community review materials

- `FIDELITY.md` - independent answer/scoring run against the Nuwa fidelity scorecard
- `references/research/` - corpus inventory, traceability notes, source index, and fidelity test artifacts

## Install

```bash
cp -r . ~/.claude/skills/gefei-perspective
```

Or clone directly:

```bash
cd ~/.claude/skills
git clone https://github.com/tens1x/gefei-perspective-skill gefei-perspective
```

## Topics covered

| # | Topic | Posts | Longforms |
|---|-------|------:|----------:|
| 01 | Paid Traffic & ROI | 203 | 3 |
| 02 | SEO & Google Algorithm | 839 | 8 |
| 03 | Overseas / Tool Sites | 613 | 8 |
| 04 | AdSense & Ad Monetization | 90 | 2 |
| 05 | AI Tools & Model Selection | 207 | 1 |
| 06 | Niche & Keyword Selection | 558 | 5 |
| 07 | Pricing & ARPU | 125 | 0 |
| 08 | Indie Dev Mindset | 416 | 1 |
| 09 | Case Studies | 201 | 1 |
| 10 | Content Ops & Growth | 1215 | 8 |
| 11 | Anti-patterns | 107 | 2 |

## Methodology

Built using the [nuwa-skill](https://github.com/alchaincyf/nuwa-skill) 5-layer extraction methodology.

## Ethical Boundary

Use this repository to consult a public product/operator perspective. Do not use it to impersonate 哥飞, claim endorsement, harass others, or make high-stakes medical, legal, or investment decisions.

## License

MIT
