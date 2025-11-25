<h1>Sweet Lift's Taxi Orders Forecasting</h1>















<h2>Description</h2>



Sweet Lift Taxi Company has collected historical data on taxi orders at airports. The goal of this project is to predict the number of taxi orders for the next hour, which will help the company attract more drivers during peak hours and improve operational efficiency.



The model’s performance is evaluated using Root Mean Squared Error (RMSE), and the target is RMSE ≤ 48 on the test dataset.



<b>Dataset</b>

- Target column - num\_orders

- Resample data by one hour







<h2>Project Overview</h2>



- <b>Data preprocessing</b> 

	- Load and inspect the dataset

	- Handle missing values

	- Resample data by one-hour intervals



- <b>Exploratory Data Analysis</b> 

	- Analyze trends and patterns in taxi orders

	- Visualize hourly, daily and monthly patterns

	- Identify peak times and seasonal trends





- <b>Model Training</b> 

	- Split dataset: 90% training, 10% test

	- Train multiple models with hyperparameter tuning

	- Compare models to find the best performing one





- <b>Model Evaluation</b> 

	- Ensure RMSE ≤ 48









<h2>Models & Tools</h2>


- ARIMA

- Auto Regression

- Python

- Pandas

- NumPy

- Matplotlib

- Skikit-learn

- VS Code













<h2>Data Visualizations</h2>




<br/>


<p align="center">


<img src="https://imgur.com/vAcSDpC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<br/>

<h3>Seasonal trends decompressed</h3>

- First graph shows seasonal patterns throughout the month of April 2018 

- Second graph shows seasonal patterns from April 1st 2018 - April 7th 2018

- Third graph shows seasonal patterns from June 10th 2018 - June 27th 2018


<img src="https://imgur.com/59Y2Hpr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<br/>

<h3>Trend, Seasonal and Residual graphics from March 1st 2018 - August 31st 2018</h3>


<img src="https://imgur.com/JU0Yvv2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<br/>

<h3>Seasonal patterns decompressed from August 9th 2018 - August 11th 2018 </h3>

This graph (along with the other above) shows a clear pattern of taxi orders spiking around midnight daily.

<img src="https://imgur.com/KMaHzsF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>








</p>








