GOAL:
*Predict the total number of Washington D.C. bicycle users on an hourly basis.*

Task description:

* Exploratory Data Analysis (descriptive analytics) 
* Ensuring data quality (correctness, consistency, missing values, outliers...).
* Plotting clear and meaningful figures.
* Giving insights on what seems relevant for prediction and what does not.
* Bonus points for:
* Studying the influence of combinations of features (not just individual features).
* Checking possibly redundant variables via correlations.
* Data Engineering
* Discussion on missing values and outliers
* Treatment of text and date features
* Generation of extra features (e.g., season, yes/no holiday, hours of daylight, combinations of features, quantization/binarization, polynomial features)
* Use of scikit-learn pipelines to perform transformations
* Machine Learning (predictive analytics)
* Choosing sensible models (linear and non-linear).
* Tuning model parameters with validation (either with a fixed validation set or with cross-validation).
* Obtaining accurate predictions in test (measured with R2 score).
* Plotting predictions vs. reality for additional insights.
* Plotting validation results to justify further choices (parameter ranges, other validations...).
* Following an incremental approach (baseline models first, then more complex models, then combining models...)

More information: 
* Training data: whole 2011 and first 3 quarters of 2012.
* Test data: 4th quarter of 2012.  Do not use it to fit your models!
* Target: total number of users (cnt)
* Error metric: R2 score (scikit-learn's default for regression).
* Features to use: at least the ones present in the data (except for cnt, casual, and registered).
