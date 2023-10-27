# Forecasting the Most Profitable Oil Production Region

## Project Description
Data on oil samples in three regions and characteristics for each well in the region are provided.  
The goal is to build a model to determine the region with the highest profit potential.  

## Key Findings
A model was trained and tested for each region, and the average predicted oil reserve and RMSE of the model were determined.  
The minimum required oil volume for profitable development of a new well was calculated.  
A comparison was made between the obtained oil volume and the average reserve in each region.  
A function was created to calculate profit based on selected wells and model predictions.  
Wells with the highest prediction values were chosen.  
Profit was calculated for the obtained oil volume.  
Risks and profit for each region were calculated using Bootstrap with 1000 samples to find the profit distribution.  
The average profit, 95% confidence interval, and risk of losses were determined.  

The best region was identified with a risk of loss below 2.5%.  

## Additional Information
Toolkit: Pandas, Matplotlib, Python, Scikit-learn.
