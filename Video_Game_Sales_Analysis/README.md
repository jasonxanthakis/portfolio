# Nintendo Video Game Sales Analysis

## Aim & Intent
*This section outlines the purpose of the report and the focus of the analysis.*

While exploring the "Video Game Sales Analyze" dataset, I noticed that Nintendo was the most successful company by global sales quite comfortably.

![alt text](top10_game_publishers.png)

Hence, I decided to analyse the source of Nintendo's sales in detail. 

The goal is to explore Nintendo’s success in the video game market and identify which games, platforms, regions and genres contributed most to its global dominance.


## The Dataset
*In this section, we introduce the dataset used for the analysis, including its source, structure, and key features.*

The dataset "Video Game Sales Analyze" was taken from Kaggle.
- Willian Oliveira Gibin, and GregorySmith. (2025). Video Game Sales Analyze [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/10407294

According to the creator, this dataset was created through webscraping frrom vgchartz.com using BeautifulSoup and Python.

The database covers data ranging from years 1980 to 2016. It contains a comprehensive list of video games with global sales which exceeded 100,000 copies.

Key features of the dataset are:
- Rank: Ranks video games by the number of global sales made
- Name: The title of the video game
- Platform: Specifies the platform on which the game was released
- Year: The year of release
- Genre: Categorises a game based on one of 11 genres
- Publisher: The company responsible for publishing the game
- Sales Data (measured in millions):
    - Regional sales data: Number of sales based on region (NA, EU, Japan & other)
    - Global sales data: Total number of sales across the globe

### Dataset Limitations
While the dataset provides valuable insights into video game sales, it has some limitations that should be considered:
- It covers sales data only up to 2016, excluding more recent platforms like the Nintendo Switch.
- Only games with global sales exceeding 100,000 copies are included, potentially underestimating the diversity of Nintendo's portfolio.
- Digital sales and revenue data are not captured (simply hard copies sold), which may skew results toward physical media platforms.

These limitations may affect the conclusions drawn in this report, and supplementary data could provide a more comprehensive analysis.

## Methodology
*This section describes the step-by-step approach used to analyze Nintendo’s sales performance, aiming to ensure the analysis is both systematic and thorough.*

- Data Cleaning: Go through the dataset and check for duplicates, null & inconsistent values.
- Exploratory Data Analysis: Understand the given data by using aggrigate functions & pivot tables.
- Data Analysis: 
    - Calculate spread or split of global sales based on the following factors: game, game platform, region and genre.
    - Compared global sales per year of release against the number of games released in that year.
    - Calculate the number and percentage of Nintendo games within the top 100 and top 10 global sales rankings.
    - Analyse the number of genres per platform to explore potential links between genre diversity and platform success.
- Data Visualisation: Create appropriate charts to summarize findings and organise insights into a dashboard.
    - Dashboard: The dashboard provides an interactive way to analyse Nintendo’s performance by region, platform, and genre.

## Dashboard
![alt text](Nintendo_Dashboard.png)

## Findings
*This section highlights the key findings from the analysis and summarises the insights drawn from it into a conclusion. The conclusion then provides a data-driven assessment of Nintendo's areas of success.*

### Insights
Between 1980 to 2016:
- Nintendo Wii and Nintendo DS are the best selling platforms by total sales (22% and 20%).
    - To evaluate per-game success, the average sales per game on these platforms were calculated:
        - Nintendo Wii: 2.73 million copies per game (101 games). 
        - Nintendo DS: 1.83 million copies per game (151 games).
- Wii Sports is the best selling Nintendo game (82 million copies). Super Mario Bros for the NES is the second best selling Nintendo game (40 million copies).
- Nintendo has made 52 out of 100 top games by global game copy sales. 
    - Nintendo DS and Nintendo Wii make up 13 and 12 of these 52 games (48.1% of Nintendo's top 100 games).
- Nintendo has the top 10 games by global game copy sales (5 from Wii, 2 from NES, 2 from GB and 1 from DS).
    - Nintendo Wii has 50% of top 100 games.
- Nintendo DS has the most games (151 out of 703).
- The best selling game genres are Platform (24%), Role-Playing (16%) and Sports (12%).
    - Platform is also the most common game genre (15.9% of games made).
- Nintendo's best selling regions are NA (46%), Japan (26%) and EU (23%).
    - Nintendo's best selling region relative to its population is Japan (4 sales per capita).

### Conclusion
Nintendo's most successful platforms by sales are the Wii and DS (22% and 20% of Nintendo sales). They also make up almost 50% of Nintendo's top 100 games. Nintendo DS has more games than Nintendo Wii (151 to 101). However, Nintendo Wii has 50% of Nintendo's top 10 games including the top seller Wii Sports (82 million copies). Furthermore, the Wii outperforms Nintendo DS by average sales per game (2.73 million per game to 1.83 million). While the DS had a larger catalog, the Wii's focused success in fewer titles solidifies its position as Nintendo's most impactful platform as of 2016.

Nintendo's best selling genre are Platform games, such as the second best seller Super Mario Bros. However, it should be noted that Platform games are also Nintendo's most common game genre (16%). Nintendo has also found great success with other genres, such as Role-Playing and Sports. A good example is the Sports themed best seller Wii Sports. Nintendo doesn't seem to have an outstanding game genre as of 2016.

The NA, EU and Japan region contribute 92% of Nintendo's sales (46%, 23% and 26% respectively). In terms of raw sales, North America is Nintendo's best performing region with almost 820 million sales. However, Nintendo's best selling region relative to population is Japan (almost 4 sales per capita), showing Nintendo's dominance in the region.