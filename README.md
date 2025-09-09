# Video Game Sales Market Research: Indentifying in Demand Games

# Author: Thanh Xuyen, Nguyen

https://www.linkedin.com/in/xuyen-thanh-nguyen-0518/

# Tool:
Python (Pandas, NumPy, Matplotblib, Seaborn), data cleaning, EDA, grouping/aggregation, visualizations, statistical insights, marketing research application.

# Dataset

Kaggke's 'vgsales.csv' with 16598 rows, 11 columns from 1980 to 2020

# Key Visualizations

<img width="859" height="545" alt="Image" src="https://github.com/user-attachments/assets/13f33e99-2139-4d00-98aa-cc89cd74fbf3" />

Total sales by region: North America has the highest sales, followed by Europe, Japan, and Other regions. Global sales is the sum of all regional sales.

<img width="1014" height="602" alt="Image" src="https://github.com/user-attachments/assets/97f662cc-71ae-4999-97c9-3ab021695b1a" />

The most common genre is Action with 3253 games, followed by Sports and Misc genres with 2304 and 1710 games respectively. The least common genres are Strategy and Puzzle with 671 and 571 games respectively.

<img width="1016" height="720" alt="Image" src="https://github.com/user-attachments/assets/cc88c4d4-b19f-4968-beb9-cc9b2c425657" />

The most common platform is DS with 2133 games, followed closely by PS2 with 2127 games. The least common platforms are GG and PCFX with only 1 game each.

<img width="1014" height="602" alt="Image" src="https://github.com/user-attachments/assets/aab5fb5d-05ec-477c-be31-fdba3246aaf6" />

The genre with the highest total sales is Action with 1721.86 million, followed by Sports and Shooter with 1308.84 million and 1025.69 million respectively. The genre with the highest average sales per game is Platform with 0.95 million, followed by Shooter with 0.80 million and Role-Playing with 0.63 million. The genre with the lowest total sales is Strategy with 173.16 million, while the genre with the lowest average sales per game is Adventure with 0.18 million.

<img width="1016" height="699" alt="Image" src="https://github.com/user-attachments/assets/fdb408b7-09db-4bb4-bb8d-b8268543367b" />

Top 5 platforms published by count are DS, PS2, PS3, Wii, and PSP with 2133, 2127, 1304, 1290, and 1197 games respectively. The platform with the highest number of games published is DS with 2133 games, followed closely by PS2 with 2127 games and PS3 with 1304 games. The platform with the lowest number of games published is GG and PCFX with only 1 game each.

Top 5 platforms by total sales are PS2, X360, PS3, Wii, and DS with 1233.56, 969.31, 949.39, 909.20, and 817.94 million respectively. The platform with the lowest total sales is PCFX with only 0.03 million.

Top 5 platforms by average sales per game are GB, NES, SNES, PS4, and X360 with 2.62, 2.56, 0.84, 0.83, and 0.78 million respectively. The platform with the lowest average sales per game is NG with 0.12 million.

Cross-referencing the top platforms by count, total sales, and average sales per game, we can see that DS and PS2 are among the top platforms in all three categories. X360 and PS3 also appear in the top platforms by total sales and average sales per game. This indicates that these platforms have a strong presence in the market with a high number of games published, high total sales, and high average sales per game.

<img width="1005" height="545" alt="Image" src="https://github.com/user-attachments/assets/c075b996-811e-42d1-b69e-2c780f1adce2" />

The year with the highest number of games released is 2009 with 1431 games, followed closely by 2008 with 1428 games and 2007 with 1202 games. The year with the lowest number of games released is 2020 with only 1 game.

The year with the highest total sales is 2008 with 678.49 million, followed by 2009 with 667.10 million and 2007 with 610.44 million. The year with the lowest total sales is 2017 with only 0.05 million.

The year with the highest average sales per game is 1989 with 4.32 million, followed by 1985 with 3.85 million and 1984 with 3.60 million. The year with the lowest average sales per game is 2017 with only 0.02 million.

Cross-referencing the top years by count, total sales, and average sales per game, we can see that the late 2000s (2007-2009) were a peak period for video game releases and sales. This period saw a high number of games released, high total sales, and relatively high average sales per game. The early years (1980s) also show high average sales per game, indicating that while fewer games were released, they tended to sell well on average.

<img width="1160" height="771" alt="Image" src="https://github.com/user-attachments/assets/ac16f2f5-ceae-4bd7-b760-f23e75eee05f" />

