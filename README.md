## Project Title
**Bike Sharing Demand Analysis**

## Description
This project analyzes bike-sharing demand in Seoul based on weather and environmental data. Using data preprocessing, exploratory data analysis, and machine learning models, the project predicts bike-sharing demand with various features.

## Features
1. **Exploratory Data Analysis (EDA)**:
   - Scatter plots for visualizing relationships between variables and bike count.
   
2. **Data Preprocessing**:
   - Feature selection and cleaning.
   - Splitting data into training, validation, and testing sets.

3. **Linear Regression Models**:
   - Simple regression using temperature.
   - Multiple regression with all features.

4. **Neural Network Models**:
   - Single-layer and multi-layer models for demand prediction.
   - Loss tracking and visualization for training and validation.

5. **Visualization**:
   - Visualizing model performance and data relationships.

## Prerequisites
### Libraries Used:
- **Python 3.x**
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `tensorflow`
- `imblearn`
- `scikit-learn`

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd <repository-directory>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the **SeoulBikeData.csv** file in the root directory.


## Usage
1. Run the script:
   ```bash
   python script.py
   ```

2. The script performs:
   - EDA (scatter plots)
   - Linear regression analysis
   - Neural network-based regression

3. Outputs:
   - Visualizations for EDA and model performance.
   - Regression scores for each model.

## Results
1. **Simple Linear Regression**:
   - Relationship between temperature and bike demand.

2. **Multiple Linear Regression**:
   - Combining all features to predict bike demand.

3. **Neural Networks**:
   - Capturing complex relationships for accurate predictions.

## Future Work
- Incorporate seasonal data and holidays for better predictions.
- Explore other machine learning models like Random Forest or Gradient Boosting.
- Extend neural network architectures for higher accuracy.

