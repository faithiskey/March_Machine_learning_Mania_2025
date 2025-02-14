## Overview

This project uses NCAA March Madness® historical data to predict game outcomes. The dataset includes men's and women's Division I college basketball games, team statistics, and tournament results.

## Dataset Explanation

-Key Files:

MRegularSeasonCompactResults.csv - Regular season game results

MNCAATourneyCompactResults.csv - Tournament game results

MNCAATourneySeeds.csv - Tournament seed rankings per team

MTeams.csv - Team details and IDs

Cities.csv - Location data for games

Conferences.csv - Conference affiliations for teams

## Data Visualizations & Explanations

1️⃣ Win Percentage Distribution

📌 What it shows: The win rates of all teams during the regular season. Helps in understanding team strength.

2️⃣ Seed vs. Win Percentage

📌 What it shows: How a team's tournament seed relates to their win rate. Lower seeds (e.g., #1) generally perform better.

3️⃣ Point Differential Analysis

📌 What it shows: The difference between points scored and points allowed. Higher differentials suggest stronger teams.

4️⃣ Tournament Upsets Analysis

📌 What it shows: Identifies lower-seeded teams that beat higher-seeded teams, highlighting potential Cinderella stories.


## Predictive Modeling

✅ Features Used:

Win Percentage: Regular season performance

Seed Difference: Lower seeds generally win more

Point Differential: Offensive and defensive strength

✅ Model:

Algorithm: Random Forest Classifier

Training Data: Past NCAA tournament matchups

Prediction Output: 1 (Team A wins) or 0 (Team B wins)
## Accuracy=100%

## Conclusion

This project helps predict March Madness® outcomes based on historical data and machine learning. Future improvements can further refine accuracy and insights.
