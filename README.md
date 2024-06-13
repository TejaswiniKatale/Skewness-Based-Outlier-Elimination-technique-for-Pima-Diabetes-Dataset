An Outlier is a data point which appears to be distinct from the majority of the other data
 points within a dataset. Various factors, such as measurement errors, data entry problems, natural
 variability, and extreme events, can lead to outliers. They may lead to erroneous evaluation
 measures, biased data analysis, and incorrect model performance resulting in in-suitable outcomes.
 Hence, identification and elimination of outliers is a crucial pre-processing step. This research
 paper suggests an algorithm for correctly removing outliers from the Pima Diabetes Dataset. It
 takes into consideration the correlation values of the features with the outcome column, further
 arranging them in descending order. The normal distribution graphs for each feature in the dataset
 are plotted for data analysis. For the Diabetes dataset, the features are either Positive (Right)
 skewed or Symmetrical. For the Symmetrical curve features, it eliminates data points which are
 lying beyond three standard deviations i.e (µ- 3σ) and (µ + 3σ), whereas for Positively skewed
 features, it eliminates those data points which are greater than (µ + 2.5σ). Starting from the
 feature having the highest correlation value, based on the skewness it eliminates the outliers by
 iterating the features one by one based on the order of correlation values. The proposed algorithm
 is successful in elimination of 108 rows from Pima Diabetes Dataset. To check the efficacy of
 the algorithm, it is compared with four techniques- Local Outlier Factor, Mahalanobis Distance,
 Multivariate Normal Distribution (N Dimensional) and DBSCAN. Also, for better evaluation
 the number of outliers eliminated by each technique lies in the same range. Furthermore, after
 elimination of outliers, three Machine Learning are implemented- Logistic Regression, Random
 Forest and Decision Tree. Among all the techniques, logistic regression on the proposed algorithm
 gives the highest accuracy of 84%, highest precision of 0.88 and highest recall of 0.65.
