# Analysis-Quality-of-Meals-Restaurants-By-ML
## Overview:
#### The focus of this project was Supervised learning (Classification Algorithms) and Unsupervised Learning (K-Means Clustering) and Natural Language Processing.

### Problem description:
#### 1- How to deal correctly with Arabic texts.\n
#### 2- To build a system to classify the sentiments in arabic text based restaurant reviews  using machine learning.

## Datasets description: 
#### [RES1 DataSet](https://github.com/hadyelsahar/large-arabic-sentiment-analysis-resouces/tree/master/datasets)
######        Table 1: Describe columns by clarifying features and data type.

Features    |Data Type         |Description                    |
|:-----------|:----------------|:------------------------------|
|Polarity    |Integer          |which is a string value has two classes (-1: Negative & 1:Positive) indicating the sentiment around the review.|
|Text        |String           |is the review plain text of a restaurant in Arabic.|
|Restaurant_id |Integer        |the restaurant ID on the website.|
|User_id    |Integer           |the user ID on the website.|
 

### Phase 1: Natural Language Processing (NLP): Arabic text preprocessing
### Tools: 
> •	Nltk
•	arabic_reshaper
•	preprocessing
•	PIL
•	bidi.algorithm
•	arabic_reshaper
•	WordCloud 

### Phase 2: Supervised learning (Classification Algorithms). 
### Tools:
•	CountVectorizer
•	TfidfVectorizer
•	imblearn.over_sampling
•	naive_bayes
•	linear_model

### Phase 3: Unsupervised Learning (K-Means Clustering)
### Tools:
•	cluster
•	matplotlib.cm

### General Tools
•	Pandas
•	Numpy
•	matplotlib.pyplot.

### Technical Approach:
#### We are using python language in the implementations and Jupyter Notebook that support the machine learning and data science projects.








