# DPS AI Challenge

## Creation of AI Accident Forecasting model

To forecast the number of accidents per category, three models were used: Prophet, SARIMA, and LSTM. Based on the Root Mean Square Error (RMSE) scores, SARIMA was selected as the final model. For training, the accident type was fixed as 'insgesamt', and for all models, the model trained on the category 'Alkoholunfälle' was saved. Visualizations generated using each model can be found [here](https://github.com/RakhiNair/AI_Challenge/blob/main/AI_Prediction_Model.ipynb).

## Model Deployment
The SARIMA-based Accident Forecasting model is deployed in Hugging Face Spaces. You can access the prediction API [here](https://rakhinair-accident-forecasting.hf.space/predict).



