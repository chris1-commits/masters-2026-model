# 2026 Masters Quantitative Winner Model

A data-driven analytics dashboard for the 2026 Masters Tournament.

**Live page:** https://chris1-commits.github.io/masters-2026-model/

## Features

- **30 contenders** profiled across **69 variables** each
- **12-factor composite scoring model** (SG T2G · SG Approach · SG Putting · OWGR · Augusta History · Recent Augusta · 2026 Form · Major Pedigree · Age · Market · Efficiency · Injury)
- **25 years of winner benchmarks** (2001–2025)
- Interactive tabs: Overview · Full Data Table · Radar Compare · Value Map (Scatter) · Benchmarks
- Chart.js visualisations: score breakdown bar chart, radar comparison, scatter plot, win score distribution

## Files

| File | Purpose |
|---|---|
| `index.html` | App shell & layout |
| `style.css` | Design system & component styles |
| `data.js` | Player dataset + benchmark constants |
| `app.js` | Rendering logic & chart initialisation |

## Model Weights

| Factor | Max Points |
|---|---|
| SG Tee-to-Green | 15 |
| SG Approach | 10 |
| SG Putting | 7 |
| OWGR | 10 |
| Augusta History | 12 |
| Recent Augusta | 8 |
| 2026 Form | 10 |
| Major Pedigree | 8 |
| Age | 5 |
| Market (Odds) | 5 |
| Efficiency | 5 |
| Injury | penalty |
| **Total** | **100** |
