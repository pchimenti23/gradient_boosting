# gradient_boosting

******These notebooks currently require an update due to 'ensemble.partial_dependence' appearing to have been deprecated and needing to be replaced by 'inspection.partial_dependence' and/or 'inpsection.PartialDependenceDisplay'******


This repository contains beginner tutorials for classification and regression using gradient boosting.  The material that is common to both methods is largely recycled.  However, anything specific to the method being used has been specifically adapted.  In this way, someone does not need to open one tutorial to get the full benefit of the other.  This treatment is not a completely comprehensive overview of the techniques.  Rather, it is a hands on walkthrough of how to build a useful model with real data.

Some may observe that feature scaling is not performed on the inputs to the model.  Note that since this is a tree based algorithm, it is simply find the optimal place to split the data into two groups.  For this reason, feature scaling is not necessary.  Feature scaling would not be detrimental to the model.  If two or more methods are being tested which require scaling, that same input can be used for gradient boosting.  In this treatment, features have been left unscaled for practical interpretability.
