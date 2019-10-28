Women’s E-Commerce Clothing Reviews dataset includes 23486 rows and 10 feature variables. 
Each row corresponds to a customer review, and includes the variables:

•	Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed. 

•	Age: Positive Integer variable of the reviewers’ age.

•	Title: String variable for the title of the review.

•	Review Text: String variable for the review body. 

•	Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best. 

•	Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended. 

•	Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.

•	Division Name: Categorical name of the product high level division.

•	Department Name: Categorical name of the product department name.

•	Class Name: Categorical name of the product class name.

The key aspect of this sentiment analysis is to analyze the body of “Review Text” for understanding the opinion expressed by it. 
These sentiments were quantified with a positive or negative value, called polarity. 
The overall sentiment is often inferred as positive, neutral or negative from the sign of the polarity score.

“Review Text” data were preprocessed and tokenized. 
Each preprocessed “Review Text” is indicated as “Positive”, “Negative” and “Neutral”. 

A recurrent neural network (RNN) and a simple embedding deep neural network were implemented for sentiment classification.
RNN reached an accuracy of 90% for sentiment classification.
Simple embedding deep neural network reached an accuracy of 88% for sentiment classification.
RNN was effective at predicting sentiment than simple embedding deep neural network.


