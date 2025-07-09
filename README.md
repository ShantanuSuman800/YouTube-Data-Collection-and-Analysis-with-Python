>YouTube Data Collection and Analysis with Python

This project is focused on collecting and analyzing data from YouTube using the "YouTube Data API v3". To learn data science, YouTube is a fantastic real-world source for working with APIs, understanding engagement metrics, and learning how to draw insights from public data.

>Project Goal

To figure out what actually makes a video trend on YouTube.

We used:
1. YouTube Data API
2. Python (with `pandas`, `matplotlib`, `seaborn`, etc.)
3. 200 trending videos (region: US)
4. Visual and statistical analysis to observe patterns in:
5. Video category
6. Duration
7. Time of upload
8. Tags
9. Views, likes, comments

> Tech Stack / Libraries

1. Python 3
2. Jupyter Notebook
3. [Google YouTube Data API v3](https://console.cloud.google.com/)
4. pandas
5. matplotlib
6. seaborn
7. isodate (for parsing video durations)

>What Does the Project Do?
Collects top 200 trending videos in the US
Stores data like:

Video title, description, channel, publish time

Views, likes, comments, tags

Category, duration, resolution

Cleans and preprocesses the data:

Fixes missing values

Converts durations and timestamps

Maps category IDs to category names

 Analyzes:

Engagement metrics (views/likes/comments)

Category-wise average performance

Video length vs view count

Impact of tags

Optimal publish hours

 Visualizes:

Distributions using histograms

Correlations using heatmaps

Engagement vs category using bar charts

Time-based insights
