# Mexico-House-Price-Prediction
🏠 Mexico House Price Prediction
📌 Project Overview
This project focuses on predicting apartment prices in Mexico using machine learning techniques.
It involves cleaning and merging multiple datasets, performing exploratory data analysis (EDA), detecting outliers, and building a Linear Regression model to estimate prices. The goal is to demonstrate data wrangling, feature engineering, and model development skills in an end-to-end workflow.

📊 Dataset
    Source: Kaggle — Mexico Apartment Price Dataset (multiple files merged).

    Features: Includes location, size, amenities, and other property characteristics.

    Target Variable: Apartment price.

🔄 Workflow
1. Data Preparation & Cleaning
    Loaded multiple datasets and merged them into a single dataframe.

    Handled missing values and ensured consistent data types.

    Removed duplicates and standardized column names.

2. Outlier Detection
    Identified outliers in numerical columns using statistical methods and visual inspection.

    Used scatter plots and box plots for confirmation.

3. Exploratory Data Analysis (EDA)
    Generated descriptive statistics to understand feature distributions.

    Plotted correlations to identify relationships between predictors and target.

4. Feature Selection & Splitting
    Selected key features based on correlation strength and domain relevance.

    Split dataset into training and test sets (80/20 split).

5. Baseline Model
    Built a baseline Linear Regression model to set performance benchmarks.

6. Model Training & Evaluation
    Trained a Linear Regression model on the training set.

    Evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

📈 Results
    The final model achieved [Insert R² score here]% accuracy on the test set.

    Key insight: [Insert your main finding, e.g., "Apartment size and location had the highest correlation with price"].

🛠️ Technologies Used
    Python (Pandas, NumPy, Matplotlib, Scikit-learn)

    Jupyter Notebook

    Kaggle (dataset source)
