# Credit_Risk_Analysis
## Analysis Overview

In this analysis, we used Scikit-learn and Imbalanced-learn libraries to build different machine learning models in order to predict credit risk for a lending institution. We also assessed how well each model works based on their accuracy scores, precision and recall scores.

## Result

The balanced accuracy scores and the precision and recall scores for each model are as below:

![Naive Random Oversampling](https://user-images.githubusercontent.com/80492376/126049523-5630c369-2e1e-4f49-81ec-275553850116.png)

Native Random Oversampling: the balanced accuracy score is 0.66, precision score is 0.01 for high risk loan and 1 for low risk loan. The recall score is 0.66 for high risk loan and 0.67 for low risk loan.

![SMOTE Oversampling](https://user-images.githubusercontent.com/80492376/126049539-67126e2c-8e3a-4654-b79a-ee41eead0354.png)

SMOTE Oversampling algorithm: the balanced accuracy score is 0.66, precision score is 0.01 for high risk loan and 1 for low risk loan. The recall score is 0.66 for high risk loan and 0.67 for low risk loan.

![ClusterCentroids Undersampling algorithm](https://user-images.githubusercontent.com/80492376/126049545-25ecbe50-9f0b-4cc2-a0b0-50d62a813d46.png)

ClusterCentroids Undersampling algorithm: the balanced accuracy score is 0.51, precision score is 0.01 for high risk loan and 1 for low risk loan. The recall score is 0.57 for high risk loan and 0.45 for low risk loan.

![SMOTEENN Sampling algorithm](https://user-images.githubusercontent.com/80492376/126049563-312b3f9f-1e7e-4c53-888d-93f71c712ef9.png)

SMOTEENN Sampling algorithm: the balanced accuracy score is 0.65, precision score is 0.01 for high risk loan and 1 for low risk loan. The recall score is 0.74 for high risk loan and 0.58 for low risk loan.

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/80492376/126049591-6175bd3d-4718-4801-8cf9-89f503c6cdd9.png)

Balanced Random Forest Classifier: the balanced accuracy score is 0.78, precision score is 0.03 for high risk loan and 1 for low risk loan. The recall score is 0.70 for high risk loan and 0.87 for low risk loan.

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/80492376/126049605-ddd11cca-b000-455b-944c-3a86c7b8335b.png)

Easy Ensemble AdaBoost Classifier: the balanced accuracy score is 0.93, precision score is 0.09 for high risk loan and 1 for low risk loan. The recall score is 0.92 for high risk loan and 0.94 for low risk loan.
