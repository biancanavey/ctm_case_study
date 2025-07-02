# Comparethemarket.com Personalisation Case Study

Leveraging customer behavioural data to drive personalised product recommendations and improve customer experience at Comparethemarket.com.

---

## Table of Contents

- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#assumptions-and-caveats)
- [Additional Notes](#additional-notes)

---

## Project Background

Comparethemarket.com is a leading price comparison platform, offering a wide range of products and services (e.g., insurance, energy, financial products). This project explores the use of customer data to deliver more personalised, relevant product recommendations, with the goal of increasing engagement and conversion rates.

**Objectives:**
- Demonstrate how customer data can identify high-potential customers and tailor product offers.
- Highlight how behavioural signals (e.g., prior interest, recency of engagement) improve recommendation effectiveness.
- Show how customer segmentation by demographics and behaviour can unlock new marketing opportunities.
- Present actionable insights to support data-driven marketing decisions.

**Stakeholders:**  
Marketing, Product, Data Science, and Customer Experience teams.

---

## Executive Summary

This analysis leverages a sample of 100,000 anonymised customer records to identify high-impact segments and optimise product recommendations. Key findings:

- **Overall purchase rate:** 30%
- **Prior interest:** Customers with prior interest are 2.77× more likely to purchase (177% uplift, p = 0.00001)
- **Top segments:**
  - Age 31–40: 36% conversion rate (CVR)
  - Segment A: 51% CVR
  - Recency-Active: 41% CVR

**Takeaway:** Prioritising behavioural signals and segment targeting can significantly boost conversion rates and customer satisfaction.

---

## Insights Deep-Dive

### Trend

- Purchase likelihood increases sharply with prior interest and recent engagement.
- Segment A and Recency-Active customers show the highest conversion rates (51% and 41% respectively).
- Overall purchase rate is steady at 30%, with notable peaks in key age and behavioural groups.

### Key Product Performance

- Products aligned with high-intent segments (Segment A, ages 31–50) outperform others.
- Segment C accounts for 51% of lost conversions, signalling an opportunity for improved targeting.

### Customer Growth and Repeat Purchase Trends

- Customers demonstrating prior interest are 177% more likely to purchase.
- Recency-Active customers are highly responsive to timely offers, suggesting strong retention potential.

---

## Recommendations

- **Amplify Prior Interest:** Deploy targeted ads and educational content to high-intent segments (Segment A, ages 31–50).
- **Optimise Segment Targeting:** Prioritise Recency-Active customers for time-sensitive offers and dynamic creatives.
- **Reduce Lost Conversions:** Implement dynamic, personalised creatives for Segment C to recover lost opportunities.
- **Leverage Surprise Wins:** Analyse unprompted purchases to uncover hidden motivators and refine recommendation logic.
- **Test and Validate:** Run A/B tests on Segment A and Recency-Active cohorts to validate uplift and refine strategies.

---

## Assumptions and Caveats

- **Data Limitations:** Dataset is anonymised and illustrative; may not reflect all real-world nuances.
- **Correlation ≠ Exclusivity:** Other factors (e.g., price sensitivity, external events) may influence results.
- **No Channel/Refund Data:** Platform/channel and refund rates not included, limiting some analyses.
- **Next Steps:** Validate findings with live data and expand to include additional product categories and engagement metrics.

---

## Additional Notes

**Supporting Files:**
- [Data Analysis Notebook (Python)](./notebooks/analysis.ipynb)
- [Presentation Slides](./presentation/comparethemarket_personalisation.pdf)
