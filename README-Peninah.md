# Phase 2 Project

![Real Estate]([https://img.freepik.com/premium-photo/real-estate-sales-manager-giving-keys-customer-after-signing-rental-lease-contract_28283-1047.jpg))

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

## Project Overview

This project seeks build a data analytics model for a real estate agency that will help homeowners buy and/or sell homes in King County, Washington.

### Business Problem

To help Microsoft with information on the movie industry based on readily available historical data of past movies such as:

>Identify and analyze the most successful movie studios and the genre.

>Explore the most-rated movie genres to target the popular niche.

>Analyze factors leading to high ROI.

>Translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create and also aid in reducing business risks.

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
