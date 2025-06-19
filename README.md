##✈️ Flight Delay Analysis & Prediction
           This project focuses on analyzing the causes of flight delays using historical airline performance data and building a predictive model to classify whether a flight will be delayed. It combines data cleaning, exploratory analysis, feature engineering, and classification modeling.

📁 Dataset
           Source: [Airline Delay Cause Dataset]

          Rows: ~179,000

          Columns: 21

          Key columns include:

          year, month

          carrier, carrier_name, airport

          Delay breakdowns: carrier_delay, weather_delay, nas_delay, security_delay, late_aircraft_delay

          arr_flights, arr_del15 (delays over 15 minutes)

🧠 Objectives
Understand delay patterns by airline, month, and delay cause.

Preprocess and encode features.

Build classification models to predict if a flight will be delayed.

Evaluate models using metrics like accuracy, F1, and AUC-ROC.



📊 EDA Highlights
Delay distributions across months and carriers.

Contribution of different delay types to total delay.

Correlation analysis between delays and number of flights.

⚙️ Modeling
Preprocessing: Label encoding, scaling with StandardScaler.

Models Used:

Logistic Regression

Random Forest Classifier

Validation:

5-Fold Stratified Cross-Validation

Evaluation metrics: accuracy, precision, recall, F1, F2, AUC
