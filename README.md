# Manufacturing-Downtime
### 🚀 Overview
This project is a Manufacturing Downtime Analysis designed to visualize and analyze manufacturing or operational efficiency data. Its purpose is to clearly identify, quantify, and assign the root causes of operational inefficiency. The analysis focuses on performance variations by operator and the most frequent downtime factors, leading directly to targeted, actionable recommendations. 

### 📊 Key Findings & Data Insights
The overall line efficiency currently sits at 64%. The analysis highlights specific areas for improvement:

1. Operator Efficiency
The primary efficiency metric is broken down by operator:

- Charlie: 67%
- Dee: 64%
- Dennis: 63%
- Mac: 61% (Lowest efficiency)
Conclusion: We should place special focus on Mac to raise the overall line performance.

2. Dominant Downtime Factors (Pareto Analysis)
The Pareto Chart shows that the top 5 factors account for 80% of the total downtime. Our focus should be exclusively on these five:

> Machine adjustment (Highest total downtime: 332 units)
> Machine failure
> Inventory shortage
> Batch change
> Batch coding error

3. Operator Accountability for Key Downtime Factors
   
A crucial part of this analysis is linking the top 5 downtime causes to the operators who experienced them most often. 
This table reveals that the 3 most significant factors are primarily due to operator error or interaction:
Factor,Charlie,Dee,Dennis,Mac,Key Insight
Machine adjustment,118,79,120,-,Dennis and Charlie contribute most to this issue.
Batch change,-,-,-,130,Mac is solely responsible for this issue.
Inventory shortage,-,85,-,80,Shared issue between Dee and Mac.

Conclusion: We should focus on Machine adjustment training for everyone and specific Batch change training for Mac, as his performance in this area is a unique and significant bottleneck.

##### ✅ Recommendations
Based on the data and operator accountability, the following targeted actions are required:

1. Start with Machine adjustment training for all operators. (Addresses the top overall downtime factor, especially high for Dennis and Charlie).
2. Provide special batch change training for Mac. (Addresses Mac's unique and severe bottleneck in Batch change downtime).
3. Apply preventive maintenance to the machine and double check inventory levels. (Addresses the top two non-operator-specific issues: Machine failure and Inventory Shortage).

   
