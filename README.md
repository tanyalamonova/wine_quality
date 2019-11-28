# Wine quality

This project is made to predict wine quality based on different characteristics. I used [Wine quality data set](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) to train classifiers.\
The code is on Python3, I used sklearn to train models, predict quality and show metrics in order to compare the results. Confusion matrixes and feature importances graphes are shown using matplotlib.\
I show each classifier's metrics: accuracy score and confusion matrix that allow us to see which model performed better.\
*All the findings and conclusions are at the end of the notebook.*

### Classifiers used in this project:
* Support Vector classifier
* Naive Bayes
* Decision Tree (that performed better than the previous two and proved that using ensemble methods makes sense here)
* Random Forest
* Ada boost
* Extra Trees

### Directions on how to run the code:
* open the notebook
* run this giant first cell in order to make all imports and prep methods (comments are attached there)
* run two other cells. Each one trains clasifiers based on either red or white wine data set. The results (metrics, feature importances and accuracy score comparison) will be shown immediately.
* that's it!
* *P.S. Jupyter notebooks are so good that you don't even have to run the code to see the results based on my data sets, just open the notebook and watch* 
