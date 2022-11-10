# Summary of 3_Linear

[<< Go back](../README.md)


## Logistic Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

3.4 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.499367 | nan         |
| auc       | 0.77381  | nan         |
| f1        | 0.833333 |   0.573201  |
| accuracy  | 0.894737 |   0.573201  |
| precision | 1        |   0.573201  |
| recall    | 1        |   0.0167229 |
| mcc       | 0.782461 |   0.573201  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.499367 |  nan        |
| auc       | 0.77381  |  nan        |
| f1        | 0.833333 |    0.573201 |
| accuracy  | 0.894737 |    0.573201 |
| precision | 1        |    0.573201 |
| recall    | 0.714286 |    0.573201 |
| mcc       | 0.782461 |    0.573201 |


## Confusion matrix (at threshold=0.573201)
|                |   Predicted as No |   Predicted as Yes |
|:---------------|------------------:|-------------------:|
| Labeled as No  |                12 |                  0 |
| Labeled as Yes |                 2 |                  5 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature                                      |   Learner_1 |
|:---------------------------------------------|------------:|
| Marital status                               |   1.49327   |
| Did you seek any specialist for a treatment? |   0.646115  |
| Do you have Anxiety?                         |   0.539524  |
| age                                          |   0.354082  |
| Do you have Panic attack?                    |   0.267781  |
| Your current year of Study                   |   0.0854077 |
| Timestamp                                    |   0.0640348 |
| What is your course?                         |   0.0580102 |
| What is your CGPA?                           |  -0.326016  |
| intercept                                    |  -0.723588  |
| Choose your gender                           |  -0.755524  |


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
