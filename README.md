#### 3.2 Multivariable Statistical Regression Analysis and Eutrophication Forecasting Model of Nutrient Flux Delivery to the Gulf of Mexico

##### ABSTRACT:
Recently, excessive amounts of nutrients due to human activity in the Midwestern United States discharge into the Gulf of Mexico through the tributaries of the Mississippi River. These excessive amounts of nutrients have contributed to significant changes in the Gulf’s ecosystems. Eutrophication phenomena in the Gulf of Mexico were first recorded in the early 1970s, which originally occurred every 3 years (Elser & Bennett, 2011). However, eutrophication now occurs annually and the dead zone area is achieving 8,776 square miles (Konopacky & Ristino, 2017). Therefore, the development of a sophisticated water quality model is an urgent priority for eutrophication control and prediction. 

However, a practical model for eutrophication control and prediction is very difficult due to a complex nonlinear relationship between water quality responses of eutrophication and water parameters (e.g., nutrient loadings, flowrate) in marine ecosystems. In addition, these parameters have an impact on each other and the highly nonlinear relationship between eutrophication and various water parameters is still unknown due to the lack of background information. Therefore, to overcome the difficulties in modeling of non-linear water systems, an appropriate approach for assessing and forecasting future eutrophication in a local aquatic environment is to use a multivariable regression model. In this study, 10 water quality parameters including temperature (C), dissolved oxygen (DO), pH, salinity (S), average flow (Q), elevated nitrate (N), total nitrogen (TKN), total phosphorus (TP), dissolved orthophosphate (OrthoP), dissolved silicon (DS) are selected to implement the multiple linear regression (MLR) analysis of nutrient flux delivery to the Gulf of Mexico. A principal component regression (PCR) followed by multiple linear regression then is applied to develop an MLR model to predict phytoplankton and zooplankton abundances which is the fundamental index of eutrophication.

	Dataset used in this study:
	https://toxics.usgs.gov/hypoxia/mississippi/nutrient_flux_yield_est.html
	https://toxics.usgs.gov/hypoxia/mississippi/real_time.html

![Screenshot](https://github.com/jr198868/Ran-Raymond-Jing-CV/raw/master/materials/Graphic_abstract_3.jpg)

##### Standard of Procedure:

	Step 1: Data cleaning and normalization
	Step 2: Extract variables
	step 3: Defines the number of observations and regressors 
	Step 4: Create a matrix of 1s with the dimensions defined above
	Step 5: Populate the matrix columns with regressors 
	Step 6: Create an ordinary least squares model
	Step 7: Extract the constants
	Step 8: Calculate the model fit result
	Step 9: Check the model residuals: Actual - prediction = residuals
	Step 10: Defines the number of observations and regressors 
	Step 11: Create a multilinear regression model to predict the dead zone area of the Mississippi River and the Gulf of Mexico

##### This project is still ongoing! More microbial community and nutrient data will be collected from the United States Geological Survey (USGS) to determine microbial community patterns affecting by the nutrient dynamics by using multilinear regression analysis. 



