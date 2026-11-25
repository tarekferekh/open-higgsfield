---
name: fityzone-content-performance-reporter
description: Import, normalize, analyze, and report FityZone Instagram or Metricool content performance. Use for CSV exports, monthly reviews, post and Reel comparisons, reach and retention diagnosis, saves, shares, watch time, profile actions, DMs, leads, client attribution, experiment tracking, and prioritized next actions.
---

# FityZone Content Performance Reporter

Read `marketing/brand-profile.md`, `fityzone-marketing-operator`, and `references/data-dictionary.md`.

## Import

1. Preserve the raw export and record source, account, timezone, export date, and reporting window.
2. Inspect column names and units before calculating. Map fields explicitly; do not assume blanks are zero.
3. Deduplicate by content ID or URL. Separate formats and incomplete reporting windows.
4. Join metadata such as pillar, hook, CTA, language, offer, and experiment when available.

Use `scripts/report_instagram.py` for a first-pass Markdown summary. Verify its aliases and calculations against the actual export.

## Analyze

Compare like-for-like posts using medians and totals. Separate reach, retention, engagement quality, profile action, lead, and conversion problems. Track reach, non-follower reach, plays, watch time, retention, completion, likes, comments, saves, shares, profile actions, DMs, leads, clients, and revenue where available.

Do not infer causation from correlation or one post. State sample size, missing fields, outliers, and data-quality issues.

## Report

Deliver scope and data quality; a KPI scorecard; winners and underperformers; explanations labeled as hypotheses; funnel bottlenecks; stop, continue, and test decisions; and three prioritized experiments with owner, metric, threshold, and review date.

Update durable Instagram working memory only with verified results. Never publish or change campaigns without approval.

