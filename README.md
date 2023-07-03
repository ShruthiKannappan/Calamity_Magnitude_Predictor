# Calamity_Magnitude_Predictor

Comments/Explanation present along with landslides.ipynb notebook.

Dataset used is Landslides.csv 


Run all the cells in colab after uploading the dataset


Section: Pipelines using SKlearn is generic for any calamity data,and any classification 

The trained pipelines can be stored in binary format by using pickle or joblib library


Eg


import joblib


joblib.dump(model,"model.joblib")


model can be loaded back from files as well
Eg

model_load=joblib.load("model.joblib")

