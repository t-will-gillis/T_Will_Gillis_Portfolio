# T_Will_Gillis_Portfolio
Portfolio

# Project 1: Date-A-Scientist

**Main goal:** Create machine learning models to make a prediction about OKCupid users. In the real world, the OKCupid app uses predictions like this to estimate compatibility among users and then suggest matches. The specific goal here is to compare and contrast the performance of supervised machine learning models to predict the religious preference of users based on other aspects of their profiles. A supplemental -learning- exercise is to see whether a natural language processing model can predict which user wrote a very brief essay. 

**Preprocessing:** Data preprocessed to select variables, remove null data, clean and sort, add dummy variables, and address label imbalance. Data split into train-test sets.

**Models:** SkLearn's Logistic Regression, K Neighbors Classifier, Decision Tree Classifier, and Random Forest Classifier. (And supplemental Natural Language with Bag of Words and Naive Bayes Classifier)

**Conclusion:** The Random Forest Classifier learning method performed best with a baseline score of 52%, which is somewhat successful and better than guessing (where 11% accuracy would be expected.) The model possibly could be refined for better accuracy, however there is a real concern of forcing/ overfitting the data. 

The Natural Language Processing learning exercise resulted in a model that made the correct prediction in average of 1.8/10 times, very slightly better performance compared to guessing (where 1/10 times is expected.) Note again that this was a learning exercise using available but not entirely adequate data, and as such this was successful.

- **Code:** Python, Jupyter Notebook
- **Packages:** pandas, numpy, matplolib, seaborn, sklearn 
- **Data Source:** Raw data for this project data provided by OKCupid app via Codecademy. 
