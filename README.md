# battery-degradation-anomaly-and-prediction
- When a factory makes EV batteries, every cell comes out slightly different. 
 Most are fine, but a few are secretly defective: they look normal on day one and then degrade fast after a few hundred charge/discharge cycles.
- Right now, the only sure way to find out whether a cell is good is to cycle it 200+ times and watch what happens. 
 That takes weeks or months, costs a lot of electricity and test-rig time, and it’s impractical to do for every cell.
 If a bad cell slips into a battery pack, the whole pack can underperform or become a safety risk.

 **Use only the first few cycles of test data (days of testing, not months) to answer two questions:**
- Which cells look abnormal compared to the rest of their batch ? (anomaly detection) -> Classification
- What would be the value of a certain parameter for each cell at cycle 200? (prediction) -> Regression

#### Methods we use for Classification
- Z-score method
- Mahalanobis Distance method
- Isolation Forest method
we also rank the cells on their tendency to be an anomaly for each method

 #### Methods we use for Classification
- 

 **We also make assumptions about the cycle 200 testing using readings upto cycle 100 to understand the accuracy of our method**

 ## Things to work on:
 - using real world data 
