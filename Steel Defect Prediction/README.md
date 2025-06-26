# STEEL PLATE DEFECT PREDICTION

#### Dataset Description
The dataset was obtained from Steel Plates Faults dataset from UCI. Feature distributions are close to, but not exactly the same, as the original.

#### Evaluation
Submissions are evaluated using area under the ROC curve using the predicted probabilities and the ground truth targets.

To calculate the final score, AUC is calculated for each of the 7 defect categories and then averaged. In other words, the score is the average of the individual AUC of each predicted column.

#### Additional Information
Type of dependent variables (7 Types of Steel Plates Faults):
1.Pastry
2.Z_Scratch
3.K_Scatch
4.Stains
5.Dirtiness
6.Bumps
7.Other_Faults

SOURCE: https://www.kaggle.com/competitions/playground-series-s4e3/data
