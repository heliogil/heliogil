# Hélio Gil

**Management · Marketing · Data with AI** — a marketer who builds the data behind the decision.

B.A. in Advertising · MBA in Data Science & AI (TripleTen, 2026) · Brasília, Brazil (UTC−3, overlaps with US hours) · English: fluent

I've run the business side (founded and managed companies for over a decade) and now I work where marketing meets data:
which leads to call first, which test to run next, and what a conversion point is worth in money.

---

## Featured work

### 🔥 Wildfire risk by municipality and day — [repo](https://github.com/heliogil/risco-incendio-municipio)
*MBA final project, approved · Python, scikit-learn, SHAP · data from INPE, MapBiomas and INMET*

Predicts fire risk (Low / Medium / High) for each municipality and day, using only information available the day before.

- Logistic regression on 8.2M fire hotspots plus land cover and weather.
- **Beats the "today = yesterday" baseline:** macro F1 0.571 vs 0.549, and High-alert precision 57.6 vs 49.2 per 100 alerts. Estimated cost in the test period: R$420.1M vs R$434.8M.
- Delivered explainability (SHAP), bias tests, hyperparameter tuning and an A/B test plan.
- Declared the goal it did not reach: High-risk days warned, 51.2 vs the 60 target per 100.

### 🖥️ Rei do FPS — [reidofps.com.br](https://reidofps.com.br)
*Product I designed and launched · SEO + affiliate model · [repo](https://github.com/heliogil/fpsreal)*

Brazil's PC-build comparator ranked by **cost per FPS** instead of specs.

- Positioning and brand (name, mascot, "we estimate FPS, we never fake it" as a trust promise).
- Data product: catalog of real parts, 600+ FPS estimates with confidence bands, compatibility rules, affiliate click tracking.
- Built so content comes from the data (price anomalies → posts), which is the growth loop.

### 📊 Marketing data projects (MBA)
Business questions, each answered in money or a decision:

| Question | Method |
|---|---|
| Which games should a store push in next year's campaign? | Market & platform analysis, hypothesis tests |
| Which bank clients are about to churn? | Imbalanced classification, F1/AUC |
| Which phone plan should we recommend to each user? | Classification on usage behavior |
| Which region gives the best return with the lowest loss risk? | Bootstrap profit & risk |
| Do weather and day of week change taxi demand? | SQL + hypothesis testing |
| Live dashboard of used-car listings | Streamlit · [app](https://tripleten-4evz.onrender.com/) · [repo](https://github.com/heliogil/Tripleten) |

### 🔎 Intent-signal lead scoring — [showcase](https://github.com/heliogil/demand-scanner-showcase)
Scans 8 public sources for buying signals, scores each lead 1–10 on fit, budget and urgency, and drafts the first message for a human to approve.
The SDR workflow, automated up to the point where judgment matters.

---

## How I work

- **Money, not metrics.** Every model ends in "what this saves or earns", not just AUC.
- **Test before you scale.** Kill criteria written before the first experiment ([how I run experiments](https://github.com/heliogil/venture-studio-os)).
- **AI as the team.** I direct AI agents to build, analyze and produce content — I read, review and decide.

**Toolkit:** SQL · Python (pandas, scikit-learn, SHAP) · A/B testing & hypothesis tests · Plotly/Streamlit dashboards · funnel & cohort analysis · AI agents for automation

---

📫 heliogil@gmail.com
