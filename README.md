# gbm
GBM Implementation with up to 5000 levels of a categorical variable 

This is a modification of the gradient boosting packages (gbm package) in R.  This gbm package has been modified to allow more than 1024 levels of a categoriacal variable.  It allows up to 5000 levels.

The previous version of the R gbm package would throw the following error when there were more than 1024 levels:  gbm does not currently handle categorical variables with more than 1024 levels. Variable ",i,": ",var.names[i]," has ",length(levels(x[,i]))," levels.")
