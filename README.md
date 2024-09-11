# Traffic Density Prediction Web App

## Overview

This web app uses a pre-trained Random Forest model to predict traffic density based on various input parameters. The app is built with Streamlit and allows users to input different features and receive a prediction of traffic density.

## Features

- **City**: Choose from a list of cities.
- **Vehicle Type**: Select the type of vehicle.
- **Weather**: Select the weather condition.
- **Economic Condition**: Choose the economic condition.
- **Hour Of Day**: Select the hour of the day (0-23).
- **Day Of Week**: Choose the day of the week.
- **Speed**: Enter the speed of the vehicle.
- **Is Peak Hour**: Indicate if it is a peak hour (0 or 1).
- **Random Event Occurred**: Specify if a random event occurred (0 or 1).
- **Energy Consumption**: Enter the energy consumption value.

## How to Use

1. **Select the Parameters**: Choose the values for each input field from the dropdowns, slider, and number input fields.
2. **Predict Traffic Density**: Click on the 'Predict Traffic Density' button to get the prediction based on the input parameters.
3. **View the Result**: The predicted traffic density will be displayed below the button.

## Setup

To run the app locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GhufranBarcha/Traffic-density-prediction-webapp
   cd Traffic-density-prediction-webapp
