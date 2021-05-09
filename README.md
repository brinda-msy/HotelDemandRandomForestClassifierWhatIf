# HotelDemandRandomForestClassifierWhatIf
Random forest classifier is a bagging/averaging method where average from predictions based on several estimators are considered because the variance is reduced. It is a modified learner with a number of decision trees within it (Farooq et al, 2021). The RFC model was tried by specifying various values for n_estimators (the number of trees to build while taking average of predictions) and the default value of 100 was found to have best accuracy. The quality of the split was measured using Gini impurity (criterion = gini) and depth of the trees was until leaves are pure (max_depth=None). Minimum two samples were needed for a node to be split (min_samples_split = 2). 
