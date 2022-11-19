# CustomerChurnPrediction

The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.
<img class="fit-picture"
     src="https://numlabs.com/static/img/posts-headers/customer_churn.JPG">
     
<p>I intend to solve this problem by the following steps:</p>
<ul>
  <li>Step 1: Test the hypothesis

The hypothesis can be tested by analysing the historical data about customers’ contracts.

Collect historical data about all customers’ contracts
Extract data on the customers who transferred to other providers

Identify whether customers churn and an increase in price happened at the same time

Prove the hypothesis

If the customer churn is along with an increase in price, we can conclude the growth in prices affects
customer churn. On the contrary, if customers transfer to another providers when there is no change or
even a decrease in price, we can say prices do not affect customer churn.</li>
  <li>Step 2: Build a model to predict customer churn
It is a binary classification problem. All customers are labelled with either 1 (switch to another provider) or O
(stay with the current provide). In order to build a powerful model to predict customer churn, lintend to
complete the following tasks:

Task 1: Collect data on all customers, including
+ contract data: starting time and ending time, price, discount, promotions, etc

+ customer information: name, country, city, profit, revenue, company size, industry, etc

+ energy usage: energy consumption amount

+ Iftransfer to other providers, this is the target label

Task 2: Understand and clean the data

Task 3: Exploratory data analysis

Discovering data patterns by data visualization

Task 4: Build a machine learning model and evaluate its performance

+ Train a model on the clean dataset got in task 2

+ Use cross-validation to evaluate the model performance

Task 5: Identify whether a discount on price can prevent customer churn

Apply 20% discount on the prices, then predict the customers’ labels again. Ifthe predicted labels (got in task
4) change from 1 to 0, this indicates the discount can stop customer churn. On the contrary, ifthe predicted
labels are still 1, this indicates the discount cannot stop customer churn.</li>
</ul>

