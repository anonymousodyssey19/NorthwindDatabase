# Northwind Database Overview:

I was brought onto this project as a data scienctist to provide insights into a supply chain. Given that the project was very vague, I went on to perform statistical analysis on the supply chain's customers, suppliers, and overall efficiency.

# Findings:

### Hypothesis 1 of 4:

H0: Discounts do not have a statistically significant effect on the quantity of product ordered.

H1: Discounts DO have a statistically significant effect on the quantity of product ordered. 

#### Result: 
Reject the H0

#### Statistics: 

KS2 Statistic / P-Value (0.12 / 0.0476), Monte Carlo Method Means (Discounted: 27.1 / Non-Discounted: 21.71),  Cohen's D (8.91), Anova Method (P-Value: 5 Categories Under .001)

### Hypothesis 2 of 4:

H0: Discounts do not have a statistically significant effect on the avg revenue.

H1: Discounts DO have a statistically significant effect on the avg revenue.

#### Result: 
Accept the H0

#### Statistics: 
KS2 Statistic / P-Value (.033/.0063), Monte Carlo Method Means (Discounted: 52.59 / Non-Discounted: 52.32),  Cohen's D (.14)

### Hypothesis 3 of 4:


H0: Customers do not have a statistically signifigant bias towards purchasing discounted products.

H1: Customers DO have a statistically signifigant bias towards purchasing discounted products.

#### Result: 
Reject the H0

#### Statistics: 
KS Statistic / P-Value (0.52 / 0.0), Cohen's D (1.55)

### Hypothesis 4 of 4:
    
H0: The perfect order fulfillment is NOT at or above the acceptable standard of 90%.

H1: The perfect order fulfillment is at or above the acceptable standard of 90%.

#### Result: 
Reject the H0

#### Statistics: 
POF Index: 95%
