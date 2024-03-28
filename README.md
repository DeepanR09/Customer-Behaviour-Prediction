For predicting customer behaviour, predictive modeling and exploratory data analysis was performed.

Packages used: pandas,sklearn (scikit-learn), matplotlib and numpy

Algorithm used: Random Forest Classificaton (XBG Classifier is another alternative)

Procedure:

1.Dataset is imported 
2.Unique attribute is days ,so they are mapped 
3.Statistical and arithmetic methods are performed for all attributes with respect to instances
4.All the attributes data types are converted into int64 (few were objects earlier)
5.Mutual Information scores are generated
6.Bar graph is plotted with mi scores
7.Train Test Split is done
8.Random forest is implemented
9.Accuracy and AUC score is generated

RESULT:
    Accuracy : 84.91 = 85%
    AUC score: 0.5545467812791867
