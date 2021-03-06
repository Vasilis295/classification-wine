# classification-wine
>This Data set contains the information related red wine , Various factors affecting the quality. This data set was prepossessed and downloaded from the UCI Machine Learning Repository. This data set was simple, cleaned, practice data set for classification modelling. Source of this Dataset: https://archive.ics.uci.edu/ml/datasets/wine+quality

Attribute Information:
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
12 - quality ('good' and 'bad' based on score >5 and <5)


#### Sources
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

#### The project includes a readme note, a i.pynb file, powerpoint presentation slides in pdf form

### There are 4 mini classification projects based on this dataset. The first performs EDA and then classification with SVC model which reaches nearly 0.8 in accuracy, precison and recall. Then we go on and run some explainers like extra tree, shap and scatterplots and interpret the results in relation to which variables are the most important and to which direction.

### The second is classification notebook we run different algorithms and try to fine tune them(Random Forest,logistic regression, bagging classifier, xgboost classifier, SVC ). Of course we scale the data first. However, results fail to pass the 0.8 bar in all these algorithms.

### The third notebook, does something similar but uses the pipeline technique to claculate algorithms and results of course are similar.

### Finally in the last notebooke we have the effort to predict wine quality with the help of simple neural neatworks. We play a bit with our model,however we see again that although the training model reaches 0.94 in accuracy, the test or validation reaches only 0.76 - 0.77.

### The 0.8 max score however is not bad, as the good and bad quality are separated by only one level in the scale of 10(up to 5 is bad and form 6 is considered good.So, in the range 4-7 it is expected that results cannot be predicted easily.

### Nevertheless, we show we can deal with classification models from the beginning to the end and with a variety of ways.


