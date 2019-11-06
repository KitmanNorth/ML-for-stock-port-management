# ML-for-stock-port-management
It's a trial project using ML for SET trading decisions

// create Individual-Stock directory

1. run individual_method.ipynb (training set) to divided all-stock into each stock
2. run add_indicators_to_all_stock.ipynb (training set)

// create Individual-Stock-Test directory 

3. run individual_method.ipynb (testing set) to divided all-stock into each stock

// create Individual-Stock-Test-Mod directory

4. run add_predata_to_test_set.ipynb
5. run add_indicators_to_all_stock.ipynb (testing set)

// create labeled-stock directory

6. run labelling_data.ipynb
7. run cleansing_data_before_merge_them.ipynb
8. run merge_all_stock.ipynb

// create labeled-stock-test directory

9. run labelling_data.ipynb (testing set)
10. run cleansing_data_before_merge_them.ipynb (testing set)
11. run merge_all_stock.ipynb (testing set)

12. choose model to train and save model
- Decision_Tree
- Random_forest
- XGBoost

13. run Test_model.ipynb to test model and evaluate them

