# JLR: The Business Case for Cyber Resilience

**Question:** If a cyber attack will eventually get through, where should a car maker spend its next pound to limit the damage?

This is an independent consulting-style case study of the 2025 cyber attack on Jaguar Land Rover (JLR). It uses public information only. It sets out what happened, what it cost, which ways of spending on resilience exist, and what a sensible, staged investment would look like.

> **Disclaimer.** This is an independent portfolio project built from public information. It is not affiliated with or endorsed by JLR or Tata Motors. All programme costs, probabilities, time savings, profit margins and insurance recovery rates are illustrative placeholders chosen for this exercise. They are not JLR figures and are not forecasts.

## Try it

**Interactive scenario explorer:** `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

Move the sliders for the chance of an attack, weeks of output lost, weeks a recovery plan saves, profit margin, insurance payout and programme cost. The page shows which option pays off best on those assumptions.

## The answer in brief

- **The length of the shutdown caused most of the loss.** In our estimate, about 74% of the attack-related loss came from the roughly five weeks when the factories were stopped. The plausible range is 61% to 86%.
- **Preparing to recover quickly scored best.** Four options were scored against six criteria. A recovery-led blend scored 3.65 out of 5, recovery first 3.45, insurance 3.10 and prevention first 2.65. The lead is narrow, and cost-focused weightings favour insurance.
- **On placeholder inputs, no option pays for itself in the central case.** The net expected benefit over three years is −£100m for prevention, −£39m for recovery, −£22m for insurance and −£69m for the blend. In a higher-risk case, recovery (+£72m) and the blend (+£75m) pay back.
- **Recommendation: spend in stages.** Approve only the first two phases (about £18m) now. Release later money only if practice runs show enough saved production time.

## What is in this repository

| Folder or file | What it contains |
| --- | --- |
| `index.html` | The interactive scenario explorer (served by GitHub Pages). |
| `deliverables/` | Source log, threat and regulatory brief, JLR profile and incident timeline, loss tree and recovery diagnostic, options analysis, financial model (Excel) with explainer, risk register, target resilience architecture, and roadmap with KPIs. |
| `summary/` | One-page visual summary (PNG and PDF). |
| `deck/` | Executive deck (10 slides). |

## How the work fits together

1. **Sources.** Every fact is traced to a public source in the source log.
2. **Threat and regulatory context.** Why attacks on UK manufacturers are rising and what rules apply.
3. **What happened at JLR.** Company profile and incident timeline, using JLR's Annual Report 2025/26.
4. **Where the loss came from.** A loss tree that separates the attack from problems that were already under way, and the full stop from the slow restart.
5. **The options.** Prevention first, recovery first, insurance and financing, and a recovery-led blend, scored with a weighted decision matrix and tested for sensitivity.
6. **The numbers.** An Excel expected-loss model with live formulas, break-even points and sensitivity tables.
7. **Risks, design and plan.** A 15-item risk register, a tiered recovery design, and a four-phase roadmap with checkpoints and KPIs.

## Main sources

- JLR Annual Report 2025/26 (sales, profit, net debt, the £260m one-off cyber cost, restart dates, liquidity and support facilities).
- Insurance Business UK, September 2026 (the absence of a cyber insurance policy at the time of the attack).
- NCSC Annual Review 2025 (nationally significant incidents rising from 89 to 204).
- Press coverage and company releases for quarterly volumes and the Cyber Monitoring Centre's cost estimate. The full list is in the source log.

## Limits of the analysis

- Public information cannot show JLR's real systems or controls.
- The split of loss between the full stop and the slow restart is our own estimate from annual report totals.
- Some figures, such as the Cyber Monitoring Centre estimate and second-quarter results, come from media reports and summaries.
- The insurance facts come from one trade article.
- Scores in the options analysis are judgements, not measurements.

## Tools used

Word and Excel for the written work and model, matplotlib for charts, and a single HTML page for the explorer.
