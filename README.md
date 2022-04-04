# t Will Gillis Portfolio
Portfolio

# Project 1: [Date-A-Scientist](https://github.com/t-will-gillis/portfolio-ok_cupid_date-a-scientist/blob/main/date-a-scientist.ipynb)

**Main goal:** Using Python and Jupyter Notebook: Create machine learning models to make a prediction about OKCupid users. In the real world, the OKCupid app uses predictions like this to estimate compatibility among users and then suggest matches. The specific goal here is to compare and contrast the performance of supervised machine learning models to predict the religious preference of users based on other aspects of their profiles. A supplemental- and learning only- exercise is to see whether a natural language processing model can predict which user wrote a very brief essay. 

**Preprocessing:** Data preprocessed to select variables, remove null data, clean and sort, add dummy variables, and address label imbalance. Data split into train-test sets.

**Models:** SkLearn's Logistic Regression, K Neighbors Classifier, Decision Tree Classifier, and Random Forest Classifier. (And supplemental Natural Language with Bag of Words and Naive Bayes Classifier)

**Conclusion:** The Random Forest Classifier learning method performs best of the four selected classifiers. It has a baseline accuracy score of 52%, which is somewhat successful and better than guessing (where 11% accuracy would be expected.) The model possibly can be refined for better accuracy, however there is a real concern of forcing/ overfitting the data. 

The Natural Language Processing learning exercise results in a model that makes the correct prediction an average of 1.8/10 times, very slightly better performance compared to guessing (where 1/10 times is expected.) Note again that this is a learning exercise using available but not entirely adequate data, and as such this exercise is considered successful. To train the model for more accurate results, the users' essays should be longer than the one or two sentences here. 

- **Code:** Python, Jupyter Notebook
- **Packages:** pandas, numpy, matplolib, seaborn, sklearn 
- **Data Source:** Raw data for this project data provided by OKCupid app via Codecademy. 


![](/images/confusion.png)
