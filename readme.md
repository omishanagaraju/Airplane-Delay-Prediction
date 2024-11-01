# Flight Delay Prediction

This repository contains the code for predicting flight delays based on various features, such as departure time, airline, and distance.

This project leverages machine learning to predict flight delays, aiming to improve customer experience on a travel booking platform. Using a dataset of domestic flight performance from 2014 to 2018, the code includes building models to identify if a flight will likely be delayed due to weather.

The project is structured as follows:

1. Data Processing: Extracts and combines monthly CSV files from a ZIP dataset containing U.S. domestic flight records.
2. Exploratory Data Analysis (EDA): Conducts initial data exploration to understand delay patterns, identify critical features, and detect trends across the busiest U.S. airports, available at- https://public.tableau.com/app/profile/omisha.nagaraju/vizzes.
3. Baseline & Model Improvement: Establishes a baseline prediction model, iteratively enhancing performance to improve delay predictions.

The data is sourced from the Bureau of Transportation Statistics (BTS), Office of Airline Information, under the Airline On-Time Performance Data.

## How to Run the Code

### Prerequisites:
- Python 3.x
- Jupyter Notebook
- Virtual environment (optional but recommended)

### Steps to Run:

1. Clone the repository:
   git clone https://github.com/omishanagaraju/Airplane-Delay-Prediction
   
   cd airplane-delays-prediction
   
2. Install Requirements:
   pip install -r requirements.txt

3. Launch Jupyter Notebook:
   jupyter notebook
   
4. This will open Jupyter in your web browser. Navigate to the file flight_delay_prediction.ipynb and open it.

5. Downlaod the compressed data file "data_compressed.zip" from https://www.dropbox.com/scl/fi/g3psk5e2fm8yrp30utfcw/data_compressed.zip?rlkey=nrrejkmeibk0l9y0ditc1ook7&st=uhkg4h3x&dl=0 and save it in the same working directory as the python notebook file, all of the information about the data is available here- https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ.

6. Run the cells in the notebook to train and evaluate the model. You can run all the cells by selecting Cell -> Run All in the notebook menu.

# Flight Delay Prediction on Amazon Sagemeaker

The SageMaker code allows us to train, validate, and deploy machine learning models on Amazon's cloud platform. It automates parts of the ML pipeline, making it easier to handle large datasets, and manage models efficiently.

Replace the bucket name with your bucket name before the code is run.

