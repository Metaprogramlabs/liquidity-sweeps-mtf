# Changelog

## [1.0.0] - 2026-10-24

### Added
- Two independent liquidity sources (Liquidity 1 and Liquidity 2), each with its own timeframe
- Timeframe modes: Auto, Select TF, X+1 TF, X+2 TF, X+3 TF
- Swing detection depth: Short, Intermediate and Long Term
- Sweep detection: wick beyond a swing level and close back inside
- Level merging: levels of different timeframes within N ticks become one line with a combined label (for example `Sweep H1+H4`)
- One line per candle when several levels are swept at once
- Invalidation by candle Close or candle Body
- Maximum level age, per-timeframe line style, custom colors and label text
