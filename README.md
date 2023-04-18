Position-Red-Cards
================
Safia Read and Ben Schwartz
04/18/2022

<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![Launch Rstudio
Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/safiaread/Position-Red-Cards/main?urlpath=rstudio)
<!-- badges: end -->

# Analysis of Impact of Red Card Recipient’s Position on Match Outcome

## Safia Read and Ben Schwartz

#### – Project Status: \[Completed\]

## Project Intro/Objective

The purpose of this project is to investigate whether the position a football player is when they are receiving a red card has an impact on the outcome of the match. This is important because match outcome has several economic effects (sponsorship, gambling, etc.) that makes winning a much more desirable outcome than losing. Knowing more about how red cards affect match outcome and also a team's offensive and defensive capabilities can help teams to strategize and betting sites to better formulate their live odds. 

### Methods Used

- Tidyverse and Lubridate packages to clean and merge datasets
- Plotly and Ggplot visualizations
- T-tests for significance
- KDE
- 2 Categorical Variable Regression

### Platforms and Languages

- R

## Project Description

The research question we explored was whether a player's position had an effect on how the team performed in a match. The football positions we investigated were defender, midfielder, and forward. We looked at match outcome and how the carded team and their opponent performed in four metrics: goals scored, shots on goal, shots on target, and corners earned. We used t.tests comparing the mean of subsets of each carded position with the mean of uncarded players to explore potential significant differences. We also used plotly and ggplot visualizations to look at factors affecting red cards as well as to compare the percentage of each match outcome of each subset of data. We used a KDE to visualize total fouls committed to gain a baseline understanding outside of red cards of the distribution of misconduct in a match. We then used regression to explore relationships between player position and match outcome. 

We faced most of our challenges in cleaning and merging the datasets. The players dataset was missing many of values we desired such as Home and Away team and had to have values renamed for relevance to our project and consistency with the teams dataset. There was also some date discrepancies between the datasets that made us have to drop some values. 

Potential future directions are expanding the scope of the project to more seasons or more leagues to better understand this phenomenon. This would also allow us to anaylze the goalkeeper position that we could not here because of lack of data. We could also look at more measures of team performance such as completed passes or saves. We could also investigate what factors cause red cards to be given, such as location, date, or referee bias.

## How to Use This Repository

This research compendium has been developed using the statistical
programming language R.

### Project Structure

project
.
├── analysis/
│   └── red_card_analysis.Rmd       # R Markdown file with our analysis and descriptive comments
├── data/
│   ├── cleaned_merged_seasons.csv      # player performance stats by match
│   └── epl-allseasons-matchstats.csv      # team performance stats by match 
└── READ.ME.md       #description of project

### Run in Your Web Browser

You can click the “binder” badge above to open this repository using
RStudio in your browser. Then, please open…

### Download and Run Locally

To work with the repository on your local computer, you will need the [R
software](https://cloud.r-project.org/) and RStudio
Desktop\](<https://rstudio.com/products/rstudio/download/>).

You can download this repository as a zip from from this URL:
[main.zip](/archive/main.zip). After unzipping, please run
`renv::hydrate()` in the console to install the necessary packages.

### Featured Notebooks/Analysis/Deliverables or Demo
https://github.com/tara-nguyen/english-premier-league-datasets-for-10-seasons
https://github.com/vaastav/Fantasy-Premier-League

### How to cite

Please cite this project as:

Read, Safia and Schwartz, Ben *Analysis of Impact of Red Card Recipient's Poisiton on Match OutcomeAnalysis of Impact of Red Card Recipient's Poisiton on Match Outcome* https://github.com/safiaread/Position-Red-Cards

### Licenses

MIT License

Copyright (c) [2023] [Safia Read and Ben Schwartz]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
