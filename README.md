# ML-Internship-Task3
## Search Queries Anomaly Detection
This project utilizes the Queries.csv dataset to detect anomalies in search query data. These 
anomalies may include queries that are significantly underperforming or overperforming in terms of 
clicks, impressions, CTR, and search position. The method used for anomaly detection is the 
Isolation Forest algorithm.

## Dataset
The dataset Queries.csv includes the following columns:
- Top Queries: The actual search terms used by users.
- Clicks: The number of times users clicked on the website after using the query.
- Impressions: The number of times the website appeared in search results for the query.
- CTR (Click Through Rate): The ratio of clicks to impressions, indicating the effectiveness of the query.
- Position: The average ranking of the website in search results for the query.

# Prerequisites
Before running the script, ensure you have Python and the following packages installed:

- pandas
- sklearn
  
