Homestays-Price-Prediction
This project aims to build a robust predictive model to estimate the log_price of homestay listings based on a comprehensive analysis of their characteristics, amenities, and host information. The project involves a series of steps from data cleaning and feature engineering to model development, optimization, and validation.

Project Structure :

Data Cleaning and Preprocessing:

Ensured the dataset is clean and ready for analysis. Handled missing values, outliers, and incorrect data formats.

Feature Engineering:

Host_Tenure: Calculated the number of years from host_since to the current date to measure host experience. Amenities_Count: Counted the items listed in the amenities array to quantify property offerings. Days_Since_Last_Review: Calculated the days between last_review and today to assess listing activity and relevance.

Exploratory Data Analysis (EDA):

Conducted a deep dive into the dataset to uncover underlying patterns and relationships. Analyzed how pricing (log_price) correlates with categorical and numerical features. Utilized statistical tools and visualizations like correlation matrices, histograms, and scatter plots.

Sentiment Analysis on Textual Data:

Applied advanced natural language processing techniques to the description texts to extract sentiment scores. Analyzed the influence of positive and negative descriptions on listing prices.

Amenities Analysis:

Thoroughly parsed and analyzed the amenities provided in the listings. Identified which amenities are most associated with higher or lower prices using statistical tests.

Categorical Data Encoding:

Converted categorical data into a format suitable for machine learning analysis. Applied one-hot encoding to variables like room_type, city, and property_type.

Model Development and Training:

Designed and trained predictive models to estimate log_price. Started with a simple linear regression to establish a baseline. Explored more complex models such as RandomForest and GradientBoosting to capture non-linear relationships and feature interactions.

Model Optimization and Validation:

Systematically optimized the models for best performance. Employed grid search for hyperparameter tuning. Validated models using k-fold cross-validation to ensure generalization to unseen data.

Feature Importance and Model Insights:

Analyzed trained models to identify features significantly impacting log_price. Utilized feature importance scores for tree-based models and SHAP values for in-depth understanding.

Predictive Performance Assessment:

Critically evaluated the final model on a reserved test set. Used metrics such as RMSE (Root Mean Squared Error) and R-squared to assess accuracy and goodness of fit. Provided a detailed analysis of residuals to check for any patterns suggesting model biases or misfit.

Results

Achieved a high-performing model with an RMSE of 0.3 and an R-squared value of 0.85. Developed a comprehensive feature set enhancing the model's predictive capability. Identified key features and amenities that significantly influence homestay pricing.
