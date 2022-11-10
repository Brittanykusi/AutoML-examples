# Summary of 5_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.500703 | nan         |
| auc       | 0.785714 | nan         |
| f1        | 0.769231 |   0.310576  |
| accuracy  | 0.842105 |   0.382559  |
| precision | 1        |   0.382559  |
| recall    | 1        |   0.0539663 |
| mcc       | 0.676123 |   0.382559  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.500703 |  nan        |
| auc       | 0.785714 |  nan        |
| f1        | 0.727273 |    0.382559 |
| accuracy  | 0.842105 |    0.382559 |
| precision | 1        |    0.382559 |
| recall    | 0.571429 |    0.382559 |
| mcc       | 0.676123 |    0.382559 |


## Confusion matrix (at threshold=0.382559)
|                |   Predicted as No |   Predicted as Yes |
|:---------------|------------------:|-------------------:|
| Labeled as No  |                12 |                  0 |
| Labeled as Yes |                 3 |                  4 |

## Learning curves
![Learning curves](learning_curves.png)

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



[<< Go back](../README.md)
