# Outlet Sales Predictions

Shar Clark

## Analyzing Outlet Sales

### Data
  - For this data set, there were 10 columns and 8523 rows. 

**Exploratory Data Analysis**
   - During EDA, a histogram and a heatmap were visualized for the data set. The histogram showed the most common weight of the items. The heatmap showed the correlations between columns.
   -  This gave us direction on what column relationships to study further. Item MRP and outlet sales had the highest positive correlation.
  
 [INSERT HEATMAP]
 
 **Explanatory Data Analysis**
   - In order to visualize the data, I created two bargraphs. One comparing outlet sales to outlet types. I concluded that the Medium sized stores had the highest sales. I took a closer look at medium sized stores and noticed that visibility had a direct correlation to higher outlet sales.
  
  [INSERT STACKED GRAPH]
  
  ### Machine Learning using the following models:
   - Linear Regression Model
   - Decision Tree Model
   
 ### Models Evaluated and Results
 
 - Decision Tree Model Train Scores
    - MAE: 762.6251 
    - MSE: 1,172,123.3890 
    - RMSE: 1,082.6465 
    - R2: 0.6039

- Decision Tree Model Test Scores
  - MAE: 738.4420 
  - MSE: 1,118,204.8984 
  - RMSE: 1,057.4521 
  - R2: 0.5947

- Linear Regression Train Scores
  - MAE: 917.9871 
  - MSE: 1,485,004.0542 
  - RMSE: 1,218.6074 
  - R2: 0.4982

- Linear Regression Test Scores
  - MAE: 872.6103 
  - MSE: 1,370,832.4401 
  - RMSE: 1,170.8255 
  - R2: 0.5031
  
I would reccomend using the Decision Tree Model, when compared to the Linear Regression Model. The RMSE is lower for the Decision Tree Model and the R2 is higher.

Both models had some bias, but the Decision Tree model outperformed the Linear Regression model. 

### Recommendations
  - **Outlet Sales Insights**
    - The medium sized outlet had the highest sales, compared to the other sized stores. When we looked closer at the medium sized outlets, we saw that they had a lot more visibility with their products. We reccommend increasing the visibility across other stores in order to increase sales.
