# Exploratory-Data-Analysis-on-Play-Store-App-Review.
the data sources is from kaggle.
#Executive Summary:
This exploratory data analysis (EDA) on the Play Store App Reviews dataset aimed to understand the characteristics and patterns within the data. The analysis involved data cleaning, exploration, and visualization to derive insights into app categories, ratings, installs, pricing, and more.
Data Overview:
The dataset contains 10 columns and 8,831 rows.
Initial data types include object, float64, and int32.
Missing values were identified and addressed during the cleaning process.
Data Cleaning Process:
Handling Missing Values:

Rows with missing data for the 'Category' column were dropped.
Missing values in the 'Type', 'Rating', 'Content Rating', 'Current Ver', and 'Android Ver' columns were filled using appropriate methods.
Column Dropping:

Unnecessary columns were dropped to streamline the dataset for analysis.
Data Type Conversion:

Columns like 'Reviews', 'Size', 'Installs', and 'Price' were converted to their respective correct data types.
Handling Special Values:

'Varies with device' values in the 'Size' column were converted to NaN.
Rows with NaN values in the 'Size' column were dropped.
Data Visualization and Analysis:
Top Categories:

Family and Game categories have the highest number of apps.
Beauty and Comics categories have the fewest apps.
Content Rating Distribution:

The 'Everyone' category dominates the Play Store.
Ratings Distribution:

Most apps have ratings between 3.5 to 4.8.
Paid vs. Free Apps:

Approximately 92% of apps are free, while 8% are paid.
Top Installed Categories:

Game, Family, Tools, Communication, and News & Magazines have the highest installs.
Top Installed Apps in Sports Category:

Apps like 8 Ball Pool, 3D Bowling, and Dream League Soccer 2018 have the highest installs in the Sports category.
Top Expensive Apps:

'I am rich' and 'I am Rich Premium' are the most expensive apps.
Apps with Highest Reviews:

Apps like Clash of Clans, Subway Surfers, and Clash Royale have the highest number of reviews.
Count of Apps in Different Genres:

Tools and Entertainment genres have the highest number of apps.
Highest Earning Apps:

The analysis identified apps that have the highest potential earnings based on price and installs.
Conclusion:
The exploratory data analysis provided valuable insights into the Play Store App Reviews dataset. It revealed patterns in app categories, ratings, installs, pricing, and genres. These insights can inform further analysis, decision-making, and potential strategies for app developers and stakeholders in the mobile app industry.




