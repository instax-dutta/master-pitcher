# master-pitcher

[![skills.sh](https://skills.sh/b/instax-dutta/master-pitcher)](https://skills.sh/instax-dutta/master-pitcher)

VCs give a deck ~3 minutes scanning opening line, ask, and team before deciding to look deeper. Six recurring gaps drive that decision. **master-pitcher** enforces an 18-check framework (6 dimensions x 3 checks) to **audit, draft, or roast** any pitch deck with a single scoring verdict.

## Install

```bash
npx skills add instax-dutta/master-pitcher --skill master-pitcher
```

Or install globally for all agents:

```bash
npx skills add instax-dutta/master-pitcher --skill master-pitcher -g -a "*"
```

Supports Claude Code, Cursor, Codex, Copilot, Windsurf, Gemini, and 20+ agents via [skills.sh](https://skills.sh).

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

## Modes

- `audit this deck` - Verdict table + top 3 fixes + placement violations
- `draft my deck` - One-liner + 12-slide outline + self-score
- `roast this deck` - Brutal VC teardown + rebuild/revise call

## Example

See [SKILL.md](skills/master-pitcher/SKILL.md) for full framework, quick reference, and templates.

## License

MIT
