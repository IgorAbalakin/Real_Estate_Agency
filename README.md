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

In this part of the project, you need to perform:

        1. Research data;
        2. Search for patterns that allow us to formulate preliminary hypotheses about which factors are decisive for the trip duration;
        3. Creating visualizations that illustrate this study.

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)
 
____
### Machine learning modelling results


| Algorithm        | Training sample score          | Testing sample score  |
| ---------------- |:----------------------:| :-----:|
|  LinearRegression | 52,84 % | 53,80 % |
|  PolynomialFeatures | 42,77 %    |   43,68 % |
|  Ridge | 52,84 %    |   53,80 % |
|  Lasso | 54,93 %    |   56,00 % |
|  DecisionTreeRegressor    | 0,82 %     |   8,28% |
|       |      |     |
|  RandomForestRegressor    | 5,35%      |   8,28% |
|  GradientBoostingRegressor| 3,22%      |   9,90% |
|  StackingRegressor    | 4,65%      |   7,92% | 
|       |      |     |
|  XGBRegressor    | 7,84%      |   10,97% | 
|  CatBoostRegressor    | 9,02%     |   11,85% | 
|  LGBMRegressor    | 9,47%      |   12,68% | 

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)
  ____
  
### Data used in the project that couldn't be placed in the GitHub repository

[File with a training sample](https://drive.google.com/file/d/1X_EJEfERiXki0SKtbnCL9JDv49Go14lF/view?usp=sharing)

[Data files from OSRM for trips from the training table](https://drive.google.com/file/d/1ecWjor7Tn3HP7LEAm5a0B_wrIfdcVGwR/view?usp=sharing)

[File with a test sample](https://drive.google.com/file/d/1C2N2mfONpCVrH95xHJjMcueXvvh_-XYN/view?usp=sharing)

[Data files from OSRM for trips from the test table](https://drive.google.com/file/d/1wCoS-yOaKFhd1h7gZ84KL9UwpSvtDoIA/view?usp=sharing)

:arrow_up: [up to content](https://github.com/IgorAbalakin/Real_Estate_Agency/blob/main/README.md#Content)
  ____
