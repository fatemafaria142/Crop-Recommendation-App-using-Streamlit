# Crop Recommendation using Machine Learning Algorithms

This project focuses on recommending suitable crops to grow in a particular farm for cultivation based on various environmental factors. The dataset used for this analysis is available on [Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset).

## Dataset Details

The dataset is created by augmenting rainfall, climate, and fertilizer data available for India. It includes the following key fields:

- **N (Nitrogen):** Ratio of Nitrogen content in soil
- **P (Phosphorous):** Ratio of Phosphorous content in soil
- **K (Potassium):** Ratio of Potassium content in soil
- **Temperature:** Soil temperature in degrees Celsius
- **Humidity:** Relative humidity in percentage
- **pH Value:** pH value of the soil
- **Rainfall:** Amount of rainfall in millimeters
  
## Model Performance

| Model                               | Accuracy | Precision | Recall  | F1 Score |
| ----------------------------------- | -------- | --------- | ------- | -------- |
| LGBMClassifier | 0.9932   | 0.9937    | 0.9932  | 0.9932   |
| XGBoost    | 0.9932   | 0.9935    | 0.9932  | 0.9931   |




# Crop Recommendation App using Streamlit

![Crop Recommendation App](crop_recommendation_1.PNG) ![Crop Recommendation App](crop_recommendation_2.PNG)

This is a simple web application built with Streamlit that provides crop recommendations based on user input. The app takes into account various factors such as soil type, temperature, humidity, and rainfall to suggest suitable crops for cultivation.

## Features
- **User-friendly Interface:** The app offers an intuitive and easy-to-use interface for users to input relevant information.
- **Data-Driven Recommendations:** Crop recommendations are generated using a data-driven approach, considering key environmental factors.
- **Real-time Results:** Instantly view the recommended crops along with additional details such as planting season and soil requirements.

## Try it out!
Visit the Crop Recommendation App [here](https://crop-recommendation-app-bd.streamlit.app/) to explore the functionalities and receive personalized crop recommendations.

