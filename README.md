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
<div class='tableauPlaceholder' id='viz1739947775986' style='position: relative'><noscript><a href='#'><img alt=' ' src='https://public.tableau.com/static/images/Fi/FinalPredictions/IoTSmartHomeDashboard/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalPredictions/IoTSmartHomeDashboard' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https://public.tableau.com/static/images/Fi/FinalPredictions/IoTSmartHomeDashboard/1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1739947775986');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} 
    else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} 
    else { vizElement.style.width='100%';vizElement.style.minHeight='1650px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';} 
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

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
