# Nintendo_Game_Sales_Analysis

Problem Summary: 
This project aims to investigate popular game genres in Japan and their impact on game firms for clients targeting the Japanese market. The Japanese gaming industry is one of the largest and most important in the world, and understanding market trends and characteristics can help companies stay ahead of changes and maximize sales.

Data: 
The dataset contains a diverse selection of games with varying sales performance, popularity, and longevity scraped from Japanese video game sales websites

Analysis: 
Linear mixed-effects regression (LMER) models were used to analyze the relationship between weekly sales and various predictor variables, fitted using three LMER models in R with the Bobyqa optimization method. Models include the game title as a random effect, which provides the best fit for exploring popular game genres in Japan and their implications for game companies. Its insights can assist game companies in making informed decisions about game development and marketing in Japan.

Key Findings:
Based on our analysis, we found that games with genres Adventure (ADV), Role-Playing (RPG), and Miscellaneous (ETC) have positive estimates, while genres such as Education, Lifestyle (HOB), Racing (RCE), Strategy (SLG), and Sports (SPT) have negative estimates. Additionally, being in the top 10 has a statistically significant effect on weekly sales.
