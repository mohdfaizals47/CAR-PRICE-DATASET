# CAR-PRICE-DATASET

Car Price Analysis (EDA Project)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a car dataset to understand the factors affecting car selling prices. The analysis includes data cleaning, preprocessing, visualization, and deriving meaningful insights.

📂 Dataset
The dataset contains details of used cars such as:
Year of manufacture
Selling price
Fuel type
Transmission type
Other technical specifications
⚙️ Technologies Used
Python
Pandas – Data manipulation
NumPy – Numerical operations
Seaborn & Matplotlib – Data visualization
🔧 Steps Performed
1. Import Libraries

Loaded all required libraries for data analysis and visualization.

2. Data Loading
Dataset loaded using pandas.read_csv()
3. Data Cleaning
Checked for missing values
Dropped unnecessary columns:
mileage
engine
max_power
seats
4. Data Preprocessing
Created a new feature:
Car_Age = Current Year (2026) - Manufacturing Year
📊 Data Visualization & Insights
🔹 1. Fuel Type Distribution
Diesel cars are the most common
Petrol cars follow next
🔹 2. Transmission Distribution
Manual cars dominate the dataset
🔹 3. Selling Price Distribution
Most cars fall in the lower price range
🔹 4. Car Age vs Selling Price
Older cars tend to have lower selling prices
📈 Key Insights
🚘 Diesel vehicles are more prevalent in the dataset
⚙️ Manual transmission is more common than automatic
💰 Selling price decreases as the car ages
📉 Price distribution is skewed towards lower values
🧠 Conclusion

The analysis shows that:

Car age is inversely proportional to selling price
Fuel type and transmission influence market trends
Most used cars are sold at affordable price ranges
