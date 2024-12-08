# Crop Recommendation System

### Project Description
The Crop Recommendation System is an intelligent application that helps farmers and agricultural professionals determine the most suitable crop to grow based on environmental conditions and soil properties. This system leverages data analysis and machine learning to provide accurate recommendations, enabling better decision-making in farming practices.

### Features
Predict the best crop for a given soil and environmental condition.
Input parameters include nitrogen, phosphorus, potassium, temperature, humidity, ph level, and rainfall.
Uses a trained machine learning model for precise predictions.
Easy-to-use interface for input and results visualization.
Helps increase agricultural efficiency and productivity.

#### Technologies Used
Programming Language: Python

Libraries:
Pandas, NumPy for data processing
Scikit-learn for machine learning
Matplotlib, Seaborn for data visualization
Tkinter (if UI is built)

Machine Learning Model: Random Forest Classifier/Logistic Regression

###  How It Works
1. Data Collection:
The system uses a dataset containing soil and environmental parameters along with the most suitable crop for those conditions.

2. Data Preprocessing:
Handles missing values and encodes categorical variables.
Normalizes the input features for better model performance.

3. Model Training:
Machine learning algorithms like Random Forest are trained on the dataset to classify the best crop for given inputs.

4. Prediction:
User inputs soil and environmental parameters into the system.
The system outputs the best crop recommendation.

## Dataset

####The dataset includes the following features:
Nitrogen, Phosphorus, Potassium (NPK) Levels
Temperature (°C)
Humidity (%)
Ph Level
Rainfall (mm)

Target Variable: Recommended Crop

## Installation Steps

#### Follow these steps to set up the project on your local machine:

1. Clone the repository:
git clone https://github.com/YourUsername/Crop-Recommendation-System.git
cd Crop-Recommendation-System

2. Install required libraries:
pip install -r requirements.txt

3. Run the application:
python app.py

4. Enter the required parameters to get crop recommendations.

## Usage

Input soil and environmental conditions via the system's interface or command line.
Click the "Predict" button to see the recommended crop.

## Output

The system predicts the most suitable crop for the given conditions.
For example:
Input: Nitrogen = 40, Phosphorus = 50, Potassium = 60, Temperature = 25°C, Humidity = 80%, pH = 6.5, Rainfall = 100 mm.
Output: Recommended Crop = Wheat

### Project Files
app.py: Main application file for running the system.
crop_dataset.csv: Dataset used for training the model.
model.pkl: Pre-trained machine learning model.
requirements.txt: List of required libraries.

## Screenshots


![Crop_Prediction1](https://github.com/user-attachments/assets/742c85cf-9a71-4ac6-a568-df93094a9c78)




![Crop_Prediction2](https://github.com/user-attachments/assets/b86d20d5-9082-4cca-b551-bc20545bc818)


##### Future Enhancements

Include real-time weather data integration.
Add more detailed soil analysis.
Support for multiple languages for better accessibility.
