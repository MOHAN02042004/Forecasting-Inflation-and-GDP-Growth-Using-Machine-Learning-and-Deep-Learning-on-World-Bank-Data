# Forecasting-Inflation-and-GDP-Growth-Using-Machine-Learning-and-Deep-Learning-on-World-Bank-Data
Objective: Developed a hybrid machine learning and deep learning framework to forecast key macroeconomic indicators—specifically inflation and GDP growth—using historical World Bank data. The system supports economic analysis, planning, and policy decision-making through robust, temporal-aware predictions.

•  Engineered time-series features including 1-year lag variables, 3-year rolling means, and    GDP per capita growth to capture economic dynamics and momentum across countries and years.

• Designed and trained separate deep neural networks for inflation and GDP growth prediction, incorporating dropout regularization and early stopping to prevent overfitting.

• Built a preprocessing pipeline using ColumnTransformer for parallel handling of numeric scaling (StandardScaler) and categorical encoding (OneHotEncoder), ensuring consistent feature transformations.

• Applied machine learning techniques such as median/mode imputation, time-based train-test splitting, and country-level filtering to enhance model reliability and data integrity.

• Evaluated models using R², Mean Squared Error (MSE), and Mean Absolute Error (MAE) across training and test sets, confirming performance improvements over naive baselines.

• Visualized loss curves, prediction accuracy, and residual distributions to validate model behavior and guide tuning decisions.

• Enabled use of the framework for macroeconomic scenario planning and forecasting in development economics, finance, and public policy contexts.


Skills & Tools Used: Python, Pandas, NumPy, TensorFlow, Keras, Scikit-learn, Deep Learning, Machine Learning, Time-Series Forecasting, Economic Modeling, Feature Engineering, Data Preprocessing, Regression Analysis, ColumnTransformer, Dropout, EarlyStopping
