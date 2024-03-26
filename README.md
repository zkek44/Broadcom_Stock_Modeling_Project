# Broadcom_Stock_Modeling_Project
Objective: The project aimed to predict Broadcom's daily closing stock prices using the daily closing stock prices of other major companies in the Information Technology sector, spanning from 4/1/2021 to 3/31/2022.

Data Source: Daily closing stock prices of Broadcom and various Information Technology companies, including Hewlett-Packard, Microchip, Qualcomm, Cisco, and Texas Instruments, among others, were utilized for this period.

Methodology: A comprehensive stepwise regression analysis was conducted with 73 independent variables to narrow down the variables influencing Broadcom's stock prices.
Variables were selected based on the stepwise regression outcome, high variance inflation factor (VIF) analysis, and individual t-test p-values, resulting in a refined model with fewer variables.
Interaction and second-order terms were tested to improve model accuracy, with a final model chosen based on the adjusted R-squared value, F-statistic, and other selection criteria.

Key Findings: The final regression model included significant variables and a second-order term that effectively predicted Broadcom's stock prices.
The adjusted R-squared value of 0.9697 indicated that approximately 96.97% of the variability in Broadcom's daily closing stock prices was explained by the model.
The analysis underscored the interrelated nature of stock prices within the IT sector, showcasing the impact of competitors and collaborators on Broadcom's stock performance.

Challenges: The project encountered challenges in model selection, particularly in identifying and testing interaction and second-order terms that could accurately capture the complexities of stock price determinants.

Learnings: The importance of a meticulous approach to variable selection in regression analysis was highlighted, demonstrating the value of stepwise regression and VIF analysis in simplifying complex models.
The project reinforced the necessity of iterative testing and refinement in developing accurate predictive models.

Future Work: Recommendations for future analysis include exploring additional interaction and second-order terms, considering higher-order polynomial terms, and extending the analysis across multiple years for a more robust model.
