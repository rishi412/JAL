# JAL
Major Project - Water Quality Analysis and Prediction using Machine Learning 

Freshwater is a critical resource for agriculture and industry survival. Examining water 
quality is a fundamental stage in administering freshwater assets. It is critical to test the 
quality of water before involving it for any reason, whether it is for animal watering, 
chemical spraying (Pesticides, etc.), or drinking water. Water quality testing is a strategy for 
finding clean drinking water. This project is based on the arising problems of water quality 
which need to be solved every few years. In the first phase of the project, we gathered the 
whole raw data from the government’s official website and utilized it as per our 
requirements. Our project JAL describes not only the water quality but also other parameters 
that have an indirect relation with it without which the analysis and forecasting are 
incomplete. These evaluating parameters are Temperature, Biological Oxygen Demand, Total 
Suspended Solids, Dissolved Oxygen, and Conductivity. Using polynomial regression, we 
calculated the water quality using the mentioned parameters. The water quality index ranges 
from 0 to 100, with 100 indicating excellent water quality. However, this analysis was not 
sufficient enough to determine the actual impact factors for the quality of surface water so we 
analyzed environmental pollution in major industrial areas and also made a comparison 
between groundwater and river water quality of critically polluted areas. All the results of 
this analysis were displayed on our website ‘JAL’ so that users can understand it without any 
complications. In the second and last phase of our project, we created a machine learning 
model using XGBoost and Linear Regression to calculate the water quality index (WQI) 
using eight different evaluating parameters that are Dissolved Oxygen Saturation (%), pH, 
Biological Oxygen Demand, Temperature, Phosphate, Nitrate, Turbidity, and Total Solids. 
According to the research papers we read, these were the most important factors for 
determining surface water quality. This model is then deployed using Flask and connected to 
our ‘JAL’ website. Our model allows users to input the parameter values and the model will 
then display the WQI.

