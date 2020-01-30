# LTFS-Data-Science-FinHack-2

Dataset split:
1. In "FinHack_V1_Ada_Boost.ipynb" manually created validation set from train set
2. In "FinHack_AdaBoost_Simple_Model.ipynb" manually created validation set from train set by removing lastest dates from train set
3. Manually created test set file that is inline with train file

Approach:
  1. Added holidays
  2. Added share prices of L&T Finance Holdings
  3. Added date time features
  4. Used Adaboost Regressor from sklearn

Note: Share price data is not considered for "FinHack_AdaBoost_Simple_Model.ipynb"

Best Model: "FinHack_AdaBoost_Simple_Model.ipynb" with Public score: 13.460, Private score: 23.0178
