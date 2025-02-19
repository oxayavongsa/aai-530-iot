# Smart Home Energy Predictions: EDA Branch
AAI-530 IoT and Machine Learning Final Project

University of San Diego, School of Engineering - Masters of Applied Artificial Intelligence

## Project Overview

This branch focuses on Exploratory Data Analysis (EDA) and data preprocessing for smart home energy prediction. The project involves cleaning, transforming, and analyzing IoT sensor data to extract meaningful insights that support predictive modeling.

## Project Components

- Data Processing & Feature Engineering

### Data Cleaning:

  - Handling missing values and outlier detection.

  - Standardizing timestamp formats and merging multiple sensor sources.

### Feature Engineering:

  - Creating rolling averages, barometric deltas, and temperature derivatives.

  - Generating new predictive variables for enhanced model performance.

## Notebooks Included

- ```EDA.ipynb``` – Primary exploratory data analysis, cleaning, and preprocessing.

- ```EDA2.ipynb``` – AI model outline and feature selection.

## Data Files

- Cleaned IoT sensor datasets for modeling:

- ```data/EcoLab_Ground_Cleaned.csv```

- ```data/Front_Door_Cleaned.csv```

- ```data/Weather_Link_Indoor_Cleaned.csv```

## Installation & Dependencies

To install the required dependencies, run:

```pip install -r requirements.txt```

Ensure requirements.txt is included in the project directory to set up the environment.

## How to Use

Clone the repository:

```git clone -b ds-eda https://github.com/oxayavongsa/aai-530-iot-smart-house.git```

Install dependencies:

```pip install -r requirements.txt```

## Run Jupyter Notebook:

Open and execute ```EDA2.ipynb``` in Jupyter or Google Colab.

## Explore Results:

Analyze statistical summaries, trends, and feature correlations.

## Google Colab Notebook

To explore the code, open the Jupyter Notebook in Google Colab:

<a href="https://colab.research.google.com/github/oxayavongsa/aai-530-iot-smart-house/blob/main/EDA.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
</a>

## Key Findings

- Identified correlations between temperature, humidity, and barometric pressure.

- Filtered and cleaned noisy sensor readings to improve model accuracy.

- Generated additional features that boost predictive model performance.

## Future Enhancements

- Automate data-cleaning pipelines using Python scripts.

- Implement anomaly detection techniques for sensor drift.

- Incorporate additional environmental variables for richer predictions.

## Contributors

- Outhai Xayavongsa (Ms. Thai) – Team Lead

- Aaron Ramirez – Tech Lead

## License

- The software is licensed under Apache License 2.0.

- The dataset follows the Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license.

For further details, refer to the original README file in the main branch.
