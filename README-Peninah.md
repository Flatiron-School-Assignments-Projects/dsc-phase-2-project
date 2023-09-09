# Phase 2 Project

![Real Estate]([https://img.freepik.com/premium-photo/real-estate-sales-manager-giving-keys-customer-after-signing-rental-lease-contract_28283-1047.jpg?w=900))

# BUSINESS ANALYSIS OF HOUSE SALES IN KING COUNTY, WASHINGTON 
## AUTHORS: 
## <u>Group 24 Members</u>
1. Samuel Gichanga
2. Leonard Mwangi
3. Moses Thiong'o
4. Evangeline Ngunjiri

Part Time Data Science Program

Due date: 11/09/2023

Technical Mentor: Stella Waithera

![Forbes](https://imageio.forbes.com/specials-images/imageserve/62437975bb1b55afcd4ab6ab/real-estate-concept/960x0.jpg)

## PROJECT OVERVIEW

This project seeks build a data analytics model for a real estate agency that will help homeowners buy and/or sell homes in King County, Washington.

## BUSINESS PROBLEM

> King County, being the home of Seattle, the most advanced and populous city in Washington and the 13th most populous in the USA, has a competitive real estate industry.

>As such, there is a complex and dynamic relationship among many factors that affect the market value of real estate property. These factors include the weather season, the location of the property, the grade of the house, the presence of a scenic view, the number of floors, the age of the house, various dimensions such as the size of the interior living space, and the size of the lot.

>For a real estate firm, the challenge is to make informed pricing decisions that will account for all the complex interrelated factors. This can lead them to misadvise home buyers and sellers as well as unnecessary loss of business opportunities and reputation.

>Our project will seek to help real estate agencies make more informed and data-driven pricing strategies for homes in King County.
## BUSINESS UNDERSTANDING
**Specific Factors that Influence the Price of a Home in King County:**
1.	Location-specific conditions include traffic, freeway access, noise, crime, sun exposure, views, parking, neighboring homes, vacant lots, access to quality schools, parks, shops, restaurants.
2.	Condition - the overall condition of the house affects its market value.
3.	Grade is a classification by construction quality which refers to the types of materials used and the quality of workmanship. It is regulated by the King County Local government.
4.	Various dimensions in square feet, such as the size of the interior living space, the lot, the basement, as well the average dimension of neighboring houses.
5.	The number of bedrooms and bathrooms.
6.	Presence of a scenic view.
7.	The age of the house.
8.	If the house is old, whether it has ever been renovated.
## BUSINESS OBJECTIVES
To complete this project, our main business objectives will be the following:
To build a data analytics model for a real estate agency that helps homeowners buy and/or sell homes in King County, Washington.
To develop a model that will help in identifying the set of attributes that will realize the best value to a home buyer and optimal returns to the home seller.
To provide insight to homeowners and buyers about:<br>
i.) How weather seasons may affect the sales volume and mean sale price of homes in King County.<br>
ii.) How the grade of a house may affect the sales volume and mean sale price of homes in King County.<br>
iii.) How the number of bedrooms affect the sales volume and mean sale price of homes in King County.<br>
To find out whether there is a variation in sales volume and mean sale prices across different locations in King County.

