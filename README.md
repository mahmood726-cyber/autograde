# AutoGRADE v1.0

**Automated GRADE Certainty Assessment Tool**

A single-file, browser-based tool that takes meta-analysis results and produces transparent, publication-ready GRADE certainty assessments with Summary of Findings and Evidence Profile tables.

## Quick Start

1. Open `AutoGRADE.html` in any browser
2. Enter your meta-analysis results (or paste metafor output)
3. Answer the guided GRADE domain questions
4. Click "Assess GRADE Certainty"
5. Copy the SoF table into your manuscript

No installation, server, or internet required.

## Features

- **Input**: Manual form + paste box (accepts metafor, RevMan, plain text)
- **5 GRADE domains**: 2 auto-computed (inconsistency, imprecision) + 3 guided (RoB, indirectness, publication bias)
- **Outputs**: Visual summary, Evidence Profile table, Summary of Findings table, manuscript text
- **Export**: Copy HTML (paste into Word), CSV download, manuscript text
- **Multi-outcome**: Up to 7 outcomes per assessment
- **Transparent**: Every downgrade decision shows reasoning and evidence
- **Offline**: Single HTML file, zero dependencies, works on file://

## GRADE Domains

| Domain | Method | Auto/Guided |
|--------|--------|-------------|
| Risk of Bias | Proportion dropdown with guidance | Guided |
| Inconsistency | I², Q, prediction interval | Auto (overridable) |
| Indirectness | 4 PICO sub-questions | Guided |
| Imprecision | CI null crossing + OIS | Auto (overridable) |
| Publication Bias | Funnel + Egger + unpublished | Guided |

## License

MIT
