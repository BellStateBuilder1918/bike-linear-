Seoul Bike Data Analysis

This project analyzes the Seoul Bike data to investigate the relationship between various environmental factors and the number of bike rentals. The analysis uses regression techniques, including both traditional linear regression and neural networks, to model these relationships.

Project Overview

The analysis is divided into the following steps:

Data Preparation

Load and clean the data by removing irrelevant columns and filtering for specific conditions.

Preprocess features, including handling categorical variables and scaling.

Exploratory Data Analysis (EDA)

Visualize the relationships between bike rentals and environmental factors such as temperature, humidity, and others.

Modeling

Linear Regression: Simple and multiple linear regression models.

Neural Networks: Deep learning models using TensorFlow to capture complex relationships.

Evaluation

Evaluate models using metrics like Mean Squared Error (MSE) and visualize their performance.

Dataset

The dataset used in this project is SeoulBikeData.csv, which contains the following columns after preprocessing:

bike_count: Number of bikes rented.

temp: Temperature (in degrees Celsius).

humidity: Humidity percentage.

dew_pt_temp: Dew point temperature.

radiation: Solar radiation.

rain: Rainfall (mm).

snow: Snowfall (cm).

Columns wind, visibility, and functional are removed after initial exploration.

Dependencies

The project requires the following Python libraries:

pandas

numpy

matplotlib

seaborn

tensorflow

scikit-learn

imbalanced-learn

Usage

Setup:
Ensure all dependencies are installed. Use the following command to install the required packages:

pip install pandas numpy matplotlib seaborn tensorflow scikit-learn imbalanced-learn

Run the Script:
Execute the Python script to perform the analysis:

python analysis_script.py

Outputs:

Scatter plots for each feature against bike_count.

Performance metrics for linear regression and neural network models.

Loss curves for the neural network models during training.

Key Insights

Temperature has a significant linear relationship with bike rentals, as demonstrated by the linear regression model.

More complex models, such as neural networks, can capture additional nuances in the data.

Future Improvements

Incorporate additional features like holidays and seasonal data.

Explore advanced regression techniques and hyperparameter tuning for neural networks.

Deploy the model using a web-based interface for real-time predictions.
