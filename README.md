
## Fisher’s Iris data set
![Iris Flower, source:https://thegoodpython.com/iris-dataset/](https://github.com/G00387867/pands-project/blob/master/iris_snipp_it.PNG "Iris Flower, source:https://thegoodpython.com/iris-dataset/")

### _Introduction_

The data set contains a set of 150 records under five attributes - petal length, petal width, sepal length, sepal width and species.
The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: **_the length and the width of the sepals and petals_**, in **centimeters**. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other[1].

The aim for this project is to analyse the Fisher's Iris flower data set using python as a coding and scripting language.

### _Methodology_

* Downloading iris data set from (http://archive.ics.uci.edu/ml/datasets/iris) and saving it to this repository [2]
* Assigning columns to raw data with each variable attribute: petal length, petal width, sepal length, sepal width and type
* showing a summary of the dataset by highlighting main data points
* Analysing the data by creating a histogram of each variable and text file summary of the statistical specification of the variable.
* Creating a pair plot(s) showing the correlation between the different variable categories.


### _Analysis_

>#### Summary of the data set
`summary = df.describe()`

`summary = summary.transpose()`

`summary = summary.head()`


 |    Type      |count | mean      |      std|  min | 25%   |50% | 75%   |max|
 |------------| --------| --------| -----------|-----|------|----|-----|-----|
| sepal_length |  150.0|  5.843333 | 0.828066 | 4.3|  5.1 | 5.80 | 6.4|  7.9|
| sepal_width |   150.0 | 3.054000 | 0.433594 | 2.0 | 2.8 | 3.00 | 3.3 | 4.4|
| petal_length |  150.0 | 3.758667 | 1.764420 | 1.0|  1.6 | 4.35 | 5.1 | 6.9|
|petal_width |   150.0 | 1.198667 | 0.763161 | 0.1 | 0.3 | 1.30 | 1.8 | 2.5|
--------------------------------

>#### _Pairplot_ using SEABORN 

![Pairplot](https://github.com/G00387867/pands-project/blob/master/Pair_Scatter.png "Pairplot")

>#### Petal Length vs Petal Width

![Petal length vs Petal width](https://github.com/G00387867/pands-project/blob/master/Petal_Length_vs_Petal_width.png "Petal length vs Petal width")

>#### Sepal Length vs Sepal Width

![Sepal Length vs Sepal Width](https://github.com/G00387867/pands-project/blob/master/Sepal_Length_vs_Sepal_width.png "Sepal Length vs Sepal Width")

### _[References]_

[1] Wikipedia: https://en.wikipedia.org/wiki/Iris_flower_data_set

[2] http://archive.ics.uci.edu/ml/datasets/iris

[3] https://www.learnbay.co/data-science-course/blog-post/exploratory-data-analysis-on-iris-dataset/

[4] https://pythonbasics.org/seaborn-pairplot/