North America has the highest sales across all genres, followed by Europe except for Role-Playing games where Japan leads. Japan has significantly higher sales in Role-Playing games compared to Other regions. Japan and Other regions have fluctuating sales across different genres; action, shooter, and racing games perform well in Other regions while other genres have lower sales.

<img width="625" height="526" alt="Image" src="https://github.com/user-attachments/assets/c5863aa7-7850-4162-b33d-829c408f5d6f" />

The correlation matrix shows strong positive correlations between all regional sales and global sales, indicating that higher sales in any region tend to contribute to higher global sales. North America and Europe have the strongest correlation (0.77), suggesting that games popular in one region are often popular in the other as well. Japan has a moderate correlation with both North America (0.45) and Europe (0.44), indicating some overlap in game preferences but also distinct differences. Other regions show moderate correlations with all other regions, suggesting a more varied market.

North America and Europe are the dominant markets, these regions have the highest sales and the strongest correlation with global sales. Japan, while having lower correlations, shows a strong preference for Role-Playing games, indicating a unique market segment. Other regions, while contributing less to total sales, still play a significant role in the global market.

# Advance analysis

## 1. Who are the top 10 publishers by global sales, and what percentage of the overall market do they control?
<img width="1027" height="691" alt="Image" src="https://github.com/user-attachments/assets/9ff6e44e-8921-4309-baf8-328fd58b14e1" />

The top 10 publishers control a significant portion of the overall market, with Nintendo alone accounting for over 20% of global sales with global sales of 1784.23 million, followed by Electronic Arts with 1093.21 million with 12.40%. The combined market share of the top 10 publishers is approximately 69.78%, indicating a high level of market concentration among leading publishers.

## 2. Who dominates sales in the Role-Playing genre, and how may unique franchises (e.g. Pokemon) contribute to their success?

The Role-Playing genre is dominated by Nintendo, which has the highest global sales of 284.53 million in this genre. The Pokemon series significantly contributes to Nintendo's success in the Role-Playing genre, with 20 unique franchises, indicating a strong and consistent presence in this market segment.

## 3. Who dominates sales in the Action genre in the North American market, and what name are their top 3 games?

The Action genre in the North American market is dominated by Take-Two Interactive, which has the highest sales of 101.45 million in this genre. Their top 3 games contributing to this success are "Grand Theft Auto V", "Grand Theft Auto: San Andreas", and "Grand Theft Auto: Vice City", all of which are part of the highly popular Grand Theft Auto series.

## 4. Who are the publishers with highest average global sales per game in the Shooter genre, and why might they outperform others?

The highest average sales per game for publishers in the Shooter genre is held by Microsoft Game Studios with 3.41 million, followed by Nintendo with 2.90 million and Activision with 1.91 million. These publishers likely outperform others due to their strong brand recognition, popular game franchises, and effective marketing strategies that resonate well with the Shooter genre audience. 

## 5. When did global sales peak, and what genres or platforms drove those peaks?

Years with peak global sales:
{2008: 678.49, 2009: 667.1, 2007: 610.44, 2010: 600.36, 2006: 520.52}

In the peak year 2008, the top genre was Action and the top platform was DS.

In the peak year 2009, the top genre was Action and the top platform was DS.

In the peak year 2007, the top genre was Action and the top platform was DS.

In the peak year 2010, the top genre was Action and the top platform was DS.

In the peak year 2006, the top genre was Action and the top platform was PS2.

The peak years for global sales were primarily driven by the Action genre, which was the top genre in all peak years. The DS platform was the leading platform in four out of the five peak years, indicating its significant role in driving sales during this period. The PS2 platform also contributed to peak sales in 2006. This suggests that both the Action genre and these platforms were key factors in achieving high global sales during these years.

## 6. When were the most games released for each platform, and how did sales trend over time for those platforms?

The platform DS had the most game releases in the year 2008 with 492 games released.

The platform Wii had the most game releases in the year 2009 with 325 games released.

The platform PS2 had the most game releases in the year 2002 with 280 games released.

The overall platform with the most game releases was DS in 2008 with 492 games released.

<img width="1005" height="545" alt="Image" src="https://github.com/user-attachments/assets/6736781b-c7c7-4bf0-86d6-be2983a2e8d3" />

## 7. When do multi-year franchises (e.g. FIFA, Call of Duty, Grand Theft Auto) see sales decline, and how long do top selling games maintain relevance?

<img width="997" height="545" alt="Image" src="https://github.com/user-attachments/assets/9b5e46bd-5c4d-4d10-b0d6-63378d932193" />

## 8. Where generates the highest sales for Action genres, and what percentage comes from Japan vs. North America?

