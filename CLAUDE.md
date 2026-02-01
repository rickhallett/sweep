# sweep

Memory consolidation and synthesis CLI for HAL's cognitive maintenance.

## Purpose

- **Consolidation sweeps** — Process memory files, identify patterns, extract insights
- **Synthesis and redundancy cleanup** — Deduplicate, merge, and prune stale entries
- **Frequent operations** — Go/Python CLI for common memory maintenance tasks
- **Audit log** — Track all consolidation operations for transparency

## Commands (Planned)

```
sweep scan       # Scan memory files for consolidation opportunities
sweep merge      # Merge redundant entries
sweep prune      # Remove stale/obsolete entries
sweep audit      # Show consolidation history
sweep status     # Report memory health metrics
```

## Stack

- Go CLI (primary)
- Python utilities (analysis/NLP helpers if needed)

## Status

🚧 Initial scaffold — not yet functional
