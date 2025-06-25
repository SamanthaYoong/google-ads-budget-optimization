
## 1. 🌐 Objective / Problem Statement

**How can we optimize budget allocation across Google Search, Display, and YouTube to improve Return on Ad Spend (ROAS) for a fashion e-commerce campaign?**

The goal is to determine which ad channels are most effective in terms of performance (ROAS, CAC, Conversion Rate), and reallocate the marketing budget accordingly to maximize return.

🔗 [View the Interactive Tableau Dashboard](https://public.tableau.com/views/OptimizingBudgetAllocationAcrossGoogleAdsChannelsforFashionE-commerce/ExecutiveOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🖼️ Dashboard Preview

![Dashboard Preview](./Executive-overview.png)

---

## 2. 🌐 Business Context

- **Industry**: Online Fashion Retail (clothing and accessories)  
- **Target Market**: Southeast Asia, mobile-first shoppers  
- **Platform**: Google Ads (Search, Display, YouTube)  
- **Campaign Period**: 14 days (June 1–14, 2025)  
- **Budget**: ~$40,000 across all channels  
- **Funnel**: Impressions → Clicks → Conversions → Revenue  

---

## 3. 🌐 Data Used

**Source**: Mock performance data from Google Ads (June 1–14)  
**Dataset**: [GoogleAds_Mock_Campaign_ROAS.csv](GoogleAds_Mock_Campaign_ROAS.csv)
### Dimensions:
- Date
- Channel (Search, Display, YouTube)

### Metrics:
- Impressions  
- Clicks  
- Conversions  
- Ad Spend ($)  
- Revenue ($)

### Derived Metrics:
- **CTR** = Clicks / Impressions  
- **Conversion Rate** = Conversions / Clicks  
- **CAC** = Ad Spend / Conversions  
- **ROAS** = Revenue / Ad Spend  

---

## 4. 🌐 Metrics Breakdown (Aggregated Over 14 Days)

| Channel         | Total Spend | Revenue       | ROAS  | CAC   | CTR (%) | Conversion Rate (%) |
|----------------|-------------|---------------|-------|-------|---------|----------------------|
| Google Search   | $7,680.59   | $147,624.26    | 19.22 | $2.58 | 6.47    | 0.78             |
| Google Display  | $7,600.28   | $99,667.03    | 13.11 | $3.24 | 8.28    | 0.77                |
| YouTube Video   | $7,209.53   | $152,241.93    | 21.12 | $2.44 | 6.65   | 0.72               |

---

## 5. 🌐 Visual Analysis Summary

### A. ROAS by Channel
- **YouTube Video**: Highest ROAS at 21.1  
- **Google Search**: High ROAS at 19.2  
- **Google Display**: Lowest ROAS at 13.1  

### B. Cost Efficiency
- **Google Search**: Highest CR (0.8%), lowest CAC ($2.58) → most efficient channel 
- **YouTube Video**: High CR (0.7%), low CAC ($2.62), strongest ROAS (21.1) → strong post-click value
- **Google Display**: Highest CR (0.8%) but highest CAC at ($3.25) → cost doesn't justify return

### C. Impressions vs. Revenue
Despite low CTR, **YouTube** contributed strong revenue at lower costs, showing high post-click performance.  
**Google Display** had the highest CTR but lowest revenue, suggesting low purchase intent or poor audience alignment.

---

## 6. 🌐 Recommendations

### Budget Reallocation

| Channel         | Current % | Recommended % | Justification                          |
|----------------|------------|----------------|----------------------------------------|
| YouTube Video   | 33%       | 55%            | Highest revenue, strong ROI, scalable  |
| Google Search   | 33%       | 40%            | Most efficient (Highest CR, lowest CAC)
| Google Display  | 33%       | 10%            | Lowest ROAS and highest CAC            |

### Channel Optimization

- **YouTube**: Improve targeting/creative to boost CTR while maintaining strong CR  
- **Display**: Limit to retargeting or high-performing segments (e.g. region/device)  
- **Search**: Maintain keyword strategy, explore dayparting for added efficiency  

---

## 7. 🌐 Impact Forecast (If Recommendations Are Applied)

| Scenario         | ROAS | Revenue   | Spend   |
|------------------|------|-----------|---------|
| Current          | 18.9 | $538,000  | $28.5K  |
| Optimized Plan   | 22.5 | $641,000  | $28.5K  |

- **Revenue uplift**: ~20%  
- **Spend** remains constant  
- **Higher returns** driven by smarter allocation to high-ROAS channels  

---

## 8. 🌐 Lessons & Strategic Takeaways

- **ROAS ≠ CTR**: YouTube had poor CTR but excellent CR and ROAS — look beyond top-funnel metrics  
- **Segment by channel + device**: Test performance across mobile vs. desktop  
- **Optimize in short windows**: Performance improved over time — continuous tuning could yield higher ROI in longer campaigns  

---

## 9. 🌐 Appendices

- 📄 CSV Dataset: [GoogleAds_Mock_Campaign_ROAS.csv](GoogleAds_Mock_Campaign_ROAS.csv)
- 📊 Tableau Dashboard: [link_here](https://public.tableau.com/views/OptimizingBudgetAllocationAcrossGoogleAdsChannelsforFashionE-commerce/ExecutiveOverview?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)
- 📚 Metrics used: ROAS, CAC, CR, CTR, Revenue 
---

### 🌐 Contact / Notes

For insights, suggestions, or collaboration, feel free to open an issue!
