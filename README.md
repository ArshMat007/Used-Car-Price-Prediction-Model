# Used Car Price Prediction

The project aims to develop an XGBoost Regressor model to accurately predict used car prices based on features like age, mileage, engine size, and fuel type. This tool
assists customers in making informed decisions, negotiating prices, gaining market insights, and saving time
Project Title: AlertPal

## Features
- Built using Streamlit for an interactive web application.
- Utilizes a machine learning model trained on the Cardekho dataset.
- Predicts car prices based on user input.

## Installation
To set up and run the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   streamlit run app1.py
   ```

## Dependencies
Ensure you have the following Python packages installed:
- `pandas`
- `numpy`
- `pickle`
- `streamlit`

## Files in This Repository
- **`app1.py`** - The main Streamlit application.
- **`model.pkl`** - Pre-trained ML model for car price prediction.
- **`Cardekho Dataset.xlsx`** - The dataset used for training.
- **`car_pridct.ipynb`** - Jupyter notebook for data analysis and model training.
- **`README.md`** - This file.

## Usage
1. Launch the Streamlit app.
2. Select the car details from the available options.
3. Click the "Predict" button to get the estimated price.

## License
This project is licensed under the MIT License.

## Acknowledgments
- The dataset is sourced from the **CarDekho** dataset.
- Built with Streamlit for easy deployment and user interaction.

