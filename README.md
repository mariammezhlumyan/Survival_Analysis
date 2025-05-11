# CLV & Churn Risk Analysis (Telco Dataset)

This project uses survival analysis — specifically the LogNormal AFT model — to:
- Predict churn probabilities
- Estimate customer lifetime value (CLV)
- Identify at-risk customer segments
- Recommend retention budget and strategy

## Key Components
- **Model**: LogNormal AFT (chosen for best AIC score and interpretability)
- **Dataset**: Telco customers with features such as age, income, internet service, and churn
- **Outputs**:
  - Individual-level CLV estimates using predicted survival time
  - Visual analysis by age group, region, and customer type
  - Top 10 high-value customers identified
  - Boxplots and histograms to explore CLV distribution
  - Recommended retention budget based on value-at-risk

## Deliverables
- `report.md`: Full interpretation and strategy
- `CLV` column in data for targeted campaigns
- Visuals for segmentation and executive summary

## Tools Used
- `lifelines` (LogNormalAFTFitter)
- `matplotlib` & `seaborn` for visualization
- `scipy` for numerical integration (discounted CLV)

This project enables data-driven retention decisions, personalized targeting, and revenue-preserving strategies based on churn risk modeling.
