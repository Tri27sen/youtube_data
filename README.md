
YouTube Video Analysis Project

Dataset Overview
The dataset consists of YouTube video data with the following columns:

publishedAt: The date and time when the video was published (datetime64[ns, UTC]).

channelId: The unique identifier of the channel (object).

channelTitle: The title of the channel (object).

categoryId: The identifier for the video category (int64).

trending_date: The date and time when the video was trending (datetime64[ns, UTC]).

tags: Tags associated with the video (object).

view_count: Number of views the video has received (int64).

likes: Number of likes the video has received (int64).

dislikes: Number of dislikes the video has received (int64).

comment_count: Number of comments on the video (int64).

comments_disabled: Indicates if comments are disabled (bool).

ratings_disabled: Indicates if ratings are disabled (bool).

description: Description of the video (object).

date: Date part of the publishedAt (object).

time: Time part of the publishedAt (object).

title_cl: Cleaned title of the video (object).

category_name: Name of the video category (object).

tag_count: Number of tags associated with the video (int64).

--------------------------------------------------------------------------------------
Analysis Performed

1. Relationship with Views, Likes, Dislikes, and Comments
Objective: Analyze the relationship between view count, likes, dislikes, and comments.
Plots: Scatter plots and correlation heatmaps to visualize these relationships.

3. Most Trending Categories
Objective: Identify the video categories that trend the most.
Plots: Bar chart showing the count of trending videos by category.

5. Most Trending Channels
Objective: Identify channels with the highest number of trending videos.
Plots: Bar chart showing the count of trending videos by channel.

7. Videos Trending More Than Once
Objective: Find videos that appeared in the trending list more than once.
Plots: List of videos and corresponding channels with high trending frequency.

9. Channels with Most Trending Videos
Objective: Determine which channels have the most trending videos.
Plots: Bar chart showing channels with the most trending videos.

11. Interaction of Top Channels
Objective: Analyze the interaction and engagement metrics of the top trending channels.
Plots: Scatter plots showing likes, dislikes, and comment counts of top channels.

13. Tags that Made Videos More Trending
Objective: Identify tags that contribute to making videos trend.
Plots: Word cloud and bar chart of most common tags in trending videos.

15. Published & Trending Days and Time Relationship
Objective: Analyze the relationship between the publish time and the trending time.
Plots: Bar charts and scatter plots showing distribution of publish hours and trending hours.

17. Rating and Trending Relationship
Objective: Investigate the relationship between ratings (likes, dislikes) and trending status.
Plots: Scatter plots and correlation heatmaps of ratings and trending metrics.

19. Most Trending Videos Duration Pie Chart
Objective: Visualize the duration of the most trending videos.
Plots: Pie chart showing the distribution of video durations among the most trending videos.
-----------------------------------------------------------------------------------------------------
Conclusion
This analysis provides insights into various aspects of trending YouTube videos, including the factors that influence their popularity, the channels that frequently trend, and the characteristics of videos that trend more than once. The visualizations help in understanding these relationships and patterns effectively.
