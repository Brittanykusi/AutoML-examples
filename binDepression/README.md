# AutoML Leaderboard

| Best model   | name                                                         | model_type     | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------|:---------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                           | Baseline       | logloss       |       0.659979 |         3.03 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                   | Decision Tree  | logloss       |       1.15247  |        13.02 |
|              | [3_Linear](3_Linear/README.md)                               | Linear         | logloss       |       0.541337 |         5.54 |
|              | [4_Default_Xgboost](4_Default_Xgboost/README.md)             | Xgboost        | logloss       |       0.617395 |         7.15 |
|              | [5_Default_NeuralNetwork](5_Default_NeuralNetwork/README.md) | Neural Network | logloss       |       0.508732 |         2.42 |
|              | [6_Default_RandomForest](6_Default_RandomForest/README.md)   | Random Forest  | logloss       |       0.503059 |         9.87 |
| **the best** | [Ensemble](Ensemble/README.md)                               | Ensemble       | logloss       |       0.45855  |         0.52 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance
![features importance across models](features_heatmap.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

