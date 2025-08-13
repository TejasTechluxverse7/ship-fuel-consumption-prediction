# ship-fuel-consumption-prediction
"Prediction of ship fuel consumption using machine learning and mathematical models"

Ship Fuel Consumption Prediction Models
Project Description
This project aims to predict ship fuel consumption and CO₂ emissions using both Machine Learning (ML) models and mathematical methods. The approach combines white-box (physics-based) and black-box (ML-based) models to enhance accuracy, interpretability, and robustness. The primary goal is to optimize fuel use, reduce costs, and contribute to sustainable shipping practices.
Dataset
The dataset used is 'Ship Fuel Consumption and CO₂ Emissions Analysis' sourced from Kaggle. It contains 1,440 entries and 10 features, including ship_id, ship_type, route_id, month, distance, fuel_type, fuel_consumption, CO₂_emissions, weather_conditions, and engine_efficiency.

The workflow includes:
1. Data Loading & Inspection
2. Data Cleaning (Z-score method for outlier removal)
3. Handling Missing Values
4. Feature Engineering (speed, displacement, power)
5. Encoding & Scaling (MinMaxScaler)
6. Train-Test Split (80%-20%)
7. Model Training & Evaluation
Models used: White Box, Random Forest, XGBoost.
Model Performance Summary
White Box:
 - MAE: 38214004.79
 - MSE: 6181.74
 - R²: -1.21

Random Forest:
 - MAE: 181.71
 - MSE: 73171.67
 - RMSE: 270.50
 - R²: 0.9955

XGBoost:
 - MAE: 117.80
 - MSE: 76177.09
 - RMSE: 276.00
 - R²: 0.9957

XGBoost performed the best in terms of accuracy and robustness.
Visualizations
 - Histogram: Distribution of fuel consumption
 - Boxplot: Comparison across ship types
 - Heatmap: Correlation between features and target
 - Scatter plots: Feature-wise relationships with fuel consumption
   
Key Learnings
 - Gained practical insights into applying ML models for predictive analytics.
 - Improved data cleaning and feature engineering skills.
 - Enhanced visualization techniques for effective model communication.
 - Strengthened understanding of Random Forest and XGBoost algorithms.
   
Future Directions
 - Implement time-series forecasting.
 - Predict CO₂ emissions in real-time.
 - Integrate with dashboards and apps for accessibility.
 - Explore Deep Learning models like LSTM.
   
Installation & Usage
1. Clone the repository:
   git clone https://github.com/<your-username>/ship-fuel-consumption-prediction.git
2. Navigate to the project folder:
   cd ship-fuel-consumption-prediction
3. Install dependencies:
   pip install -r requirements.txt
4. Run the Jupyter Notebook 'Final.ipynb' to reproduce the analysis.
   
License
This project is licensed under the GNU License - see the LICENSE file for details.