## STUDY QUESTIONS
1. What is the relationship between weather season and sales performance?<br>
2. Which is the best weather season to buy a house?<br>
3. Which are the best performing house grades?<br>
4. What is the optimal range of a house grade for different budgets?<br>
5. What is the relationship between number of bedrooms and sales performance?<br>
6. What is the optimal range of bedrooms for different budgets?<br>
7. Which set of variables has the highest influence on the sale price of a house?<br>
8. How are the house prices and house sale volumes distributed around the county?
## DATA UNDERSTANDING
The dataset kc_house_data.csv, has 21,597 rows and 21 columns. Below is a description of the variables in the dataset.
| Column           | Description                                                                                       |
|------------------|---------------------------------------------------------------------------------------------------|
| **id**               | Identification for a house                                                                        |
| date             | Date house was sold                                                                               |
| price            | Sale price for a house, which is the target variable                                             |
| bedrooms         | Number of bedrooms                                                                                |
| bathrooms        | Number of bathrooms                                                                               |
| sqft_living      | Size of living area in square feet                                                                |
| sqft_lot         | Size of the lot in square feet                                                                    |
| floors           | Total number of floors (levels) in the house                                                      |
| waterfront       | '1' if the property has a view to a waterfront, '0' if not                                       |
| view             | A rating of Fair, Average, Good, Excellent depending on the view of the property                  |
| condition        | Overall condition of the house                                                                    |
| grade            | An index from 1 to 13 indicating the quality level of construction and design                     |
| sqft_above       | Square footage of the house excluding the basement                                               |
| sqft_basement    | Square footage of the basement                                                                    |
| yr_built         | Year the house was built                                                                          |
| yr_renovated     | Year when the house was last renovated. '0' if it has never been renovated                       |
| zipcode          | 5-digit zip code of the house                                                                     |
| lat              | Latitude coordinate                                                                               |
| long             | Longitude coordinate                                                                              |
| sqft_living15    | Average size of interior living space of the 15 closest houses, in square feet                    |
| sqft_lot15       | Average size of the land lots for the 15 closest houses, in square feet  

## METHODOLOGY
Execution of the project involved the following:

### Data Understanding and Cleaning
We explored the datasets to understand their schema, size, data types, and examine the presence of invalid or inconsistent data such as missing values, duplicates, placeholders, and outliers.

### Data Transformation
We transformed the data into DataFrames using the Pandas library in Python and we performed different transformations and analyses to suit.

### Feature Engineering
Based on the avaliable variables, we engineered new variables that would better suit our analysis and modelling.

### Data Analysis 
We analyzed the relationship between the most influential predictor variables and price, which is the response variable. 

### Hypothesis Testing
We tested the statistical significance of the various findings from our analysis.

### Multiple Regression Modelling
We build the best-fitting model for inferring the relationship between predictor variables and the response variable.

### Data Visualization
We used various visualization methods such as bar plots, histograms, and scatter plots to display our findings and facilitate interpretation.

### Data Interpretation
We interpreted the various findings and visualizations to build a recommendation for a real estate agency.

## THE FINDINGS
### 1. The relationship between weather season and sales performance
Our analysis reveals that there is a significant variation in the volume of sales across the months in year.<br>
i.) January and February starts off the year with low sales of around 1,000 houses per month.<br>
ii.) The volume starts to rise in March, where it is about 1,500 houses.<br>
iii.) From April to July, the volume is about 2,000 houses per month.<br>
iv.) May has the highest volume at above 2,000 houses.<br>
v.) The volume starts to decline to around 1,700 houses in August and 1,500 houses in September.<br>
vi.) There is a slight increase in October, but the price then drops through November and December.

The distribution of mean sale prices over the months in a year also shows that there are significant differences.<br>
i.) The months of January and February have lower mean prices of between $500,000 and $525,000.<br>
ii.) The mean price from March to August is around $550,000 or higher. April has the highest mean price of above $550,000.<br>
iii.) The mean price drops slightly in August and September, rises slightly in October, and then drops again in November and December.<br>


### 2. 

### The Data

I will be working with 4 Datasets out of the 11 provided:

* df_movie_gross
* df_movie_budgets
* df_imdb_rating
* df_title_basics
  
These data sets focus mostly on the various movie studios, revenue generated, genres of movies, and their popularity.

## METHODOLOGY

![data-cleansing](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/c3b83118-879b-46f9-bea6-f592a08996e4)

Data was pre-processed and cleaned by:

>Viewing the data set and data type.
>Checking for missing values. 
>Checking for duplicate values.

![DataVisualization](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/bfcbe942-64a6-49da-a1d2-40c7a9c47697)

Data was analyzed and visualized by tools like:

>Vertical and horizontal graphs, line graphs and scatter plots.

## RESULTS

![avengers-avengers-endgame](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/64508e7c-b35b-4c23-af34-61497a28f769)


