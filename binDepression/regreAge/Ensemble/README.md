# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                  |   Weight |
|:-----------------------|---------:|
| 3_Linear               |        1 |
| 6_Default_RandomForest |        2 |

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.415842 |  nan        |
| auc       | 0.809524 |  nan        |
| f1        | 0.833333 |    0.382845 |
| accuracy  | 0.894737 |    0.382845 |
| precision | 1        |    0.382845 |
| recall    | 1        |    0.112398 |
| mcc       | 0.782461 |    0.382845 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.415842 |  nan        |
| auc       | 0.809524 |  nan        |
| f1        | 0.833333 |    0.382845 |
| accuracy  | 0.894737 |    0.382845 |
| precision | 1        |    0.382845 |
| recall    | 0.714286 |    0.382845 |
| mcc       | 0.782461 |    0.382845 |


## Confusion matrix (at threshold=0.382845)
|                |   Predicted as No |   Predicted as Yes |
|:---------------|------------------:|-------------------:|
| Labeled as No  |                12 |                  0 |
| Labeled as Yes |                 2 |                  5 |

## Learning curves
![Learning curves](learning_curves.png)
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
