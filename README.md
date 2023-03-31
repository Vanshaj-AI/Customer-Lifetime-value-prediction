# Customer-Lifetime-value-prediction
<h2>Description</h2>
Customer lifetime value (CLTV) is the total revenue a single customer can be estimated to make for a business throughout their business relationship. It's also possible to calculate CLTV just for a given time interval to gain  insights for a shorter term or quarterly/ annual business performance and prediction.
This project will help businesses in predicting Customer Lifetime value to segment customers and identify features of highly valuable customers to help businesses leverage insights to make cost-effective decisions,  allocate funds and implement strategies for marketing, customer acquisition, and profitability on products.
The dataset for this project is available on Kaggle, provided by Brazillian E-commerce company called Olist.

<h2>Terminology Alert!</h2>

- <b>Customer Acquition Cost</b> - Customer acquition cost refers to the estimated resources and cost a company needs to spend   on marketing and other methods to acquire an additional customer. The ratio between Customer Lifetime Value (CLV) and (CAC) is a metric used to measure th  effectiveness of a company's customer acquisition strategy. It helps to determine how much a customer is worth over the entire duration of their relationship with the company compared to how much it costs to acquire them in the first place.

- <b>(Note</b> - A high CLV:CAC ratio is typically indicative of a successful business. It suggests that the customer is likely to spend more money with the company over time than it costs to acquire them, which can lead to long-term profitability. Conversely, a ratio of 1:1 suggests that the business is struggling, and growth can only be achieved through significant investment, with little profit expected.)


- <b>Purchase Frequency</b> - is determined by calculating the proportion of the total number of orders placed by customers against the total number of customers.
- <b>Churn Rate</b> - It denotes the percentage of customers who have discontinued their association with the business.
- <b>Customer Lifespan</b> - It refers to the duration for which a customer has been consistently placing orders.
- <b>Repeat Rate</b> - is calculated by comparing the number of unique customers to the number of customers who have made more than one purchase.

<h2>Business Context where CLTV can be applied.</h2>

The business contexts on which CLTV may be applied my be classified based on 2 factors:

<b>1) Contractual vs Non-Contractual</b>

Depends on whether there is a predetermined contract perdiod before you use the product / service.

Examples for Contractual models:

- Club memberships
- Magazine subscriptions
- Credit cards
Example for Non-Contractualmodels:

- Grocery stores
- e-Commerce shopping like Amazon
- Doctor visits
If purchase is within a contract, the customer churn is explicitly known.

<b>2) Continuous vs Discrete Purchases</b>

Depends on whether the puchase happens contunuously or at specific times / opportunity. Purchases can be with or without a contract

Examples of continuous purchases:

- Grocery
- Book rentals
- Hospital visits

Examples of discrete purchases:

- Public Events
- Club memberships
- Insurance policies
- Mobile phone plans

<h2>Model Approaches for calculating CLTV.</h2>

There are various methods available for calculating Customer Lifetime Value (CLV).

1) The oldest and simplest method is to use historical data of customers to calculate the average revenue obtained from all customers. This provides a single value to denote the lifetime value, which can also be computed at an individual customer level.

2) An improved solution is to introduce cohorts and calculate the revenue for each cohort. However, a disadvantage of these methods is that they are unable to calculate the CLV for new customers.

3) A machine learning-based approach can solve this problem. Statistical models can be built with the help of available data, where recent six-month data can be used as independent variables and total revenue over three years as a dependent variable to build a regression model.

4) A probabilistic approach can also be used for calculating CLV. RFM (Recency, Frequency, Monetary) can be calculated from the available data, and this table can be used to extract CLV. Probabilistic models like BG/NBD and Gamma-Gamma can be used in this approach.

Customers can be grouped into segments based on the value to the business using algorithms like K-means. Specific promotions and discounts can then be provided to focus on high-value customer groups.

Overall, it is important to choose the most appropriate method for calculating CLV based on the available data and business needs to ensure that the results are accurate and useful for decision-making.



<h2>Languages and Modules Used</h2>

- <b>Pandas</b> 
- <b>NumPy</b>
- <b>Matplotlib</b> 
- <b>Seaborn</b> 
- <b>Plotly</b> 
- <b>Lifetime</b>
- <b>Datetime</b>

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>



<h2>Program walk-through:</h2>
<p align="center">
Launch the utility: <br/>
<img src="https://live.staticflickr.com/65535/52783488903_5d2930b6ec_k.jpg" height="80%" width="80%" alt="CLTV Steps"/>
<br />

<!--


<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
