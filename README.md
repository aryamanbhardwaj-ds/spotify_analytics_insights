Spotify Data Analytics Dashboard
📌 Project Overview
This repository contains a professional Spotify Analytics Dashboard built using Power BI. The project aims to analyze music streaming trends, track popularity, and artist performance. By transforming raw streaming data into interactive visuals, this dashboard identifies the key "success factors" that drive songs to the top of the charts.

📊 Dashboard Preview
Note: Place a screenshot of your dashboard here to grab the recruiter's attention! ![Dashboard Screenshot](link_to_your_image.png)

🛠️ Technical Implementation
Since this is a standalone Power BI project, the core technical work resides within Power Query and DAX.

1. Data Cleaning & ETL (Power Query)
Data Normalization: Cleaned and structured raw Spotify datasets, ensuring consistency across track names, artist IDs, and release dates.

Feature Engineering: Extracted time-based columns (Year, Month, Quarter) to enable time-series analysis.

Data Integrity: Handled missing values in popularity scores and streaming counts to prevent skewed visualizations.

2. Data Modeling
Implemented a Schema approach to connect track metadata with streaming metrics.

Established one-to-many relationships between the Artist table and the Tracks table for seamless cross-filtering.

3. DAX & Analytical Measures
I authored several custom DAX measures to move beyond basic data reporting. Key calculations include:

Total Streams & Reach: Aggregated volume across regions.

Average Popularity Score: A dynamic metric reacting to user-selected filters.

Time-Intelligence: Comparison of performance across different release years and months.

💡 Business Insights
Genre Dominance: Identified which genres are currently leading in streaming volume and listener retention.

Audio Characteristics: Analyzed how attributes like 'Danceability' and 'Energy' correlate with a track's likelihood of becoming a hit.

Artist Growth: Visualized the trajectory of artists to identify "Rising Stars" versus established icons.

📂 How to Use This Repo
Download: Clone this repository or download the .pbix file.

View: Open Spotify Dashboard Creation Project.pbix using Power BI Desktop.

Interact: Use the slicers on the left/top to filter by Year, Genre, or Artist to see the data update in real-time.