## Top 10 Titles by Domestic and Foreign Gross
## Top 10 Studios by Domestic and Foreign Gross

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/2680675a-fdbd-4a87-a496-51586289572c)

### FINDINGS

We can see that the leading movie is Star Wars followed by Black Panther, Avengers, Jurassic World, Marvel Avengers etc.
We can see that the leading studio is BV followed by Uni, WB, Fox and etc.
This graph provides insights into leading studios and movies into their respective revenue contributions.

## Movie Budget vs Gross Figures

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/923c65e9-2d4e-43ac-a475-a4fde541aff0)

### FINDINGS

There’s similarity with the analysis from top 10 studios and movies seeing Avengers and Star Wars appearing to be leading in both of these and are all from BV studio.

## Top 10 Movies by Profit

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/76958c63-12ce-41f6-9ee5-fe5bdf0082ed)

### FINDINGS

From the graph above showing the Top 10 Movies by Profit, we still see that Avatar, Star Wars, Avengers, and Black Panther are leading in profits. 

Looking at these movies strategies will definitely be of help to Microsoft on launching their movie studio.

## Top 10 Genres by Average Rating and Number of Votes

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/24933fd3-8bae-4d44-aadc-ff9a7a09a768)

### FINDINGS

The most voted genres are Mystery, News, and Thriller, followed by Adventure and Action, Adventure, Musical, etc.

The most voted Primary Titles are The Paternal Bond followed by Freeing Bernie Baran and etc, these are not similar to leading movies as to the ones we saw before with high income gross.

## Top 10 Genres by Average Profit

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/f60a2246-abc5-45da-aac7-ee0f234dc542)

### FINDINGS

Genres with higher average profit can be considered more lucrative, making them potentially more attractive for investment or production decisions, so priority should be placed on producing movie genres like adventure, comedy, and romance.

## Correlation between Genres and Return on Investment (ROI)

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/22233a83-4fa9-495b-bff4-062ae8c1f246)

### FINDINGS

Genres with higher positive correlation values such as Mystery, Adventure, and Drama, are also leading in profit, average rating, and gross amounts and are more likely to yield better returns on investment.

These genres have historically shown a stronger association with higher ROI.

## Correlation Heatmap of Attributes with Gross Profit

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/1905e6eb-a818-4e71-9211-081616af0dff)

### FINDINGS

The heat map represents correlation with red being a positive correlation and blue being a negative correlation.

We can observe a Positive Correlation between:

>'production_budget' and 'worldwide_gross'.
>'production_budget' and 'profit'.
>'worldwide_gross' and 'profit' have the highest correlation.

## Correlation between Profit, Worldwide Gross, and Production Budget

![image](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/b2f83e1f-8d9b-45bc-949c-f83a9431c2e6)

### FINDINGS 

The linear graph also shows that 'production_budget' and 'profit' have a positive correlation, indicating that movies with higher production budgets tend to have higher profits, but 'profit' and 'worldwide_gross' have more similarities.

## CONCLUSION AND RECOMMENDATIONS

Microsoft needs a big production budget as it translates to successful gross income.

 Collaborations will help ease the transition to the new movie field by:
 
 >a) Working with already established Studios such as Walt Disney.

 >b) Using product placement from various companies to generate revenue which can be used in the production budget.

Movie genres to prioritize are adventure, comedy, and romance to name a few as they were highly ranked and had high gross income.

Research top-tier content and the latest trends to incorporate in movies such as the latest stories or technology to be used in movie making such as Computer Generated  Images (CGI).

Create a very strong marketing team to ensure the success of the movies both locally and internationally as worldwide gross had the highest correlation to profit.

Create a strong fan base by making merchandise that will also bring in revenue which can be channeled into the production budget which is a key factor in determining the success of movies.


## FOR MORE INFORMATION

Please view the full data analysis on the Jupyter Notebook (student.ipynb) and the presentation.

![end](https://github.com/PennyGituku/dsc-phase-1-project/assets/133040605/6f68fc87-3eef-4f85-a1cd-f7645a104de8)
