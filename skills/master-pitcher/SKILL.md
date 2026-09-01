---
name: master-pitcher
description: Use when auditing, drafting, roasting, or rewriting a pitch deck, fundraising narrative, or VC presentation - or when the founder needs feedback on opening line, TAM, traction placement, why-now timing, or team credibility
---

# Master Pitcher

## Overview

VCs give a deck ~3 minutes scanning opening line, ask, and team before deciding to look deeper. Six recurring gaps drive that decision. This skill enforces an 18-check framework (6 dimensions x 3 checks) to audit, draft, or roast any deck with a single scoring verdict.

**Core principle:** If it fails the 3-minute scan, nothing else matters.

## When to Use

- Auditing an existing deck before a VC meeting
- Drafting a new deck from scratch or outline
- Roasting a deck to find brutal gaps
- Rewriting one-liner, TAM slide, or founder story
- Founder asks "is my deck ready?" or "what's wrong with my pitch?"

When NOT to use: internal product roadmaps, sales decks for customers, public marketing site copy.

## The Framework - 18 Checks

Score 1 per check. 15-18 = pitch-ready. 10-14 = fixable gaps, revise before next meeting. Under 10 = rebuild before booking more VC time.

| # | Dimension | 3 Checks (1 pt each) |
|---|-----------|----------------------|
| 01 | **The Scan Test** | (a) Opening line explains what you do in under 10 words (b) Ask (amount + use of funds) appears by slide 2 (c) Team slide shows relevant, provable experience - not just job titles |
| 02 | **The One-Liner** | (a) One sentence, zero buzzwords (b) Format: `[Category] for [specific customer]` - the way [known company] did for [known problem] (c) Stranger could repeat it back correctly after hearing once |
| 03 | **The TAM Reality Check** | (a) Bottom-up (customers x price), not top-down (% of big number) (b) Every number defensible live, unscripted (c) No leading rupee/dollar figure without visible math behind it |
| 04 | **The Why Now** | (a) One shift named - regulation, cost curve, or behaviour (b) Addresses why not possible/attractive 5 years ago (c) Appears in first third of deck, not buried at end |
| 05 | **Traction Placement** | (a) Strongest number (revenue, retention, waitlist, users) by slide 3 (b) Number includes context/comparison, not raw total (c) Trend line shown, not single snapshot |
| 06 | **Founder-Market Fit** | (a) Why you / why this problem answered in first 2 minutes (b) Unfair advantage shown - data, network, expertise, or timing (c) Founder slide reads as credibility argument, not resume |

## Modes - Output Contracts

Pick one mode per invocation. Output MUST match this shape or it is incomplete.

### Mode 1: AUDIT - `audit this deck`

Output shape IN ORDER:

1. **Verdict line:** `Score: X/18 - [pitch-ready | fixable gaps | rebuild]`
2. **Dimension table:** 6 rows, each `0-3/3` with which checks failed and why (cite slide numbers)
3. **Top 3 fixes ranked:** highest leverage first, each as `Fix: [current] -> [rewrite]`
4. **Placement violations:** list any ask/traction/why-now slide-number violations

### Mode 2: DRAFT - `draft my deck`

Output shape IN ORDER:

1. **One-liner** in required format (Category for customer - way X did for Y), under 20 words, zero buzzwords
2. **Slide outline 1-12:** each slide has title + 1-line content rule + placement constraint
   - Slide 1: Opening (<10 words what you do)
   - Slide 2: Ask (amount + use of funds) + why-now teaser
   - Slide 3: Traction (strongest number + context + trend)
   - Slides 4-6: Problem, Solution, Why Now (full)
   - Slides 7-8: Market (bottom-up math), Business Model
   - Slides 9-10: Team (provable experience) + Founder-Market Fit
   - Slides 11-12: Go-to-market, Closing/Contact
3. **Self-score:** score the draft you just produced against the 18 checks

### Mode 3: ROAST - `roast this deck`

Output shape IN ORDER:

1. **Roast line:** one brutal sentence a VC would think but not say
2. **Score: X/18 - verdict** (same scale)
3. **6-dimension teardown:** each dimension scored `0-3/3`, brutal tone, cite exact slide/bullet that fails
4. **Rebuild or revise call:** explicit `REBUILD` if under 10 else `REVISE` with 3 must-fix items

## Implementation Steps

1. Identify mode from user intent (audit/draft/roast). If ambiguous, ask.
2. Extract or request: opening line, ask + use of funds, slide order, TAM math, traction numbers, team bios, why-now shift.
3. Score all 18 checks. Be strict - unchecked = 0, no partial credit, no charity.
4. Produce output matching the mode contract exactly. Never skip verdict, table, or placement checks.
5. End with one question: "Want me to rewrite the 3 failing slides?"

## Quick Reference

| Symptom | Failing Dimension | Instant Fix |
|---------|-------------------|-------------|
| Opening has "revolutionizing", "synergy", "ecosystem", "disrupt" | 02 One-Liner | Rewrite as `[Category] for [customer]` without adjectives |
| TAM says "$XT market, we get 1%" | 03 TAM | Replace with `(# customers x $ price = $Y)` bottom-up |
| Ask on last slide or no use-of-funds | 01 Scan Test | Move to slide 2: `$XM - 40% eng, 30% GTM, 30% ops` |
| Traction on slide 6+ or "500 users" alone | 05 Traction | Move to slide 3: `500 users, 40% WoW, 3x vs last month chart` |
| "Why now: AI is hot" or no why-now | 04 Why Now | Name one shift: `GPU cost fell 10x since 2022, now viable` |
| Team: "CEO, CTO" with no proof | 01 + 06 Fit | `Ex-Stripe, shipped payments for 2M merchants` |
| Buzzword one-liner stranger can't repeat | 02 One-Liner | Test: read to stranger, can they repeat in 5 sec? |

## Common Mistakes

- **Charity scoring:** giving 1 for "almost" - if check is not fully met, score 0. VCs do.
- **Top-down TAM:** "% of $2T market" always scores 0 on 03(a) and 03(c). Must show customers x price math.
- **Burying the ask/traction:** even a great traction number scores 0 on 05(a) if on slide 6. Placement is the check.
- **Resume team slide:** listing titles without `shipped X for Y` proof fails both 01(c) and 06(c).
- **Vague why-now:** "market is ready" or "timing is perfect" fails 04(a) - must name regulation, cost curve, or behaviour shift.
- **Buzzword one-liner:** "AI-powered synergistic platform democratizing..." fails 02(a)(b)(c) simultaneously. Rewrite from scratch.

## Example

**Before (0/3 on One-Liner):** "We leverage cutting-edge paradigm-shifting infrastructure to democratize finance for everyone"

**After (3/3):** "Expense management for freelance designers - the way Zerodha did for retail traders" (12 words, category + customer + anchor, repeatable)

**Before (0/3 on TAM):** "India fintech is $2.3T, capturing 1% = $23B"

**After (3/3):** "4.2M freelance designers x Rs 800/mo x 12 = Rs 4,032 Cr SAM; 10% SAM = Rs 403 Cr SOM" (bottom-up, defensible, math visible)

## Scoring Template (copy-paste)

```
Score: __/18 - [pitch-ready | fixable gaps | rebuild]

| # | Dimension | Score | Failed checks & evidence |
|---|-----------|-------|--------------------------|
| 01 | Scan Test | _/3 | |
| 02 | One-Liner | _/3 | |
| 03 | TAM | _/3 | |
| 04 | Why Now | _/3 | |
| 05 | Traction | _/3 | |
| 06 | Founder Fit | _/3 | |
```
