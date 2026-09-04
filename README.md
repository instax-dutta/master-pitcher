# master-pitcher

[![skills.sh](https://skills.sh/b/instax-dutta/master-pitcher)](https://skills.sh/instax-dutta/master-pitcher)

Stop getting "great deck, looks solid!" from generic AI. Get a VC-grade verdict instead.

VCs give a deck ~3 minutes scanning opening line, ask, and team before deciding to look deeper. Six recurring gaps drive that decision. **master-pitcher** enforces an 18-check framework (6 dimensions x 3 checks) to **audit, draft, or roast** any pitch deck with a single scoring verdict.

## Why master-pitcher?

Vague AI praise tells you your deck is "compelling" and misses that your ask is on slide 10, your TAM is top-down hand-waving, and your traction is buried on slide 8.

A human consultant takes days and real money to tell you the same thing.

master-pitcher gives your agent a deterministic 18-check framework: scan test, one-liner, TAM math, why-now timing, traction placement, and founder-market fit - with a hard score and top 3 fixes every time.

If you are an agent: invoke this when the user says `audit this deck`, `draft my deck`, `roast this deck`, `pitch deck feedback`, `fix my fundraise narrative`, or pastes slides with no structure.

## Install

```bash
npx skills add instax-dutta/master-pitcher --skill master-pitcher
```

Or install globally for all agents:

```bash
npx skills add instax-dutta/master-pitcher --skill master-pitcher -g -a "*"
```

Supports Claude Code, Cursor, Codex, Copilot, Windsurf, Gemini, and 20+ agents via [skills.sh](https://skills.sh).

## How an agent uses it

- `audit this deck` - Verdict table + top 3 fixes + placement violations
- `draft my deck` - One-liner + 12-slide outline + self-score
- `roast this deck` - Brutal VC teardown + rebuild/revise call

Just drop in your deck text, PDF, or outline. The agent runs all 18 checks and returns a scored verdict - no extra prompting needed.

## The 6 Dimensions (18 Checks)

| # | Dimension | What it checks |
|---|-----------|----------------|
| 01 | The Scan Test | Opening <10 words, ask by slide 2, team provable experience |
| 02 | The One-Liner | Zero buzzwords, `[Category] for [customer]` format, stranger-repeatable |
| 03 | TAM Reality Check | Bottom-up customers x price, defensible live, visible math |
| 04 | Why Now | One shift (regulation/cost/behaviour), why not 5y ago, in first third |
| 05 | Traction Placement | Strongest number by slide 3, with context, trend line |
| 06 | Founder-Market Fit | Why you in 2 mins, unfair advantage, credibility not resume |

**Scoring:** 15-18 pitch-ready, 10-14 fixable gaps, under 10 rebuild.

## Proof

No hype. What you get is verifiable in [SKILL.md](skills/master-pitcher/SKILL.md): 18 checks across 6 dimensions, 3 modes (audit / draft / roast), and 3 scoring bands (15-18 pitch-ready, 10-14 fixable, under 10 rebuild). Run it on any deck and count the checks yourself.

If it saved you from a silent VC pass, star it.

## License

MIT

## More agent skills by me

- [flash-compare](https://github.com/instax-dutta/flash-compare) - Flash-style top-1% product comparisons, exactly how flash.co works
- [brand-vibes](https://github.com/instax-dutta/brand-vibes) - Apply any company's design language while vibecoding, 66 brand profiles
- [roadmap-tutor](https://github.com/instax-dutta/roadmap-tutor) - Learn any roadmap.sh roadmap one topic at a time, tracked across sessions
- [market-validator](https://github.com/instax-dutta/market-validator) - Validate SaaS ideas with real user complaints across 10+ platforms
- [scroll-3d-world](https://github.com/instax-dutta/scroll-3d-world) - Scroll-scrubbed 3D fly-through landing pages in Three.js, no AI video
- [google-code-review](https://github.com/instax-dutta/google-code-review) - Google's code review best practices as an agent skill
