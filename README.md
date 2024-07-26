   #                         Movie Studio Analysis
![image](https://github.com/user-attachments/assets/b85fdeee-c96e-4254-a223-a41f8db6af7a)

This repository contains an analysis of movie data to provide insights on what types of films are performing best at the box office. The goal is to help a new movie studio decide what types of films to create.

## Project Overview
We aim to provide actionable recommendations based on data from **Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers.** The analysis will focus on identifying trends and patterns in successful movies.
### Main Objective:
- Identify what types of films would a new movie studio create.
#### Specific Objectives:
- Which genres are most profitable?
- Which genres are most popular among viewers?
- Do viewers prefer long or short movies?
- Which writers & directors produce most successful movies?
- Which studios produce most profitable movies?

## Business Understanding
### Data Sources
- Box Office Mojo
- IMDB
- Rotten Tomatoes
- TheMovieDB
- The Numbers
## Key Findings

## Univariate Analysis
1. Average Rating Distribution
- The most common rating is 6.2, with highly rated movies (rating ≥ 9) being rare (1% of the dataset).
  
2. Runtime Distribution
 - The most common runtime is 101 minutes, with the majority of movies having runtimes between 90 and 113 minutes.
   
3. Return on Investment (ROI)
The most common ROI is 1.09, with the majority of films having ROIs between -0.58 and 3.52.

4. Genre Distribution
The top genres are Drama (26.2%), Action (23.8%), and Comedy (19.7%).

5. Production Budgets
The most common budget range is 0 - 50 million dollars, with the highest budget being 425 million dollars (Avatar).

## Bivariate Analysis
1. Film Profitability by Runtime Category
- There is no significant difference in profitability among short, medium, and long movies.
  
2. Ratings by Genre
- The highest average ratings are :( **rating > 6.2**)

| GENRE        | Average_Rating |
|--------------|----------------|
| Sport        | 7.9            | 
| Documentary  | 7.07           |    
| Biography    | 6.98           |
| Music        | 6.75           |
| Mystery      | 6.61           |
| Animation    | 6.45           |        
| Adventure    | 6.41           |


3. Genre by ROI
- The most profitable genres are  :(**ROI > 2.50** )
  
| GENRE        | Retrun on Inv. |
|--------------|----------------|
| Fantasy      | 4.76           | 
| Mystery      | 3.69           |    
| Aniamtion    | 2.72           |
| Sci-Fi       | 2.69           |
| Adventure    | 2.61           |


## Multivariate Analysis
- A multiple linear regression model was used to predict ROI based on runtime, average rating, and genre.
- The model showed that runtime and average rating are not strong predictors of ROI, with an R-squared value of 0.001.

## Correlation Analysis
- There is a weak positive correlation between vote average and ROI (0.2019).
- There is a weak positive correlation between runtime minutes and ROI (0.0097).

## Linear Regression Models
- Vote average is not a statistically significant predictor of ROI.
- Runtime minutes are not a statistically significant predictor of ROI.
  # RECOMMENDATIONS

1. Focus on **Profitable & are highly rated genres**. The most profitable & highly_rated genres are:
 - **Mystery**
 - **Animation**
 - **Adventure**

2. **Consider Viewer Preferences**: Longer movies tend to have higher ratings.

3. **Budget Consideration**s: Most successful films have moderate budgets.


This comprehensive analysis provides actionable insights for the new movie studio, guiding them on the types of films to create for better box office performance.

