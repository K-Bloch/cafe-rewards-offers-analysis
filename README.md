# Cafe Rewards Program: Interaction Patterns and Completion Rates

All technical steps and visualizations are documented in the accompanying [Jupyter Notebook](notebooks/cafe-rewards-program-interaction-patterns-and-completion-rates-final.ipynb).

## Project Background

Beanie Coffee is a popular coffee shop chain that runs a loyalty program called **Cafe Rewards**, offering members (registered customers) access to exclusive offers. These offers fall into three types:
- **BOGO**: Buy one, get one free.
- **Discount**: Direct monetary discounts on purchases.
- **Informational**: No direct rewards, just product or promotional information.

The data from a recent 30-day campaign is now ready for analysis. Executives have requested a review on the following areas:
- **Completion Rates**: How many reward offers were completed, and which ones had the highest completion rates?
- **Customer Demographics**: What are the key demographic patterns, especially regarding offer completion?

## Executive Summary

Key findings include:
- A campaign-wide completion rate of ~63%.
- Informational offers showed both extreme successes (93% completion for one campaign) and weaknesses (50% completion for another).
- The success of informational offers suggests significant customer interest, but the lack of transaction-level data makes it difficult to gauge their true impact.
- Demographic trends reveal younger customers are least engaged overall, while older customers show high engagement with discount and BOGO offers.
- Older customers are consistently more engaged across most offer types.
- Younger customers engage more with informational offers but represent the smallest proportion of customers.


### Completion Rates

- **Total Interactions**: 66,496 offers were received, and 41,567 were completed (~63% completion rate).
- **Informational Offers**:
  - Informational_2 excelled with a 93% completion rate.
  - Informational_1 performed poorly, with a 50% completion rate.
  - Informational offers have a short 3-day window for completion, therefore their long-term impact on purchases can't be reliably measured. Customers may interact with these campaigns beyond the 3-day window.
- **Discount Offers**: 
  - Discount_3 achieved the highest success at 75% completion.
  - Discount_1 was weaker at 49%.
- **BOGO Offers**:
  - These had the overall lowest completion rate (57%), with Bogo_2 standing out as particularly weak (50%).

### Customer Demographics

1. **BOGO Offers**:
   - Weakest engagement in the 18–34 age group.
   - Best performance with customers aged 55–64.
   - Most completions came from the 45–54 age group.
2. **Discount Offers**:
   - Lowest engagement from customers aged 34 and younger.
   - High and consistent redemption rates from customers aged 45 and older.
3. **Informational Offers**:
   - Highest completion rates in customers aged 18–34.
   - The 45–54 age group were the biggest group who interacted with this offer.

---

## Recommendations

1. **Informational Offers**:
   - Consider capturing transaction-level data to verify their true impact.
   - Investigate why Informational_2 was so successful and replicate its elements in future campaigns.

2. **BOGO Offers**:
   - Reassess the products included in these campaigns. They may not align with customer preferences.
   - Test alternative product selections or incentives on a small scale, borrowing successful elements from discount and informational campaigns.
   - Examine other factors such as redemption time limits, minimum spend thresholds, and marketing channels.

3. **Demographics**:
   - Increase outreach to the 18–34 demographic, who represent the smallest customer base but are responsive to informational offers.
   - Incorporate products and patterns from successful informational campaigns into BOGO and discount offers.
   - Explore whether income levels or other demographic traits influence engagement and how.
     

