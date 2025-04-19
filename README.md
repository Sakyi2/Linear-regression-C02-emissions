# Linear-regression-C02-emissions
this project uses linear regression to explore and predict C02emissions of vehicles
CO2 Emissions Prediction with Linear Regression

Project Description

This project uses linear regression to explore and predict CO₂ emissions of vehicles based on their engine size.
The goal is to understand the relationship between a car’s engine size and the amount of CO₂ it emits.

We use Python libraries like pandas, matplotlib, and scikit-learn to perform data exploration, visualization, and model building.

⸻

Dataset
	•	Dataset used: FuelConsumptionCo2.csv
	•	Features used:
	•	ENGINESIZE — Size of the vehicle engine (in liters)
	•	CO2EMISSIONS — Carbon dioxide emissions (in grams per kilometer)

⸻

Project Structure
	•	work.ipynb — Jupyter Notebook containing all the code (data loading, visualization, model training).
	•	FuelConsumptionCo2.csv — Dataset file (if you upload it too).

⸻

Requirements

You can install the necessary libraries by running:
pip install pandas matplotlib scikit-learn

Steps Performed
	1.	Import Libraries
Import pandas, matplotlib.pyplot, and scikit-learn.
	2.	Load the Dataset
Load the .csv file using pandas.
	3.	Data Exploration
Plot a scatter plot of ENGINESIZE vs CO2EMISSIONS.
	4.	Model Training
Train a simple linear regression model to predict CO2 emissions from engine size.
	5.	Visualization
Plot the regression line on top of the scatter plot.
	6.	Evaluation
Evaluate the model using metrics like Mean Absolute Error (optional if you extend it).


