## Introduction
This project aims to classify the price range of mobile phones using machine learning techniques random forset.
 ## Dataset
battery_power: Total energy a battery can store in one time measured in mAh
blue: Has bluetooth or not
clock_speed: speed at which microprocessor executes instructions
dual_sim: Has dual sim support or not
fc: Front Camera mega pixels
four_g: Has 4G or not
int_memory: Internal Memory in Gigabytes
m_dep: Mobile Depth in cm
mobile_wt: Weight of mobile phone
n_cores: Number of cores of processor
pc: Primary Camera mega pixels
px_height: Pixel Resolution Height
px_width: Pixel Resolution Width
ram: Random Access Memory in Mega Bytes
sc_h: Screen Height of mobile in cm
sc_w: Screen Width of mobile in cm
talk_time: longest time that a single battery charge will last when you are
three_g: Has 3G or not
touch_screen: Has touch screen or not
wifi: Has wifi or not
price_range: This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost)
## Data Analysis and Preprocessing
Before building our predictive model, I perform data analysis and preprocessing to understand the dataset and prepare it for training. This includes:
- Checking the dataset dimensions
- Exploring feature columns and their types
- Splitting the data into training and testing sets
## Exploratory Data Analysis
Exploratory Data Analysis (EDA) helps us understand the relationships between different features and the target variable. I use visualization libraries such as create visualizations, including:
- Bar Plots to Explore Categorical Variable 
- Distribution plots of numerical features
- Heatmaps to visualize correlations between features
## Feature Selection
The dataset was analyzed to select the most relevant features that contribute to the classification of mobile price range using Wrapper methods. Features such as mobile depth in cm , RAM , 4G , battery power ,dual sim ,pixel resolution height, pixel resolution width,screen height of mobile in cm ,screen width of mobile in cm and touch screen   were considered significant for predicting the price range accurately.
## Model Performance
Random Forest : Accuracy = 0.9125
