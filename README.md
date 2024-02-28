The project is about the critical issue of fake news prediction. The spread of false or misleading 
information has become a significant problem, as it can deceive public opinion, disrupt trust in 
reliable sources, and even provoke social and political instability. It is required to address this 
problem through the development of precise predictive models to identify and battle fake news.

Defining the ML problem:
Task(T): Classify the news as “Fake” or “Not Fake”.
Experience(E): Labeled dataset of news articles with indications of whether they are fake or not. 
This dataset will be used to train and evaluate the model.
Performance measure(P): Accuracy will be used to assess how well the model is able to correctly 
classify news articles.

Data:
a) Data is from: https://www.kaggle.com/c/fake-news/data?select=train.csv
b) Features which are entering to the algorithm: Title, Author 
c) Number of examples in the data set: 20800
d) Possible methods of handling missing data: It will be used null strings for the missing 
values. Ultimately, null values will be replaced by using empty string.

Algorithm: 
a) We will use following algorithms;
I. Logistic Regression
II. Decision Trees
b) Are the algorithms available off the shelf from the libraries? Yes
