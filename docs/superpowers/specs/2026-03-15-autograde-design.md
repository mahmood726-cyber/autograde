# AutoGRADE — Automated GRADE Certainty Assessment Tool

## Date: 2026-03-15
## Status: APPROVED

## Overview
Single-file HTML tool (~50-100KB) that takes meta-analysis results as input and produces transparent, publication-ready GRADE certainty assessments with Summary of Findings and Evidence Profile tables.

## Architecture
- Single HTML file, zero external dependencies
- Works offline on file:// protocol
- Pure forms + tables + CSS (no Plotly, no WebR)
- TextExtractor patterns (ported from LivingMeta) for paste-box parsing

## Input
- Manual form: outcome name, effect measure, pooled estimate, CI, I², Q, k, N, CER, tau²
- Paste box: accepts metafor output, RevMan XML, LivingMeta JSON, plain text
- Multi-outcome: up to 7 outcomes per assessment
- Form pre-fills from pasted data

## GRADE Assessment (5 domains)
- Auto-computed: Inconsistency (I², Q, PI), Imprecision (CI null crossing, OIS)
- Guided: RoB (proportion dropdown), Indirectness (4 sub-questions), Publication Bias (funnel + Egger + unpublished)
- Each domain: traffic light + downgrade level + footnote reason

## Output
- Visual certainty summary (bar + traffic lights + plain language)
- Evidence Profile table (standard GRADE EP format)
- Summary of Findings table (Cochrane SoF format with NNT)
- Export: copy HTML, CSV, manuscript text

## Target
BMJ Evidence-Based Medicine or Journal of Clinical Epidemiology
