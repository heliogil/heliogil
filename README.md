# Hélio Gil

**Marketing analytics · CRO · Lifecycle & CRM** — a marketer who builds the data behind the decision.

B.A. + postgraduate degree in Marketing · MBA in Data (TripleTen, 2026) · Brazil, remote (UTC−3, overlaps with US hours) · English: conversational

I've run the business side (a construction company above R$25M in revenue) and now I work where marketing meets data:
which leads to call first, which test to run next, and what a conversion point is worth in money.

---

## Featured work

### 🎯 Bank Marketing — lead scoring for a term-deposit campaign
*MBA final project, in progress · Python, scikit-learn, SHAP · repo goes public after the review*

A bank called 41k clients to sell one product; 11% said yes. I'm building a model that ranks who to call first.

- **Baseline already beats the call list:** the top 20% of the ranked list converts at ~35% vs. 11% overall (≈3× lift), about −68% cost per acquisition at the same call budget.
- Caught a classic leak: call `duration` predicts the outcome but is only known *after* the call — dropped it, and measured what that costs in AUC.
- Ends in decisions, not metrics: an A/B test plan for the new call order, profit in currency, SHAP drivers per segment, and a per-client talking point for the SDR.

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

📫 heliogil@gmail.com · Open to remote roles in **Marketing Analytics, CRO, Lifecycle/CRM** and **SDR/BDR**.
