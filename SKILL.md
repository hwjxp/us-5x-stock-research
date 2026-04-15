---
name: us-5x-stock-research
description: Use when the user wants to study, screen, or review U.S. stocks with potential to become 5x to 10x multi-baggers. Supports regime analysis, theme selection, leader identification, catalyst mapping, market-cap and float filters, technical entry review, and post-mortem comparison against historical U.S. 5x winners. Also use when the user wants a repeatable investing framework or stock-picking checklist focused on major winners rather than broad diversification.
---

# US 5x Stock Research

Use this skill to study U.S. stocks through the lens of `5x-10x` winner selection.

This skill is not for:

- generic retirement allocation
- passive ETF portfolio construction
- options Greeks modeling without a stock thesis
- penny-stock pumping without business, liquidity, and catalyst validation

## Core Goal

Find stocks where the market is still underestimating:

- the size of the opportunity
- the speed of the inflection
- the strength of the leader
- the durability of the trend

The working model is:

`regime -> theme -> leader -> catalyst -> sizing -> technical execution`

## Quick Start

Good invocations:

- `用这个 skill 帮我筛美股里最像下一只 5x 的票。`
- `分析这只股票有没有成为 5x 龙头的潜力。`
- `把这份候选名单按 5x 潜力打分。`
- `复盘过去 10 年的 5x 股共性。`
- `帮我看这只票现在是不是技术上适合买点。`

When this skill triggers:

1. Identify whether the task is `screen`, `single-name deep dive`, `historical study`, or `trade timing`.
2. Use live sources for current prices, market caps, earnings dates, and other unstable financial facts.
3. Separate `clean full-year historical samples` from `special-case samples` such as spinoffs or relistings.
4. Judge the stock first on business and catalyst quality, then on chart structure.
5. Return a decision-ready output with explicit invalidation conditions.

## Workflow

### 1. Regime Check

Start with market backdrop:

- liquidity and rates
- risk appetite
- whether the market is rewarding early growth, turnarounds, cyclicals, or pure narrative
- whether 5x names are broadening or concentrated in one theme

Read:

- [references/framework.md](./references/framework.md)

### 2. Theme Selection

Prefer themes where a few leaders can capture outsized economics:

- AI infrastructure / software re-acceleration
- biotech with major readouts or first-in-class potential
- energy, shipping, commodities, or hardware when supply-demand shifts are extreme
- crypto-adjacent equities when liquidity and narrative align
- turnaround stories only when balance-sheet survival is credible

Avoid treating every hot story as a valid theme. A real theme should have capital flow, earnings-path relevance, or a hard catalyst chain.

### 3. Leader Filter

Prefer names that are already leader or clear strong number two:

- strongest revenue or user acceleration
- clearest category positioning
- best product or cost curve
- improving margins or balance sheet
- enough liquidity for institutional participation

Use the detailed scoring dimensions in:

- [references/framework.md](./references/framework.md)

### 4. Market Cap and Float Filter

For 5x studies, focus on the sweet spot where upside is still mathematically possible but liquidity is real.

Default framing:

- under `$500M`: extreme risk, often too noisy unless catalyst quality is exceptional
- `$500M-$5B`: fertile 5x zone, but survival and liquidity need more scrutiny
- `$5B-$30B`: best balance of scale, credibility, and multi-bagger room
- above `$30B`: still investable, but 5x usually requires a rare re-rating and major earnings expansion

Always inspect:

- free-float quality
- average dollar volume
- short interest
- recent dilution or unlock risk

### 5. Technical Execution

Do not treat 5x winners as random bottom bounces.

Prefer charts that already show:

- reclaim of `50DMA`
- reclaim of `200DMA`
- breakout above a meaningful base or prior range
- volume expansion on the breakout
- ability to trend above `50DMA` after breakout

Use:

- [references/technical-setups.md](./references/technical-setups.md)
- [references/entry-and-exit-strategy.md](./references/entry-and-exit-strategy.md)
- [references/position-sizing.md](./references/position-sizing.md)
- [references/trade-management-playbook.md](./references/trade-management-playbook.md)

### 6. Historical Anchoring

When comparing a candidate against past winners:

1. Use only relevant analogs.
2. Flag whether the analog is a `persistent trend leader`, `high-beta momentum trend`, `event-driven revaluation`, or `mania/squeeze`.
3. Do not anchor on distorted samples without noting the distortion.

Use:

- [references/sample-universe.md](./references/sample-universe.md)

### 7. Output

Prefer a decision-ready structure:

- thesis
- why now
- what must happen for 5x to remain possible
- technical setup
- invalidation
- ranking versus other candidates

Use:

- [references/output-template.md](./references/output-template.md)
- [references/scorecard-zh.md](./references/scorecard-zh.md)
- [references/checklists-zh.md](./references/checklists-zh.md)
- [references/entry-and-exit-strategy.md](./references/entry-and-exit-strategy.md)
- [references/position-sizing.md](./references/position-sizing.md)
- [references/trade-management-playbook.md](./references/trade-management-playbook.md)

## Technical Rules

- A stock can be early fundamentally but should not be technically broken unless the user explicitly wants deep-value turnaround hunting.
- When a name is already far above `50DMA`, distinguish `healthy leadership` from `late-stage euphoria`.
- Treat violent squeeze patterns and steady institutional trends as different species.
- For historical studies, summarize chart behavior rather than narrating every candle.
- Separate `selection quality` from `execution quality`; a good stock bought badly can still be a poor trade.
- Prefer staged entry, staged adds, and staged trimming over all-in / all-out behavior.

## Research Rules

- Use live sources for unstable facts such as price, market cap, earnings date, current float, guidance, and analyst expectations.
- Prefer primary or company sources for catalysts: earnings releases, investor decks, FDA updates, SEC filings, company blogs, and exchange announcements.
- Be explicit when a conclusion is inference rather than directly stated by a source.
- If a historical sample is a spinoff, relisting, ticker-history distortion, or merger artifact, mark it as `special-case` before using it as a pattern anchor.

## Default Deliverables

Depending on the request, return one of these:

- `5x Potential Scorecard`
- `Historical Analog Review`
- `Technical Setup Review`
- `Buy / Add / Trim / Exit Plan`
- `中文评分卡`
- `中文执行清单`
- `Entry / Exit Plan`
- `Position Sizing Plan`
- `Trade Management Playbook`

## Resources

- [references/framework.md](./references/framework.md): full investing framework and scoring dimensions
- [references/technical-setups.md](./references/technical-setups.md): chart patterns and execution rules
- [references/sample-universe.md](./references/sample-universe.md): remembered sample names and caveats
- [references/output-template.md](./references/output-template.md): response templates
- [references/scorecard-zh.md](./references/scorecard-zh.md): Chinese 5x scoring card
- [references/checklists-zh.md](./references/checklists-zh.md): Chinese buy/add/trim/avoid checklist
- [references/entry-and-exit-strategy.md](./references/entry-and-exit-strategy.md): entry and exit framework
- [references/position-sizing.md](./references/position-sizing.md): risk and sizing framework
- [references/trade-management-playbook.md](./references/trade-management-playbook.md): staged execution and position management
