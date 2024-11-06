Ice Video Game Sales Analysis Project
Overview
This project analyzes global video game sales data for Ice, an online store, to identify patterns in platform and genre popularity and understand factors that drive game success. The goal is to support strategic planning for targeted advertising, game development, and future releases by uncovering regional preferences in North America, Europe, and Japan.

Dataset
Source: Ice Video Game Sales Dataset
Content: Over 16,000 entries with details on platforms, genres, release years, regional sales (NA, EU, JP, and Others), user and critic scores, and ESRB ratings.
Objective: To identify successful game attributes and preferences by region to optimize marketing and development strategies.
Project Structure
Notebook: ice_game_sales_analysis.ipynb - This main analysis notebook covers data preparation, analysis, visualization, hypothesis testing, and final conclusions.
Data: datasets/games.csv - The source dataset for the analysis, stored in the datasets folder.
Analysis Steps
Data Loading and Preparation: Standardized column names, handled missing values, converted data types, and created a new total_sales column.
Exploratory Data Analysis (EDA): Investigated platform and genre preferences, trends in regional sales, and the impact of user/critic scores on sales.
Regional Profiles: Identified the top platforms, genres, and ESRB ratings by region (NA, EU, JP).
Hypothesis Testing:
Tested whether average user ratings are the same for Xbox One and PC platforms.
Tested whether there’s a difference in user ratings between Action and Sports genres.
Conclusions and Recommendations: Summarized findings and provided actionable strategies based on insights from the analysis.
Key Findings
Platform Preferences:

North America: Xbox 360 and PlayStation 2 lead in popularity.
Europe: PlayStation 2 and PlayStation 3 dominate the market.
Japan: Nintendo DS and legacy PlayStation platforms are favored.
Genre Preferences:

North America & Europe: Action, Sports, and Shooter genres are most popular.
Japan: Role-Playing games are highly preferred, indicating a unique cultural taste.
Impact of User Ratings: Weak correlation (-0.06) between user scores and sales, suggesting that ratings alone do not drive sales.

Hypothesis Testing:

No significant difference was found in user ratings between Xbox One and PC platforms.
No significant difference in user ratings was found between Action and Sports genres.
Recommendations
Targeted Marketing:

North America: Market Action, Sports, and Shooter games on Xbox and PlayStation.
Europe: Emphasize PlayStation platforms, focusing on Action, Sports, and Racing games.
Japan: Prioritize Role-Playing games on Nintendo DS and 3DS, leveraging popular RPG franchises.
Game Development Focus:

Invest in multi-platform releases, particularly for Action and Role-Playing games, to capture audiences across regions.
Leveraging ESRB Ratings:

In North America and Europe, highlight mature-rated games in advertisements.
In Japan, focus on family-friendly games, aligning with cultural preferences for less graphic content.
How to Run the Project
Environment Setup:

Install dependencies:
powershell
Copy code
pip install pandas numpy matplotlib seaborn scipy jupyter
Run Notebook:

Open the Jupyter Notebook:
powershell
Copy code
jupyter notebook ice_game_sales_analysis.ipynb
Execute each cell in sequence to reproduce the analysis.
Author
For more information or questions, please contact [Rawaa Yousseif](https://github.com/rawaayousseif/ice-video-game-sales-analysis.git).