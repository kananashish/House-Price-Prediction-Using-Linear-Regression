# House Price Prediction using Linear Regression

## Overview
This project aims to predict house prices using a **Linear Regression Model** trained on the **California Housing Dataset**. The dataset contains various features like median income, house age, and location-based metrics to estimate housing prices in different regions of California.

## Dataset
The dataset used in this project is the **California Housing Dataset**, which is available in Scikit-learn. It consists of:
- **Features:**
  - `MedInc`: Median income in the area
  - `HouseAge`: Average age of houses in the area
  - `AveRooms`: Average number of rooms per dwelling
  - `AveBedrms`: Average number of bedrooms per dwelling
  - `Population`: Population in the area
  - `AveOccup`: Average number of occupants per household
  - `Latitude`: Geographical latitude
  - `Longitude`: Geographical longitude
- **Target:**
  - `MedHouseVal`: Median house value in the area

## Project Structure
```
├── data/                  # Dataset (if applicable)
├── notebooks/             # Jupyter notebooks for analysis and modeling
├── src/                   # Source code for model training and evaluation
│   ├── data_processing.py # Data preprocessing scripts
│   ├── model.py           # Model training and evaluation scripts
│   ├── utils.py           # Helper functions
├── results/               # Outputs, predictions, and model evaluations
├── README.md              # Project documentation
└── requirements.txt       # Dependencies required to run the project
```

## Installation
To run this project locally, ensure you have Python installed and follow these steps:

```bash
# Clone the repository
git clone https://github.com/kananashish/house-price-prediction.git
cd house-price-prediction

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

## Usage
1. **Load and preprocess the dataset:** Run `data_processing.py` to clean and prepare the dataset.
2. **Train the model:** Execute `model.py` to train a Linear Regression model.
3. **Evaluate the model:** Check results in the `results/` directory.

Run the script:
```bash
python src/model.py
```

## Results
The trained model provides predictions for house prices based on input features. Performance metrics such as **Mean Squared Error (MSE)** and **R² Score** are used to evaluate the model.

## Future Improvements
- Implementing **feature engineering** to enhance model performance.
- Trying other **regression models** like Decision Trees, Random Forest, and XGBoost.
- Deploying the model as a **web API** for real-time predictions.

## Author
**Ashish Kanan**  
[GitHub](https://github.com/kananashish) | [LinkedIn](https://www.linkedin.com/in/ashishkanan/) | [Twitter](https://x.com/kanan_ashish)

## License
This project is open-source and available to everyone.
