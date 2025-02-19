# Smart Home Energy Predictions: IoT and Machine Learning
### AAI-530 IoT and Machine Learning Final Project
University of San Diego, School of Engineering - Masters of Applied Artificial Intelligence

## Project Overview
This project leverages IoT sensor data to develop predictive models and classifications for indoor environmental conditions. Using deep learning techniques, including Long Short-Term Memory (LSTM) networks, Convolutional Neural Networks (CNN), and Seasonal Autoregressive Integrated Moving Average with Exogenous Variables (SARIMAX), the study explores temperature forecasting and anomaly detection in smart home settings.

## Project Components
### Final Paper

The technical paper provides an in-depth analysis of the project, detailing data preprocessing, exploratory data analysis (EDA), model selection, and performance evaluation. 

Key insights include:

- Data sources: EcoLab Ground and WeatherLink Indoor sensors.

- Data preprocessing: Outlier removal, missing value handling, feature engineering.

Modeling results:

- LSTM achieved a Root Mean Squared Error (RMSE) of 0.81°C.

- CNN classified indoor conditions with 94% accuracy but struggled with rare classes.

- SARIMAX performed well for short-term forecasts but declined in long-term accuracy.

## Dashboard

The interactive dashboard visualizes key findings, including:

- Time-series analysis of temperature trends from June to November 2023.

- Comparison of predicted vs. actual temperatures using LSTM and SARIMAX.

- eCO₂ levels and classification results for different environmental conditions.

## Codebase

The code repository consists of Python scripts and Jupyter Notebooks for:

- Data preprocessing: Cleaning and feature engineering.

- Modeling: Implementation of LSTM, CNN, and SARIMAX models.

- Evaluation: Performance metrics and comparative analysis.

- Visualization: Graphs and plots illustrating trends and predictions.

## Git Ignore & License

- .gitignore specifies ignored files, ensuring version control efficiency.

*LICENSE outlines usage rights, adhering to Apache License 2.0 for software and Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) for dataset use.*

## How to Use

1. Clone the repository:

```git clone https://github.com/oxayavongsa/aai-530-iot-smart-house.git```

2. Install dependencies:

```pip install -r requirements.txt```

3. Run the Jupyter Notebook:

- Open and execute Final_Code_G3.ipynb in Jupyter or Google Colab.

4. Explore results:

- View predictions and insights in the provided dashboard.

## Key Findings

- LSTM outperformed traditional time-series models in capturing temperature variations.
  ![LSTM Model Predictions vs. Actual Indoor Temperture (°F)]([path_to_image.png](https://public.tableau.com/app/profile/outhai.xayavongsa/viz/FinalPredictions/IoTSmartHomeDashboard))
  ![image](https://github.com/user-attachments/assets/3f4cf25d-9fba-4846-a1cc-cdd1cac0dc8d)

- CNN effectively classified environmental conditions but required better handling of imbalanced classes.

- SARIMAX provided interpretability but struggled with long-term forecasting.

- Data preprocessing, including smoothing and interpolation, significantly improved model performance.

## Future Enhancements

- Incorporate real-time IoT data streams for live monitoring.

- Explore hybrid models combining CNN and LSTM for enhanced spatial and temporal analysis.

- Improve handling of rare conditions through class balancing techniques.

## Contributors

- Outhai Xayavongsa (Ms. Thai) - Team Leader

- Aaron Ramirez - Tech Lead

## License

The software is licensed under Apache License 2.0.

The dataset follows the Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.
