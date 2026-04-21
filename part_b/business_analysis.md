Part B: Business Case Analysis

Scenario: Promotion Effectiveness at a Fashion Retail Chain

A fashion retailer operates 50 stores across urban, semi-urban, and rural locations. Each month, the marketing team runs one of five promotions: Flat Discount, BOGO (Buy-One-Get-One), Free Gift with Purchase, Category-Specific Offer, and Loyalty Points Bonus. Stores vary in size, monthly footfall, local competition density, and customer demographics. The company wants to determine which promotion should be deployed in each store each month to maximise the number of items sold.

B1. Problem Formulation 

a) target variable - identify promotion offer to increase number of item sold/total sales should increase
   input variable - customer category,location,footfall,,existing sales,previous data of sold items base on each month promotion .value,discount etc etc
   ML Type - supervise multivariable classification because we want classify the promotion to deploy likeFlat Discount, BOGO (Buy-One-Get-One), Free Gift with Purchase, Category-Specific Offer, and Loyalty Points Bonus

b) As company focus on promotional offer like flat discount,BOGO,Free Gift with Purchase, Category-Specific Offer, and Loyalty Points Bonus .The first two lower the revenue w.r.t discount and items sold while rest offers will increase the footfall of high value customer .
company must work on principle to increase the value per item sold and maintain the footfall of all type of customer to increase the profitability of store. Final out come of any business depends on the revenue increase by minimizing loss or cost involved.

c) Once must choose different treatment of urban,semi-urban and rural location .Urban customer prefer speficic offer ,loyalty treatment,flat discount semi urban free gift with purchase,bogo where as rural location looks for flat discount and bogo .local competition density, and customer demographics varies locationwise .



B2. Data and EDA Strategy — 10 marks

a) transaction tables would have customer id, items sold,date,revenue,promotion offer,store details, 
store table would have location,items available,promotional offer with dates
promotion table would have discount and dates
calendar would have dates and promotion of day, month ,festival etc
one row must have - customer id, date,purchase details like category & number of items,location,promotionoffer,discount ,revenue

b) EDA would be on charts like - 
   box plot : promotional offer vs location wise purchase, 
   time series analysis : monthwise item sold with clear flagging of offer
   scatterplot - monthly footfall vs items sold
   heatmap - correlation between all variable

c) If 80 % of dataset has no promotion then model will also predict no promotion to offer.



B3. Model Evaluation and Deployment

a) not attempt...


   