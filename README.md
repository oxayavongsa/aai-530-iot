# Smart Home Energy Predictions: Models Branch

AAI-530 IoT and Machine Learning Final Project

University of San Diego, School of Engineering - Masters of Applied Artificial Intelligence

## Project Overview

This branch focuses on the development and evaluation of predictive models for smart home energy forecasting. Various machine learning and deep learning models are implemented to forecast temperature and classify environmental conditions based on IoT sensor data.

## Project Components

### Models Implemented

- ARIMA (AutoRegressive Integrated Moving Average) – Traditional statistical approach for time-series forecasting.

- SARIMAX (Seasonal ARIMA with Exogenous Variables) – Used for temperature forecasting incorporating seasonality.

- LSTM (Long Short-Term Memory Network) – Recurrent Neural Network (RNN) optimized for sequential data predictions.

- CNN (Convolutional Neural Network) – Used for classification of indoor conditions (comfortable, humid, dry, unstable).

Hybrid Models – Combination of CNN, LSTM, and ARIMA for enhanced forecasting accuracy.

## Notebooks Included

- ```ARIMA.ipynb``` – ARIMA and SARIMAX model implementations and evaluations.

- ```LSTM.ipynb``` – Deep learning model using LSTM for temperature forecasting.

- ```CNN.ipynb``` – CNN-based model for environmental classification.

- ```CNN_class.ipynb``` – Fine-tuned CNN classification for improved predictions.

- ```All_Models_Combined.ipynb``` – Unified implementation combining all models for evaluation.

- ```All_Models_Combined_Rev_CNN.ipynb``` – Revised CNN-based approach for indoor condition classification.

## Data Files

Preprocessed datasets used for model training and evaluation:

- ```EcoLab Ground Cleaned.csv```

- ```Front Door Cleaned.csv```

- ```Weather Link Indoor Cleaned.csv```

## Trained Models

Trained versions of models saved for reuse:

- ```final_cnn_model.keras```

- ```lstm_model_optimized.keras```

## Installation & Dependencies

To install the required dependencies, run:

- ```pip install -r requirements.txt```

Ensure requirements.txt is included in the project directory to set up the environment.

## How to Use

Clone the repository:

- ```git clone -b models https://github.com/oxayavongsa/aai-530-iot-smart-house.git```

Install dependencies:

- ```pip install -r requirements.txt```

Run Jupyter Notebook:

- Open and execute any of the ```.ipynb files``` in Jupyter or Google Colab.

Explore Results:

- Evaluate model predictions and classification accuracy.

## Google Colab Notebook

To explore the code, open the Jupyter Notebook in Google Colab:

<a href="https://colab.research.google.com/github/oxayavongsa/aai-530-iot-smart-house/blob/main/All_Models_Combined.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
</a>

## Key Findings

- LSTM outperformed ARIMA in long-term time-series forecasting.

- CNN effectively classified environmental conditions but required better handling of imbalanced classes.

- Hybrid models showed improvements in accuracy by combining deep learning and statistical approaches.

## Future Enhancements

- Fine-tune hyperparameters for better model optimization.

- Explore attention mechanisms in LSTM models.

- Implement reinforcement learning for adaptive forecasting.

## Contributors

- Outhai Xayavongsa (Ms. Thai) – Machine Learning & AI Lead.

- Aaron Ramirez – Model Optimization & Research Lead.

## License

- The software is licensed under Apache License 2.0.

- The dataset follows the Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.
