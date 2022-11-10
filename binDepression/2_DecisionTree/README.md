# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

11.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.15247  | nan         |
| auc       | 0.744048 | nan         |
| f1        | 0.538462 |   0.0642857 |
| accuracy  | 0.368421 |   0.0642857 |
| precision | 0.368421 |   0.0642857 |
| recall    | 1        |   0.0642857 |
| mcc       | 0        |   0.0642857 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.15247  | nan         |
| auc       | 0.744048 | nan         |
| f1        | 0.538462 |   0.0642857 |
| accuracy  | 0.368421 |   0.0642857 |
| precision | 0.368421 |   0.0642857 |
| recall    | 1        |   0.0642857 |
| mcc       | 0        |   0.0642857 |


## Confusion matrix (at threshold=0.064286)
|                |   Predicted as No |   Predicted as Yes |
|:---------------|------------------:|-------------------:|
| Labeled as No  |                 0 |                 12 |
| Labeled as Yes |                 0 |                  7 |

## Learning curves
![Learning curves](learning_curves.png)

## Decision Tree 

### Tree #1
![Tree 1](learner_fold_0_tree.svg)

### Rules

if (Marital status <= 0.5) and (What is your course? <= 22.5) and (Timestamp > 15.5) then class: No (proba: 92.86%) | based on 28 samples

if (Marital status <= 0.5) and (What is your course? <= 22.5) and (Timestamp <= 15.5) then class: No (proba: 69.23%) | based on 13 samples

if (Marital status > 0.5) then class: Yes (proba: 100.0%) | based on 8 samples

if (Marital status <= 0.5) and (What is your course? > 22.5) and (Age <= 19.0) then class: Yes (proba: 100.0%) | based on 4 samples

if (Marital status <= 0.5) and (What is your course? > 22.5) and (Age > 19.0) then class: No (proba: 66.67%) | based on 3 samples





## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions for class 0 (Fold 1)
![SHAP worst decisions class 0 from Fold 1](learner_fold_0_shap_class_0_worst_decisions.png)
### Top-10 Best decisions for class 0 (Fold 1)
![SHAP best decisions class 0 from Fold 1](learner_fold_0_shap_class_0_best_decisions.png)
### Top-10 Worst decisions for class 1 (Fold 1)
![SHAP worst decisions class 1 from Fold 1](learner_fold_0_shap_class_1_worst_decisions.png)
### Top-10 Best decisions for class 1 (Fold 1)
![SHAP best decisions class 1 from Fold 1](learner_fold_0_shap_class_1_best_decisions.png)

[<< Go back](../README.md)
