
Customer is the key to the survival of any business as there is no business without a customer. So all the business of today aim to know about the
preferences, likes and dislikes of the customer so as to enhance the customer behaviour. Predicting Customer Behavior is made possible through 
market basket analysis.

# market basket analysis
Market basket analysis is a data mining technique used by retailers to increase sales by better understanding customer purchasing patterns. 
It involves analyzing large data sets, such as purchase history, to reveal product groupings, as well as products that are likely to be purchased
together.

# Three things to remember: Support, Confidence, Lift
Rule(X, Y)

#Support  
Support measures how frequently an association rule happens in a dataset.
In N transactions what is the probability of purchasing both the items = Frequency(X,Y) / N

#Confidence  
Confidence measures how strong an association rule is.
When X has happened, what is the likilehood for Y to happen = Frequency(X, Y) / Frequency(X)
For instance , what is the likelihood that customer to buy a mouse along with a laptop, buy a glass of wine or ginger garlic paste with a pack of chicken.

#Lift 
Lift is the ratio between target response and average response. 
As Lift is a ratio, it can have a value greater or below 1, depending on whether the model performs better than the average at predicting the outcome. 
As a result:

If Lift is greater than 1, it means that the target response is more likely than the average response. Therefore, the association rule improves the 
chances of the outcome. This gives the opportunity for cross - selling and reducing the customer churn.

If Lift is below 1, the target response is less likely than the average response. As a result, the association rule lessens the chances of the 
desired outcome.

A lift of 1 means that the model (or association rule) does not affect the outcome.

reference : https://techbusinessguide.com/what-is-lift-in-market-basket-analysis/

