# Referee Analysis in the English Premier League

## Project Description
This project delves into the influence of referees in the English Premier League (EPL) between the 2014-2015 and 2018-2019 seasons. Leveraging extensive match data, the analysis explores referee biases and their potential impact on game outcomes. Specifically, the project addresses three key questions:

1. Is there a difference in the frequency of fouls, yellow cards, and red cards issued to the "Big 6" teams compared to others?
2. Which referees show bias towards or against specific teams?
3. Which teams are most likely to receive fouls, yellow cards, and red cards?

Our findings reveal nuanced patterns suggesting potential biases in some cases. However, due to various influencing factors, these results are not definitive.

## Features and Highlights

- **Exploratory Analysis:** Relationships between half-time and full-time goals, and referee decisions on fouls and cards.
- **Visual Demonstrations:** Heatmaps showing referee tendencies, scatterplots for goal analyses, and summaries of card distributions.
- **Insights:** Identification of referees with a significant tendency to issue cards unevenly between teams.

## Tech Stack

- **Languages:** R, R Markdown
- **Libraries:** ggplot2, dplyr, tidyr
- **Tools:** RStudio, Pandoc for report generation

## Datasets
The project utilizes the following datasets:

1. [2014-15 Premier League Matches](https://data.world/chas/2014-15-premier-league-matches)
2. [2015-16 Premier League Matches](https://data.world/chas/2015-2016-premier-leage-matches)
3. [2016-17 Premier League Matches](https://data.world/chas/2016-2017-premier-league-matches)
4. [2017-18 Premier League Matches](https://data.world/chas/2017-2018-premier-leage-matches)
5. [2018-19 Premier League Matches](https://data.world/chas/2018-2019-premier-league-matches)

## Project Highlights

### Images and GIFs
- **Heatmap of Referee Decisions:** A visualization of referee tendencies to issue yellow cards to home vs. away teams.
- **Scatterplots of Goals:** Depicting correlations between half-time and full-time goals.
- **Card Distribution Graphs:** Summaries of yellow and red card distributions.

## Challenges and Solutions

### Most Difficult Aspect
The most challenging aspect of the project was integrating and cleaning the disparate datasets. The data varied in structure and quality, requiring extensive preprocessing to harmonize and extract meaningful insights. This was tackled using robust data manipulation libraries in R, such as `dplyr` and `tidyr`.

## Conclusion
This analysis sheds light on referee behavior and their potential influence on EPL games, providing a foundation for further research in sports analytics. While the findings suggest some trends, more comprehensive datasets and advanced models could refine these conclusions.
