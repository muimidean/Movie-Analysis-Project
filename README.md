# Movie Analysis Project
## Overview
We analyze movie industry data to help a new studio make informed production decisions. This project explores how factors such as budget, ratings, vote counts, genres and studio performance influence box office success, providing data-driven insights to guide profitable and audience-attracting film investment.

## Objectives
* Determine the relationship between production budget and profitability.
* Asses the impact of ratings and vote counts on gross revenue.
* Explore trends in movie performance over time.
* Evaluate the performance of existing studios.
* Examine the combined influence of rating, vote counts and budget on worldwide revenue.
  
## Data Understanding 
We obtain our dataset from the [Github](https://github.com/learn-co-curriculum/dsc-phase-2-project-v3.git.) To streamline data management, we create a new SQLite dataset name movie_data.db and store it in the Data folder, consolidating only the relevant tables required for analysis. 

## Data Preparation
We perform basic data inspection to ensure data quality. This included exploring every table in the dataset.

## Data Cleaning
We clean the dataset to ensure accuracy and consistency before analysis. This involves handling missing values, verifying datatypes, checking duplicates and filtering the data.

## Feature Engineering
We perform feature engineering to prepare the dataset for analysis. This involved merging the tables using the key variables such as movie_id, movie titles and total_gross. The merged dataset allows us to analyze relationships across different aspects of movie performance effectively.

## Data Analysis
we perform univariate, bivariate and multivariate analysis.

## Findings 
We check for the distribution of the most prevalent genres

<img width="800" height="590" alt="image" src="https://github.com/user-attachments/assets/99843b38-8fa3-45cb-906f-739b5c15d258" />


The plot shows that the most profitable movie genres combine action and adventure with elements like sci-fi, fantasy, comedy or animation. These blends attract broad audiences and generate the highest returns, indicating that films mixing excitement, imagination and humor have the greatest commercial appeal.

We check for the top performing studios

<img width="800" height="590" alt="image" src="https://github.com/user-attachments/assets/8e1b28b6-7284-499b-91fe-9c77bc2b008c" />

The chart shows that Disney (BV) leads the film industry in total gross revenue, followed by Fox, Universal(Uni) and Warner Bros (WB). There is a steep decline from BV to LG/S, indicating that a few major studios dominate the box office while smaller studios contribute significantly less.

<img width="800" height="590" alt="image" src="https://github.com/user-attachments/assets/70e4c173-7d6b-4efc-931f-ee7092e210ac" />

The chart indicates a general positive correlation between worldwide revenue and average ratings. Movies with higher ratings, larger budgets, and greater audience engagement (measured by vote counts) tend to generate higher worldwide revenue.

## Conclusion
Our analysis highlights the key factors driving movie success in the film industry:

* **Budget vs Profitability:** Higher budgets generally lead to higher profits, though some low-budget films still perform well through smart spending and marketing.

* **Ratings & Votes:** Movies with ratings between 6–8 and higher vote counts tend to earn more, showing that audience engagement influences box office success.

* **Studio Performance:** A few major studios—especially Disney, followed by Fox, Universal, and Warner Bros—dominate the industry, while smaller studios succeed in niche markets.

* **Genre Performance:** The most profitable genres combine action and adventure with elements like sci-fi, fantasy, comedy, or animation. These blends attract wide audiences and deliver the highest returns.

## Recommendations

* **Optimize Budget Allocation:** Invest strategically in production budgets, maintaining a balance between scale and cost efficiency. High budgets can yield strong returns, but careful financial planning and market research are essential to avoid overspending.

* **Enhance Audience Engagement:** Focus on storytelling quality, originality, and early audience involvement through marketing and digital campaigns to improve ratings and visibility.

* **Capitalize on Genre and Franchise Trends:** Prioritize profitable genres—especially Action, Adventure, Sci-Fi, and Animation—and consider developing sequels or shared universes to sustain audience loyalty.

* **Diversify Strategies:** Explore niche markets, streaming opportunities, and creative low-budget productions to expand reach and competitiveness.

* **Leverage Data for Decision-Making:** Continuously track performance metrics such as budget, ratings, and votes to guide investment choices and forecast future trends effectively.

## Next Step
* **Expand the Dataset:** Add newer data and include variables like marketing spend or streaming success.
* **Perform Genre Deep-Dives:** Analyze audience demographics and regional preferences.

## For More Information
For additional details, questions, or collaboration inquiries, please contact:

muimidean@gmail.com

mathengealice709@gmail.com

muthoniwinnie573@gmail.com

mwendemichelle4@gmail.com

labanltarasin@gmail.com
