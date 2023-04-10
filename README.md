# YouTube API Project - CBC News Analysis
***

## Introduction

CBC News is a 'national public news and information service' that keeps Canadians up-to-date with important information in connection with people's communities and the world around them. Recently, since inception in October 1972, CBC News Marketplace celebrated its' 50th season on air. I enjoy the CBC Marketplace videos and value the awareness and investigative work completed by the team involved. Out of curiosity, I decided to analyze the CBC News YouTube Channel using the YouTube Data API and analyze CBC News Marketplace video statistics in-depth and explore which videos attracted the most user consumption and engagement, in the form of video views, likes, and comments.

I will aim to answer the following questions:
 
1. How does the CBC News YouTube channel compare to other Canadian News YouTube channels?
2. What is the most popular CBC Marketplace video?
3. Is there a relationship between the number of views and the number of likes in a video? Title length? Comments? Duration? Tags?
4. How often are the videos published throughout the week? 
5. What types of topics are the videos covering, based on analysis of video titles?

## Methods

Using the YouTube Data API guidelines, I obtained authorization credentials for API requests of YouTube's various entities. In order to retrieve statistics data for individual videos, the following steps were implemented in this notebook:

1) Retrieve unique identifier information on specific channels by accessing the YouTube channel of interest and reviewing the HTML source code.
2) Using the API to retrieve specific channel and playlist resource properties information, such as the unique video identifier information.
3) Using the API to retrieve video properties and statistics information with the unique video ids.

Upon completing the above steps, a dataset of the videos information in the CBC Marketplace playlist were created and processed for cleaning and enrichment prior to downstream analyses.
