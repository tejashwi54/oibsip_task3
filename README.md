# oibsip_task3

# Car Price Prediction with Machine Learning 🚗💰  

## Overview  

This project predicts the selling price of used cars using machine learning techniques. It considers various factors such as the car's brand, fuel type, transmission, and other specifications to make accurate price predictions.

## Dataset  

The dataset includes features like:

- **Car_Name**: Name of the car

- **Year**: Year of manufacturing

- **Selling_Price**: Price at which the car was sold (Target variable)

- **Present_Price**: Current showroom price

- **Driven_kms**: Kilometers driven by the car

- **Fuel_Type**: Type of fuel used (Petrol/Diesel/CNG)

- **Selling_type**: Individual or dealership sale

- **Transmission**: Manual or Automatic

- **Owner**: Number of previous owners

## Dependencies  

Ensure you have the following Python libraries installed:

pip install pandas numpy scikit-learn matplotlib seaborn

## How to Run  
1. Clone this repository:  

   git clone https://github.com/your-username/Car-Price-Prediction.git
   
2. Navigate to the project directory:  
   
   cd Car-Price-Prediction
   
3. Run the script:  
   
   python src/car_price_prediction.py


## Model Used  

The project uses **Linear Regression** for predicting car prices. The model is evaluated using metrics like:

- Mean Absolute Error (MAE)

- Mean Squared Error (MSE)

- Root Mean Squared Error (RMSE)

- R² Score

## Results  

The model predicts car prices with reasonable accuracy. Future improvements include advanced feature selection, hyperparameter tuning, and exploring other models like Random Forest or XGBoost.

## Folder Structure  

Car-Price-Prediction/

│── src/               # Python scripts (main code files)

│── requirements.txt   # Dependencies

│── .gitignore         # Ignore unnecessary files (like .csv, .env)


## Contributing  
Feel free to fork this repository, improve the model, and submit pull requests!

## License  
This project is open-source and you are welcome to make changes as per your choice.

