# Conceptualize an application for public health

### Overview : Analysis of the Nutriscore, conception of a new score upon the weaknesses of the preceding. Cleaning of the OpenFoodFacts dataset.

Starting from the 3 GB dataset of OpenFoodFacts, the data is cleaned using several techniques: feature selection (the features that allow computing the Nutriscore), regular expressions, drops, imputations by statistics, imputations by models (KNN, Linear regression), and outlier detection. 

The dataset (the nutriscore) is analyzed through univariate analysis, bivariate analysis (Pearson, ANOVA, Komogorov-Smirnov, Levene, Kruskal-Wallis, QQPlot) and multivariate analysis with a principal component analysis for visualisation. 

The nudge score is imagined in response to this analysis which is an evolutional rate in between a n and n+1 basket scores.
