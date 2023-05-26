# -Unsupervised-ML-Retail-Sales-Predication-ML-project-Sunil-Kumar-K
During our analysis, we noticed that the Sales column contained a significant number of rows with zero sales, totaling 172,817 rows. Initially, we created a new dataframe by removing these rows with zero sales and proceeded to train our model. We applied various algorithms and achieved an accuracy score of approximately 74%.

However, our curiosity led us to explore the total dataset, including the rows with zero sales. Subsequently, we trained another model using different algorithms and obtained an impressive accuracy of around 98%. This result was significantly better than the previous model.

Based on these findings, we reached the conclusion that removing the rows with zero sales actually resulted in the loss of valuable information. Given the substantial number of such rows (172,817), it became apparent that removing them would eliminate a large portion of the dataset. Consequently, we decided not to remove these values from our analysis.

Our best model in terms of Root Mean Percentage Error (RMPSE) was achieved using the Random Forest algorithm. Additionally, we explored gradient boosting techniques such as Adaboost and XGBoost. We carefully selected the optimal parameters for these algorithms to prevent overfitting and ensure reliable predictions.
