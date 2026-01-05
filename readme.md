**💰 Gold Price Prediction using Machine Learning 📈**

**📝 Project Overview**

This project focuses on predicting the price of Gold (GLD) using historical financial data. By analyzing the relationship between gold and other market assets like the S&P 500, Silver prices, and Crude Oil, we built a robust predictive model using the Random Forest Regressor algorithm.

**📊 Dataset Information**

The dataset contains 2,290 daily records of gold prices and related financial indicators.

    Date: The date of the observation.

    SPX: The S&P 500 Stock Market Index.

    GLD: Gold Price (Target Variable).

    USO: United States Oil Fund prices.

    SLV: Silver Price.

    EUR/USD: Currency exchange rate.

**🚀 Key Features**

    ✅ Data Cleaning: Handling missing values and formatting.

    ✅ Exploratory Data Analysis (EDA): Visualizing trends and distributions.

    ✅ Correlation Analysis: Understanding how Silver and Stock indices impact Gold.

    ✅ Predictive Modeling: Using a Random Forest ensemble method.

    ✅ Accuracy Visualization: Comparing "Actual" vs. "Predicted" prices through line graphs.

**🛠️ Technologies Used**

    Python: Primary programming language.

    Pandas & NumPy: For data manipulation and processing.

    Matplotlib & Seaborn: For data visualization and correlation analysis.

    Scikit-Learn: For splitting data, model training, and performance metrics.

**🏗️ Workflow**

    Data Collection: Loading the gld_price_data.csv file. 📁

    Data Pre-processing: Inspecting statistical measures and checking for null values. 🔍

    Data Analysis:

        Generating a Heatmap to find correlations.

        Checking the distribution of Gold prices. 📉

    Train-Test Split: Dividing data into training (80%) and testing (20%) sets. ✂️

    Model Training: Implementing the RandomForestRegressor. 🌲

    Model Evaluation: Using R-Squared Error to check performance. 🏆

**📈 Results**

The model performs exceptionally well with a high R-Squared value, indicating that the features (Silver price, SPX, etc.) are strong predictors for Gold price movements.

    R-Squared Error: ~0.989 (High accuracy) ✅

    Prediction vs Actual: The visualization shows that the predicted values almost perfectly overlap with the actual gold prices.