# Healthcare Trend Dashboard

## Project
Single-file executive healthcare dashboard for payer audience.
- **File:** `index.html` (3264 lines, self-contained)
- **Stack:** Vanilla JS, Chart.js (CDN), no build system
- **Deploy:** GitHub Pages → marsboy24/healthcare-trend-dashboard

## Audience & Standards
- Executive payer audience — concise, data-forward, no noise
- **Data sources:** Government/peer-reviewed required. Commercial sources must be flagged.
- All figures must be sourced. No placeholders.

## Current Sections
1. Overview — 6 KPI cards with drill-down driver panels
2. National Trends — NHE trajectory, spend composition, service mix, GDP comparison
3. Payer Landscape — 5 payer KPI cards, 4 charts, accordion table
4. Condition Drivers — Top 10 conditions: bar, detail card, bubble, payer mix

## Key Data (verified Q4 2024–Q1 2026)
- NHE 2024: $5.3T (+7.2%), per capita $15,474, 18.0% GDP
- Private insurance: $1.64T (+8.8%)
- Medicare: $1.12T (+7.8%), 54% MA penetration
- Medicaid: $931.7B (+6.6%), 76M enrollees
- Rx: $467B (+7.9%), GLP-1s $35B+ dominant driver
- Employer family premium 2025: $26,993 (KFF)

## Identified Gaps (priority build targets)
- GLP-1 dedicated spend section
- Medicare Advantage financial performance / overpayment
- Behavioral health spending (separate from prevalence)
- CBO federal health projections
- Health equity / SDOH data
- Hospital pricing transparency

## Interaction Patterns
- KPI cards → click → driver panel (animated bars + insights)
- Chart bars → click → in-card context panel
- Table rows → click → accordion detail

## Workflow
- Use `/plan` before adding any new section
- Use `search-first` + `market-research` skills when sourcing data for gaps
- Use `/verify` after significant changes before committing
- Use `/learn` at end of productive sessions to capture patterns
