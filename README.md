# CarbonIQ 🌱

**Understand, track, and shrink your carbon footprint — built for India.**

A personal carbon footprint coach that turns everyday lifestyle inputs into a meaningful annual CO₂ number, ranks the highest-impact changes *for you*, and lets you track your reductions over time.

Built for **PromptWars Challenge 3 — Carbon Footprint Awareness Platform**.

🔗 **Live demo:** [shridhoot2222.github.io/carboniq](https://shridhoot2222.github.io/carboniq/)

---

## Why this is different

Most carbon calculators run on US/EU emission factors and compare you to a global average that means nothing locally. CarbonIQ is grounded in **India-specific numbers** — the CEA grid intensity, LPG cylinders, Indian transport modes — and benchmarks you against the **Indian per-capita footprint (~1,900 kg/yr)** and the **global sustainable target (~2,000 kg/yr)**. The result is a number that's actually relevant to where you live.

## The three jobs (mapped to the brief: *understand · track · reduce*)

| Tab | What it does |
|-----|--------------|
| **Understand** | A short lifestyle form → annual CO₂ broken down by Transport / Home Energy / Food / Goods on an animated donut, plus a "you vs average Indian vs sustainable target" comparison. |
| **Reduce** | Simple actions **ranked by CO₂ saved for your specific inputs**, plus a live *what-if simulator* (meat-free days, AC temperature, car→metro swaps) that recomputes your projected footprint as you drag. |
| **Track** | Commit actions to a plan, keep a daily streak, watch cumulative kg saved grow, and see a projected trend line bending toward the target. |

## Emission factors

| Source | Factor |
|--------|--------|
| Grid electricity | 0.71 kg CO₂ / kWh |
| LPG cylinder (14.2 kg) | 42.5 kg CO₂ |
| Petrol car | 0.18 kg / km |
| Two-wheeler | 0.05 kg / km |
| Metro / train | 0.015 kg / km |
| Bus | 0.05 kg / km |
| Domestic flight (1 hr) | 150 kg |
| Diet (veg / non-veg / vegan) | 1000 / 1600 / 750 kg/yr |
| New goods | 0.5 kg CO₂ / ₹100 |

_References: Central Electricity Authority (CEA), India GHG Program, IPCC. Estimates are for awareness, not audit-grade accounting._

## Tech

- **Single self-contained `index.html`** — vanilla HTML/CSS/JS, **zero dependencies, no build step**.
- **Hand-built SVG charts** (donut + trend line) — no chart library, so the live preview can't break.
- **localStorage** persistence — your data stays in your browser.
- Fully responsive, dark "instrument-panel" UI.

## Run locally

```bash
# just open the file — there's no build step
open index.html        # macOS
# or double-click index.html
```

---

_Made with curiosity for a lower-carbon life._
