# British Airways Analysis For Forage Using Python ✈✈

## Situation

In the repo there are  2 python notebook files. In one I was conducting a sentiment analysis on British Airways reviews, in another I was training a model to predict customer booking (If a customer was going to book or not). These poroject were given on the forage externship plaform. Understanding which customers are most lilely to book a flight and customers satisfcation is invaluable. Such information can be used to enhance marketing efforts, resource allocation, market sentiment, customer service, personalized offers and risk management. This will also increase customer retention and customer experience. 

## Task

The goal of this project is to build a model to predict customer booking to 60% and conduct sentiment analysis on historical data. This will enable the company to improve customer service and allocate resources to customers most likey to book. It will also improve marketing messaging and address customers pain points. 

## Action For Classification Model

- **Data Preparation and Cleaning**
  - Loading the data
  - Cleaning the data

- **Feature Engineering**
  - Label Encoding of categorical values
  - Dealing with imbalanced data using Synthetic Minority Over-smapling Technique (SMOTE)
  - Feature scaling using standardizaton
  - Selecting best feature by testing using Variance thresholding, SelectKbest, and extracting feature importance from Random Forest Classifier.

- **Machine Learning Operation**
  - Splitting the data into training data and test data. 
  - Training different model using the collection of features selected from each test.
  - Evaluating resulting results.


## Action For Sentiment Analysis
- **Data Preparation and Cleaning**
  - Loading the data
  - Cleaning the data
  - Text processing

- **Sentiment Analysis With NLTK**
  - Visualizing using Wordcloud
  - Visualizing sentiments using Barchart

- **Sentiment analysis using Textblob**
  - Visualizing sentiments using barchart. 


 ## Results 📜 

The model performs well overall, with an accuracy of 83% and fairly balanced metrics across both classes.
It is slightly better at detecting class 1 (recall = 0.92) but is less precise when predicting class 1 (precision = 0.78).
There is a trade-off between precision and recall, especially for class 0, where recall (0.75) lags compared to precision (0.91).

From the sentiment analyses I found that most reviews were positive than negative. 

> Check out the Pythont for full details 🙂

