# YouTube Statistics Analysis Project

## Overview
This project analyzes global YouTube statistics from 2023 to identify trends, patterns, and insights that can help content creators understand factors influencing YouTube success. The dataset includes details such as YouTube channels, subscribers, video views, earnings, content categories, and country-based metrics for the top YouTubers worldwide.

## Dataset
The dataset used for this analysis is sourced from Kaggle under the title "Global YouTube Statistics 2023." It contains data on 995 YouTube channels and includes the following key columns:

- **Youtuber**: Name of the YouTube channel.
- **Subscribers**: The number of subscribers for each channel.
- **Video Views**: Total number of views for each channel.
- **Uploads**: Number of videos uploaded by each channel.
- **Category**: The content category of the channel (e.g., Music, Gaming, Education).
- **Country**: The country where the channel is based.
- **Earnings**: Estimated earnings (monthly and yearly) for each channel.
- **Subscribers for Last 30 Days**: Number of new subscribers gained in the past month.
- **Video Views for Last 30 Days**: Total views gained in the past month.
- **Created Year**: The year the YouTube channel was created.
- **Channel Type Rank**: Rank based on category popularity.
- **rank**: Rank of the channel based on popularity.
- **Youtuber**: Name of the YouTube channel.
- **subscribers**: Number of subscribers to the channel.
- **video views**: Total video views on the channel.
- **category**: Category of the channel (e.g., Music, Shows, People & Blogs).
- **Title**: Title of the channel or video.
- **uploads**: Number of uploads by the channel.
- **Country**: Country where the channel is based.
- **Abbreviation**: Country abbreviation.
- **channel_type**: Type of the channel (e.g., individual, brand).
- **video_views_rank**: Rank of the channel based on video views.
- **country_rank**: Rank of the country based on the number of channels.
- **channel_type_rank**: Rank of the channel type.
- **video_views_for_the_last_30_days**: Video views in the last 30 days.
- **lowest_monthly_earnings**: Lowest estimated monthly earnings of the channel.
- **highest_monthly_earnings**: Highest estimated monthly earnings of the channel.
- **lowest_yearly_earnings**: Lowest estimated yearly earnings of the channel.
- **highest_yearly_earnings**: Highest estimated yearly earnings of the channel.
- **subscribers_for_last_30_days**: Number of new subscribers gained in the last 30 days.
- **created_year**: Year when the channel was created.
- **created_month**: Month when the channel was created.
- **Gross tertiary education enrollment (%)**: Tertiary education enrollment rate in the channel’s country.
- **Population**: Population of the country where the channel is based.
- **Unemployment rate**: Unemployment rate in the country.
- **Urban_population**: Percentage of the population living in urban areas.
- **Latitude/Longitude**: Geographical coordinates of the channel's country.

## Data Cleaning
The dataset had missing or inconsistent values, before conducting any analysis, the dataset was cleaned to ensure accuracy and consistency. The following steps were performed:

1. **Dropping Unnecessary Columns**: Columns such as "Abbreviation", "created_month", "Latitude", and "Longitude" were dropped as they were not relevant to the analysis.
2. **Handling Missing Data**: Missing values in the columns 'Country', 'created_year', and 'channel_type_rank' were dropped, while columns like 'subscribers_for_last_30_days' and 'video_views_for_the_last_30_days' were filled with median values. The 'category' and 'channel_type' columns were filled with the most frequent values (mode).
3. **Date Conversion**: The 'created_year' column was converted to a datetime format for consistency.

## Data Analysis and Insights
The project focuses on several key analyses to derive insights:

### 1. Top 10 YouTubers by Average Video Views
In this analysis, the top 10 YouTube Channels globally, along with their categories, were identified based on their average video views.

**Key Insights:** Channels leading in terms of average video views, largely due to their engaging content and viral appeal, belong to Shows, Music, and People & Blogs categories. This suggests that these categories have strong potential for gaining subscribers.

### 2. Average Views per Upload for Top 10 YouTubers
This analysis examines the average video views per upload for the top 10 YouTubers.

**Key Insights:** This analysis shows  whether quality or quantity drives engagement i.e whether focusing on fewer, high-quality videos or high-frequency uploads has a noticeable impact on the views per video.

### 3. Relationship Between Subscribers and Video Views
This scatter plot explores the relationship between a channel’s number of subscribers and its total video views (video performance).

**Key Insights:** A strong positive correlation between subscribers and video views indicates that channels with more subscribers tend to have more views on average. However, outliers (with high subscribers but low views) might represent inactive or contentless channels.

### 4. Average Video Views and Subscribers by Category
Bar charts were used to compare average video views and subscriber counts across different YouTube categories.

**Key Insights:** Categories such as Shows, Trailers, and Film & Animation have the highest subscriber counts, indicating their broad appeal, while Science & Technology and Travel & Events categories have fewer subscribers but can cater to niche interests, offering a dedicated, loyal audience. This suggests that targeting broad categories may provide faster growth for creators, while specializing in a niche could build a more engaged audience over time.

### 5. Monthly and Yearly Earnings Across Categories
This analysis shows how YouTuber earnings vary across categories, focusing on both monthly and yearly earnings.

**Key Insights:** Categories like Shows and Music offer high earnings potential, with many channels in these categories achieving significant monthly and yearly revenue. However, niche categories such as Travel & Events and How-to & Style may have smaller earnings potential due to fewer views, but can still offer profitable opportunities if creators have loyal audiences. There exists a wide range between lowest and highest earnings which shows that a channel’s revenue depends heavily on its popularity and engagement.

### 6. Top Countries with the Most Popular YouTube Channels
This analysis identifies the top countries with the most popular/successful YouTube channels.

**Key Insights:** USA, India, and Brazil are the top countries in terms of popular channels, largely due to their large populations, high internet penetration, and active creator communities, indicating strong digital content markets in these regions. Creators looking to grow their channels can consider focusing on these regions or tailoring content to cultural preferences and language to engage these large markets.

## Conclusion
This analysis highlights key insights into the factors that drive YouTube channel success, focusing on metrics like video views, subscriber count, earnings, and geographical distribution. By understanding the relationship between these factors, content creators can make informed decisions about their content strategy. 

By using this data, YouTubers and brands can tailor their strategies to optimize growth, increase engagement, and boost monetization opportunities. Whether you're a creator or a marketer, these insights can guide you in maximizing your channel's performance .








