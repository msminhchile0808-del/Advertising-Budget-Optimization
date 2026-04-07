# Advertising-Budget-Optimization
Robert Morris University - Intro to Data Analytics

This memo outlines the findings and recommendations from our advertising budget optimization analysis. The objective was to strategically allocate a total budget of $10,000 across three advertising channels—Online Ads, TV Ads, and Print Ads—to maximize the combined reach and impact, while adhering to specific cost, reach, and impact parameters for each channel, and ensuring at least one unit of each channel is purchased to maintain distributor contracts.

**Analysis Overview:**

We utilized a linear programming model to identify the most efficient allocation of the budget. The model considered the following:

*   **Total Budget:** $10,000
*   **Channel Parameters (per unit):**
    *   **Online Ads:** Cost: $50, Reach: 1,000, Impact: 2
    *   **TV Ads:** Cost: $200, Reach: 5,000, Impact: 5
    *   **Print Ads:** Cost: $100, Reach: 3,000, Impact: 3
*   **Constraints:**
    *   Total expenditure must not exceed the budget.
    *   At least one unit of each channel must be purchased.
    *   Units must be integer values (no partial units).

**Optimal Solution:**

Based on the optimization model, the following allocation is recommended:

*   **Online Ads:** 2 units
*   **TV Ads:** 49 units
*   **Print Ads:** 1 unit

**Results:**

This allocation yields an **Overall Reach x Impact score of 1,238,000**, representing the maximum possible value given the defined constraints and parameters.

**Expenditure Breakdown:**

*   Online Ads: 2 units * $50/unit = $100
*   TV Ads: 49 units * $200/unit = $9,800
*   Print Ads: 1 unit * $100/unit = $100
*   **Total Expenditure: $100 + $9,800 + $100 = $10,000**

**Conclusion:**

The optimization model suggests that TV Ads are the most impactful channel for maximizing reach and impact within the given budget, leading to a significant allocation towards this channel, while ensuring contractual obligations for all channels are met. This allocation fully utilizes the available budget to achieve the highest possible combined reach and impact.

**Recommendation:**

We recommend proceeding with the outlined advertising budget allocation to achieve the highest possible return in terms of reach and impact from the $10,000 budget.
