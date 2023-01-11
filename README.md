# Real Estate Agency (house price prediction) 

### Content
[1. Project Description](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Project-Description) 

[2. Data overview and basic analysis](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Data-overview-and-basic-analysis) 

[3. Data cleaning](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Data-cleaning) 

[4. Exploration Data Analysis (EDA)](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Exploration-Data-Analysis-EDA) 

[5. Machine learning modelling results](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Machine-learning-modelling-results) 

[6. Data used in the project that couldn't be placed in the GitHub repository](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Data-used-in-the-project-that-couldnt-be-placed-in-the-GitHub-repository) 
 
____
### Project Description 

*Business task*: to determine the characteristics for quickly estimating the value of a real estate object, without wasting time sorting ads and searching for profitable offers, that would allow to bypass competitors in terms of speed and quality of transactions.

*Technical task*: to create a machine learning model that based on the proposed features of a real estate object will predict its value..
 
:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)

 ____
### Data overview and basic analysis

        status - type of deal (sale, lease, etc.)
        private pool - having own private swimming pool (duplicated feature)
        propertyType - property type (house, apartment, single family, and so on) 
        street - street name
        baths - number of baths
        homeFacts - information about heating, air conditioning, year of construction, repairs, parking availability
        fireplace - fireplace information
        city - city name
        schools - information about the number of schools, their rating, distance from the property
        sqft - living space
        zipcode - zipcode
        beds - number of beds
        state - abbreviation of the state
        stories - number of stories  
        mls-id - MLS ID (duplicated feature)     
        PrivatePool - having own private swimming pool (duplicated feature)  
        MlsId - MLS ID (duplicated feature)          
        target - target value, house price


:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)

____
### Data cleaning

       1. Removing duplicates
       2. Filling in gaps (medians and modes)
       3. Removal of emissions in two stages: by the three sigma method and the Tukey method
       4. Removal of correlated features

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)

 ____
### Exploration Data Analysis (EDA)

In this part of the project, we need to perform:

        1. Research data
        2. Search for patterns that allow us to formulate preliminary hypotheses about which factors are decisive for the trip duration
        3. Create visualizations that illustrate this study.

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)
 
____
### Machine learning modelling results


| Algorithm        | Training sample score          | Testing sample score  |
| ---------------- |:----------------------:| :-----:|
|  LinearRegression | 52,84 % | 53,80 % |
|  PolynomialFeatures | 42,77 %    |   43,68 % |
|  Ridge | 52,84 %    |   53,80 % |
|  Lasso | 54,93 %    |   56,00 % |
|  DecisionTreeRegressor    | 0,82 %     |   8,02% |
|       |      |     |
|  RandomForestRegressor    | 5,41%      |   8,35% |
|  GradientBoostingRegressor| 2,45%      |   10,31% |
|  StackingRegressor    | 4,77%      |   8,01% | 
|       |      |     |
|  XGBRegressor    | 8,00%      |   11,02% | 
|  CatBoostRegressor    | 8,93%     |   11,61% | 
|  LGBMRegressor    | 12,24%      |   13,89% | 

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)
  ____
  
### Data used in the project that couldn't be placed in the GitHub repository

[All the data](https://drive.google.com/uc?id=11-ZNNIdcQ7TbT8Y0nsQ3Q0eiYQP__NIW&export=download)

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)
  ____
