# Tiktok-project-Google-Coursera
This project is the capstone for Course 2 of the Google Data Analytics Python Certification. It focuses on understanding and preparing data for exploratory data analysis (EDA) to support the development of a claims prediction model for the Tiktok App.

# Project Overview
TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider in a timely manner. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

#This project includes the following tasks:
Construct a dataframe from the churn dataset.
Review the data types of each column.
Generate descriptive statistics to understand the dataset better.
Prepare the data for further analysis.


#Dataset Overview
The dataset consists of 19,383 rows and 12 columns. Each row represents a different published TikTok video in which a claim/opinion has been made.. Below is a breakdown of the dataset:

- **#** (int) - TikTok assigned number for video with claim/opinion.
- **claim_status** (obj) - Whether the published video has been identified as an “opinion” or a “claim.” In this dataset, an “opinion” refers to an individual’s or group’s personal beliefs or thoughts. A “claim” refers to information that is either unsourced or from an unverified source.
-video_id (int) - Random identifying number assigned to video upon publication on TikTok.
-video_duration_sec (int) - How long the published video is measured in seconds.
-video_transcription_text (obj) - Transcribed text of the words spoken in the published video.
-verified_status (obj) - Indicates the status of the TikTok user who published the video in terms of their verification, either “verified” or “not verified.” 
-author_ban_status (obj) - Indicates the status of the TikTok user who published the video in terms of their permissions: “active,” “under scrutiny,” or “banned.”
-video_view_count (float) - The total number of times the published video has been viewed.
-video_like_count (float) - The total number of times the published video has been liked by other users. 
-video_share_count (float) - The total number of times the published video has been shared by other users.
-video_download_count (float) - The total number of times the published video has been downloaded by other users. 
-video_comment_count (float) - The total number of comments on the published video. 


#Assignment Goals
The main tasks of this project are to:

Build a dataframe for the TikTok dataset
Examine data type of each column
Gather descriptive statistics
