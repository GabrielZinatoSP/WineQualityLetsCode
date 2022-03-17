# Statistics and Machine Learning - Wine Quality Prediction 
(Data Science Degree - [Let's Code](https://letscode.com.br/))

## The goal of this project from the Statistics module of the Data Science course I'm currently undergoing was to compare the performances of a Linear Regression and a Logistic Regression when applied to physicochemical data on wine in an attempt to predict the quality of the wine. In the end, the Logistic Regression had a much better performance due to some characteristics of the dataset and the nature of the problem itself (A classification problem). 

- [Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

- [Notebook](https://github.com/GabrielZinatoSP/WineQualityLetsCode/blob/main/Linear%20and%20Logistic%20Regression%20-%20Red%20Wines%20and%20White%20Wines.ipynb)

## Data Set Information:

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: [Vinho Verde](http://www.vinhoverde.pt/en/) or the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

## Attribute Information:

Input variables (based on physicochemical tests):

    1 - fixed acidity
    2 - volatile acidity
    3 - citric acid
    4 - residual sugar
    5 - chlorides
    6 - free sulfur dioxide
    7 - total sulfur dioxide
    8 - density
    9 - pH
    10 - sulphates
    11 - alcohol

Output variable (based on sensory data):

    12 - quality (score between 0 and 10)


