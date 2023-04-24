# Analysing-Sensor-Data-to-Detect-Stress-A-Case-Study-Using-Wearable-Technology
1. Folders to be created in Google Drive:
    1. Main folder : Data Science
    2. Sub folder1 : Data Science/extract
    3. Sub folder2 : Data Science/Users
 2. Stress-Predict-Dataset-main.zip has to be placed in folder structure : Data Science/Stress-Predict-Dataset-main.zip
 3. Above folders have to be created and Stress-Predict-Dataset-main.zip file has to be placed in respective file path
 4. Stress_Predict_Dataset_EDA.ipynb file has to be run - This file contains
     1. Data preparation steps(gets the raw data file and combine it),
     2. Data preprocessing
     3. Visualization
     4. Data set is prepared for all the participants
     5. Data of each participant is written into .csv file and placed in filepath : Data Science/Users/
 5.stress_predict_model_deployment_code.py file has to be run - This file contains
      1. Reads the .csv files from path Data Science/Users/ for all participants
      2. Common functions to train,test and evaluate models : Randomforest and BLSTM
      3. Execution: Run the execute1('blstm',users,1) for required model and for required number of users.
