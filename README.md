The primary purpose here was to create a running code that could be used for any dataset (already preprocessed) 
suitable for the model to bring some meaningful results. 
To run the code, make sure to follow these steps:
1. Use datasets that work well under ExtraTreesClassifier (structured/tabular datasets, especially when handling
   complex, non-linear relationships, imbalanced classes, and high-dimensional data)
3. Make sure the dataset is cleaned and preprocessed with target and input variables ascertained.
4. Avoid colab or other online python notebooks if you are using a large dataset that requires a lot of CPU power
   when running studies in Optuna. 
