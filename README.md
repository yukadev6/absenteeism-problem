This is a case study for developing a model that will predict the probabilty of an individual being excessively absent from work. 
After preprocessing the data, building a logistic regression model, and loading it as a Python module, the model is used to make predictions with new data.

How to use and run the Jupyter Notebook files
1. Create a local folder in a location where the entire repo can be cloned.
2. Open terminal and navigate to that new folder (local repo)
3. Run this command in terminal: git clone https://github.com/yukadev6/absenteeism-problem.git
4. Open Google Drive and upload the entire cloned local repo.
5. Open the Absenteeism_preprocessing.ipynb and it will open in Google Colab.
6. Upload the Absenteeism_data.csv to the current session files and then under Runtime, select "Run all" and this will produce the Absenteeism_preprocessed.csv file.
7. Download the Absenteeism_preprocessed.csv from the session files to the local repo to be used in the next step.
8. Open the Absenteeism_logistic_reg.ipynb and upload the Absenteeism_preprocessed.csv to the current session files.
9. Under Runtime, select "Run all" and this will produce the model and scaler.
10. Download the model and scaler from the session files to the local repo to be used in the next step.
11. Open the Absenteeism_integration.ipynb and upload the Absenteeism_new_data.csv, absenteeism_module.py, model, and scaler to the current session files.
12. Under Runtime, select "Run all" and this will produce the Absenteeism_predictions.csv file.
13. Download the Absenteeism_predictions.csv file from the session files to the local repo.
