# CarPrice-Analysis
Customer Demographic Analysis for new product launch in Automobile sector.
## Objectives 

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. 

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know:
 - Which variables are significant in predicting the price of a car
 - How well those variables describe the price of a car

### Business Goal 

We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to understand the pricing dynamics of a new market.

### Data Understanding

The source data given contains the information about different types of cars across the American market. 

## Analysis 

#### 1. Importing and Understanding Data
 - Imported the dataset
 - Shape and Type of columns in dataset
 - Statistical Information about dataset
#### 2. Data Cleaning and Preparation using Exploratory Data Analysis (EDA)
 - Derived new columns CompanyName and Power to Weight Ratio
 - No missing values and duplicate values in dataset
 - Dropped Car ID column as it will not be useful in our further analysis
 - Standardized all String column values by converting them to Uppercase
 - Converted Categorical variables to numeric variables to support Linear Regression Analysis
 - Rescaled the variables by applying normalize function
 - Corrected Spelling mistakes in Car Name column
 - Univariate and Bivariate Analysis by plotting graphs
 #### 3. Splitting data into training and testing sets
 #### 4. Linear Regression using Recursive Feature Elimination
 #### 5. BootStrap Technique used to resample and create a large dataset for Model prediction
 
 ## Conclusion
 
 ### Model Results Summary
 After evaluating various models, we have identified the following variables as most significant variables to predict car price in US market.
 - enginesize
 - CarName_BMW
 - CarName_BUICK
 - CarName_PORSCHE
 
 So to conclude, Geely should consider enginesize while designing the cars and it should follow the business strategy of BMW, BUICK, PORSCHE to meet certain price levels.

<b> Please note that based on the domain we felt that there is no need to take any action in outliers. If we have taken any action in outliers, the model accuracy might have changed.</b>
