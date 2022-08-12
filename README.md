# t Will Gillis Portfolio
Portfolio

### Python Developer Projects:
- [Project 1: Date-A-Scientist](#project-1-date-a-scientist)
- [Project 2: Orion Constellation](#project-2-orion-constellation-and-supplement)
- [Project 3: Life Expectancy vs GDP](#project-3-life-expectancy-vs-gdp)

### Software Developer Projects:
- [Project 4: Mobile App](#project-4-mobile-app)
- [Project 5: Appointment Maker](#project-5-appointment-maker)
- [Project 6: Loteria](#project-6-loteria-game)


# Project 1: [Date-A-Scientist](https://github.com/t-will-gillis/portfolio-ok_cupid_date-a-scientist/blob/main/date-a-scientist.ipynb) 
#### Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Sklearn

**Main goal:** Using Python and Jupyter Notebook: Create machine learning models to make a prediction about OKCupid users. In the real world, the OKCupid app uses predictions like this to estimate compatibility among users and then suggest matches. The specific goal here is to compare and contrast the performance of supervised machine learning models to predict the religious preference of users based on other aspects of their profiles. A supplemental- and learning only- exercise is to see whether a natural language processing model can predict which user wrote a very brief essay. 

**Preprocessing:** Data preprocessed to select variables, remove null data, clean and sort, add dummy variables, and address label imbalance. Data split into train-test sets.

**Modules:** SkLearn's Logistic Regression, K Neighbors Classifier, Decision Tree Classifier, and Random Forest Classifier. (And supplemental Natural Language with Bag of Words and Naive Bayes Classifier)

**Conclusion:** The Random Forest Classifier learning method performs best of the four selected classifiers. It has a baseline accuracy score of 52%, which is somewhat successful and better than guessing (where 11% accuracy would be expected.) The model possibly can be refined for better accuracy, however there is a real concern of forcing/ overfitting the data. 

The Natural Language Processing learning exercise results in a model that makes the correct prediction an average of 1.8/10 times, very slightly better performance compared to guessing (where 1/10 times is expected.) Note again that this is a learning exercise using available but not entirely adequate data, and as such this exercise is considered successful. To train the model for more accurate results, the users' essays should be longer than the one or two sentences here. 

- **Code:** Python, Jupyter Notebook
- **Packages:** Pandas, NumPy, Matplolib, Seaborn, Sklearn (Logistic Regression, K Neighbors, Decision Tree, Random Forest, Naive Bayes)
- **Data Source:** Raw data for this project data provided by OKCupid app via Codecademy. 


![](/images/confusion.png)



# Project 2: [Orion Constellation](https://github.com/t-will-gillis/orion_constellation/blob/main/constellation.ipynb) and [Supplement](https://github.com/t-will-gillis/orion_constellation/blob/main/supplemental.ipynb)
#### Python, Jupyter Notebook, Excel, Matplotlib, Axes3D

**Main goal:** Using Python and Jupyter Notebook to create a 3-dimensional representation of the principal stars in the Orion constellation. By importing matploblib and especially the Axes3D module, the goal is to make an accurate IRW representation of the stars. The star data from the first project comes from Codecademy. The star data from the second Supplement is open-sourced from the internet for astronomical coordinates and distances, and then converted using an Excel file/ .csv to generate a new set of (x,y,z) coordinates to use for plotting. The Supplement file can thus be used to generate a 3-D representation of any group of stars given sky coordinates and distances. The format of the first project comes from Codecademy, but with edits to the data for an improved presentation.

**Preprocessing:** Preprocessing primarily applies to the Supplement. As noted above, astronomical data i.e. right ascension, declination, and distance measurements were open-sourced from the internet and then were processed by a custom-written Excel program to generate the correct (x,y,z) coordinates for display by Axes3D. This custom program can then be extended for use on any set of stars given the initial astronomical coordinates.

**Modules:** The primary modules used are matplotlib and Axes3D.

**Conclusions:** With Axes3D and the custom processing program, any group of stars can be shown in a true orientation that demonstrates the actual relationship among the sample of stars. For examples, the four primary stars of Betelgeuse, Bellatrix, Rigel, and Saiph are all visualized to be much closer to earth than the belt and other stars. Effective visualization is crucial for data analysts and scientists.

- **Code:** Python, Jupyter Notebook, Excel
- **Packages:** Matplotlib, Axes3D, Pandas, Numpy
- **Data Source:** Raw data for this project data provided by Codecademy, and additional data researched and open-sourced from the internet. 

![](/images/orion_3-dr.png)


# Project 3: [Life Expectancy vs GDP](https://github.com/t-will-gillis/gdp_and_life_expectancy/blob/main/life_expectancy_gdp.ipynb) 
#### Jupyter Notebook, Python, Excel, Matplotlib

**Main goal:** Use Python and Jupyter Notebook to explore relationship between Life Expectancy and GDP for six representative countries over 15 years.

**Preprocessing:** The provided data did not include population, therefore population data for the relevant countries/ years were downloaded from UN data via the internet, imported and processed in Microsoft Excel, and then imported into Pandas.

**Conclusions:** Adjusting GDP for population (i.e. per capita) shows Mexico performing better than China in life expectancy, and Germany with a near equivalent per capita GDP but longer life expectancy than the US. Chile is outperforming all countries on life expectancy to per capita GDP, which would seem to say that maximizing GDP does not automatically maximize life expectancy.

- **Code:** Python, Jupyter Notebook, Excel
- **Packages:** Matplotlib, Pandas, NumPy, Seaborn
- **Data Source:** Raw data for this project data provided by Codecademy, with additional data researched and downloaded from UN via the internet. 

![](/images/life-gdp_pc_per_country_per_year.png)


# Project 4: [Mobile App](https://github.com/t-will-gillis/CBDB)
#### HTML, CSS, JavaScript, jQuery Mobile, MongoDB, Monaca Mobile App Platform

**Description:** Mobile application, here specifically a 'Comic Book Data Base.' The link is to the index.html, stylesheet.css, main.js files, as well as to the Android APK. The app features a user registration and login with strong password checking, forms for entering collection data, saving data using MongoDB nonrelational database management system, data edit and retrieval, and logout. 

The app is written within the Monaca Platform using jQuery Mobile JavaScript framework and can be deployed for Android, Apple, Microsoft, or as a Progressive Web App.

- **Code:** HTML, CSS, JavaScript, jQuery Mobile, MongoDB
- **Packages/ Platforms:** Monaca Mobile App Development Platform

![](/images/Screenshots.png)


# Project 5: [Appointment Maker](https://t-will-gillis.github.io/appointment_maker_v5/)
#### ReactJS, NodeJS, JavaScript, HTML/CSS

**Description:** Appointment maker app. [Link to code](https://github.com/t-will-gillis/appointment_maker_v5_code)

- **Code:** ReactJS, Javascript, HTML/CSS
- **Packages/ Platforms:** React-Router-DOM, NodeJS

![](/images/appointment_screenshot.png)


# Project 6: [Loteria Game](https://github.com/t-will-gillis/loteria-game)
#### HTML, JavaScript, Phaser3

**Description:** This is a link to a zip file for a simple Phaser3 game of Loteria, with code built from the base file phaser3-parcel-template framework from Ourcade/supertommy. 

- **Code:** HTML, JavaScript
- **Packages:** Phaser3 and phaser3-parcel-template
- **Sources:** [Phaser3](https://www.phaser.io) and [Phaser3 Parcel Template](https://github.com/ourcade/phaser3-parcel-template) via Ourcade, supertommy 

![](/images/loteria_screenshot.png)

