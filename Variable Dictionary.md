# Variable Dictionary



|**Variable**|**Description**|
|-|-|
|yen\_usd|CSV of yen/USD Data from April 1 2014 - March 31 2025|
|idemitsu|CSV of Idemitsu Data ""|
|mitsubishi|CSV ""|
|oji|CSV ""|
|teijin|CSV ""|
|ajinomoto|CSV "" |
|kajima|CSV ""|
|okuma|CSV ""|
|kewpie|CSV ""|
|toyota|CSV "" |
|toray|CSV ""|
|meiji|CSV ""|
|nippon\_paper|CSV "" |
|shin-etsu|CSV ""|
|eneos|CSV ""|
|nikkei|CSV ""|
|honda|CSV ""|
|tokyo\_electron|CSV ""|
|obayashi|CSV ""|
|stock\_list|List of all the data above|
|stock\_names|List of all the stock names|
|stock\_splits|Dictionary recording when stocks in our data set had a split or consolidation|
|stocks|Dictionary of each stock name as the key and their DF of Date, Open, High, Low, Close, Volume, daily change, and total change|
|stock\_prices|A data frame organized by date that contains every stock close and day change as a column as the fiscal year|
|summary|Collection of day change summary statistics for all stocks|
|monthly\_returns|Data frame of all stock names and their monthly returns organized by date|
|total\_cols|list of {stock name}\_total\_change|
|correlations\_total|correlation matrix of stocks total change|
|yen\_corelations\_total|correlation matrix only looking at stocks relationship to yen/usd|
|correlations\_month|correlation matrix of stocks monthly change|
|yen\_correlations\_mont|correlation matrix only looking at stock relationships to yen/usd|
|daily\_cols|list of daily column names to extract data from stock\_prices|
|correlation\_day|correlation matrix of daily changes|
|yen\_correlations\_day|correlation matrix of daily changes of stocks compared only to yen/usd|
|industry\_exports|CSV containing the fiscal year data of Japanese export ratios based on industry|
|stock\_industries|Dictionary containing the names of all our stocks and the type of industry they primarily do business in|
|industry\_list|List of the industries in our data set|
|avg\_exports|The average export ratio over fiscal year 2014 - 2024 grouped by industry|
|yearly\_yen|Data frame of fiscal year, yen start price, yen end price, and the percent change|
|export\_yen|Data frame organized by fiscal year and grouped by industry. Contains the years export ratio and yen change ratio|
|industry\_data|Data frame that contains fiscal year data and percent changes of export ratio per fiscal year|
|industry\_corr|Correlation matrix of industry export ratios to USD/Yen|
|yearly\_corr\_df|Data frame containing fiscal year, company name, and their correlation coefficient to USD/Yen|
|yearly\_comparison|Same data frame as above bot with export ratio percentage attached|
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||
|||



