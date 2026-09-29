# Nihongo Immersion Analysis

Analysis of my own Japanese immersion log (2023–2026), exported from NihongoTracker —
anime, visual novels, manga, and light novels consumed while learning Japanese.

## Why this project

Instead of a generic tutorial dataset, this uses ~3 years of my own study data to
answer a real question: **how much has my Japanese reading speed actually improved?**

## Key finding

Reading speed (characters/minute) grew roughly 5x between October 2023 (~50 cpm) and
peak months in 2026 (~250 cpm) — quantifiable evidence of progress toward JLPT N1,
not self-reported estimation.

## Stack

Python · pandas · matplotlib

## Structure

```
data/          raw exported CSV
notebooks/     EDA notebook
```

## Next steps

- Study consistency: streaks, day-of-week patterns
- Enrich with VNDB/AniList APIs via `mediaId` (genre/tags vs. reading speed)
- Simple predictive model: estimate time-to-finish based on length + current pace
