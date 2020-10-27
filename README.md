# Vehicle_Price_Prediction #

**Aim:** To estimate selling price of cars based on features of cars

**Dataset Info** It contains information about used cars listed on www.cardekho.com

* name
* year
* selling_price
* km_driven
* fuel
* seller_type
* transmission
* owner

**Model**

* Random Forest

**Hyperparamter Tuning**

* Number of trees in random forest
* Number of features to consider at every split
* Maximum number of levels in tree
* Minimum number of samples required to split a node
* Minimum number of samples required at each leaf node

**Best Parameter**

* n_estimators: 700
* min_samples_split: 15
* min_samples_leaf: 1
* max_features: auto
* max_depth: 20

**Metrics**

* R-Squared Score: 0.9735114915286157
* Variance Score: 0.9735135158445363 


