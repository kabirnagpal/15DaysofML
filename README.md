# 15DaysofML
This repository is a smaller version of [100DaysofML](https://github.com/kabirnagpal/100DaysofML) to motivate beginners to take up that challenge and dive deeper into the domain of Machine Learning.  

1. Worked with [StratifiedKFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.StratifiedKFold.html) and [XGBoost](https://xgboost.readthedocs.io/en/latest/) for a private anomaly detection dataset. [F1 - Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) was found to be around 96%.  
2. Worked on Data Visualisations using [Pairplot](https://seaborn.pydata.org/generated/seaborn.pairplot.html) and [Distplot](https://seaborn.pydata.org/generated/seaborn.distplot.html) to test Hypothesis and measure Skewness. Also worked on increasing Correalation of X with Y.  
3. Worked on [Feature extractions](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.feature_selection) for decreasing time consumed to train the model. Models used  
    - [recursive feature elimination](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html#sklearn.feature_selection.RFE)
    - [f_classif](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.f_classif.html#sklearn.feature_selection.f_classif)
    - [mutual_info_classif](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html#sklearn.feature_selection.mutual_info_classif)
    - [SelectFromModel](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectFromModel.html#sklearn.feature_selection.SelectFromModel)  
4. Worked with [XGBoost](https://xgboost.readthedocs.io/en/latest/python/python_api.html) on the dataset and finetuned to reach an F1-score of 96.2% on an anomalies detection dataset.
5. Worked on reducing [skewness](https://towardsdatascience.com/transforming-skewed-data-73da4c2d0d16) of the dataset. Also worked with [Power Tranform](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PowerTransformer.html#sklearn.preprocessing.PowerTransformer) and understood the working. 
    - Right skewed: log transform
    - Left skewed : square transform