Top region for Action genre sales: NA_Sales with sales of 861.8 million

Percentage of Action genre sales from North America: 50.05%

Percentage of Action genre sales from Japan: 9.21%

## 9. Where do Nintendo published games perform best relative to competitors, and which regions do they underperform?

The region where Nintendo performs best is NA_Sales with sales of 815.75 million, which ratio is 45.72%.

The region where Nintendo underperforms the most is Other_Sales with sales of 95.19 million, which ratio is 5.34%.

## 10. Where have sales grown the most from 1980s to 2010s?

<img width="1169" height="728" alt="Image" src="https://github.com/user-attachments/assets/72d7af31-fedd-43a6-a05a-e1bca75fe12c" />

The most sales growth ratio from 1980s to 2010s:
Other_Sales with growth of 262.58 million, which ratio is 3682.75%.

The highest sales growth rate from 1980s to 2010s is in Other regions with a growth of 262.58 million, which ratio is 3682.75%, following that is Europe with a growth of 807.67 million and a ratio of 2588.69%. This indicates a significant increase in sales in Other regions over the decades, suggesting that these markets have expanded rapidly and may offer new opportunities for game publishers and developers.

The North America and Europe regions are not the highest growth regions from 1980s to 2010s, but the sales values have significantly increased from 1980s to 2010s. With an increase of 876.82 million and a growth rate of 372.07% for North America, and an increase of 807.67 million and a growth rate of 2588.69% for Europe, these regions remain dominant markets for video game sales despite not having the highest growth rates compared to Other regions and Japan in terms of percentage growth.

## 11. How do regional sales correlate with global success, and which geners show the strongest cross-regional appeal?

The most genres with strong cross-regional appeal, as indicated by high correlations with global sales across multiple regions, are Sports, Platform, Racing, Role-Playing, Puzzle, Misc, Shooter, Simulation, Action, Fighting, Adventure, and Strategy. These genres tend to perform well in North America and Europe, suggesting they have broad international appeal and are likely to succeed in diverse markets. Those genres with high correlations across multiple regions indicate a strong cross-regional appeal, those regions are North America and Europe. Which means games in these genres are likely to perform  well in both North American and European markets high correlations with global sales across multiple regions.

## 12. How much do multi-platform releases boost total global sales compared to platform games?

Total global sales from multi-platform releases: 4602.13 million (average per game: 1.69.)

Total global sales from single-platform releases: 4213.73 million (average per game: 0.31.)

Boost in sales from multi-platform releases: 547.09 %

## 13. How has the distribution of sales by genre evolved over time (e.g., rise of Shooters post 2000), and what factors (platform/publisher) explain it?

<img width="1005" height="545" alt="Image" src="https://github.com/user-attachments/assets/6d7537d5-98a3-4b5f-81d3-96a334ccf844" />

The top platforms for the Shooter genre are X360, PS3, and PS2, with X360 leading in total sales. The top publishers are Activision, Electronic Arts, and Microsoft Game Studios, with Activision having the highest sales. These platforms and publishers likely succeed in the Shooter genre due to their strong game libraries, popular franchises, and effective marketing strategies that resonate with Shooter game enthusiasts.

## 14. What are the top 10 highest-selling games overall, and why (based on genre, platform, publisher, release year)?

These top 10 highest-selling games overall have achieved significant global sales, with "Wii Sports" leading the list with 82.74 million sales.

These games are predominantly from Nintendo, indicating the company's strong presence in the video game market. The genres of these top-selling games include Sports, Platform, Racing, Role-Playing, Puzzle, Misc, and Shooter, showcasing a variety of game types that appeal to a wide audience. The platforms for these games are mainly Wii and Nintendo's handheld consoles (NES, GB, DS), highlighting the popularity of Nintendo's hardware in driving game sales. The release years of these games range from 1984 to 2009, indicating that both classic and more recent titles have achieved significant sales figures. Overall, the success of these games can be attributed to their engaging gameplay, strong brand recognition, and the popularity of the Nintendo platform.

# Conclusions

Insight conclusions:
The video game industry has seen significant growth and changes over the decades, with North America and Europe remaining dominant markets. The Action genre is the most popular across all regions, while Role-Playing games have a strong presence in Japan. Major publishers like Nintendo and Electronic Arts control a large portion of the market, with Nintendo excelling in the Role-Playing genre. The late 2000s were a peak period for game releases and sales, driven by platforms like DS and PS2. Multi-platform releases boost sales significantly compared to single-platform games. Overall, understanding regional preferences, genre popularity, and platform success can help developers and publishers tailor their strategies for better market performance.
