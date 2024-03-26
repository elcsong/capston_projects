# TikTok Project Executive Summary
#### the TikTok Claims Classification Project

## Issue / Problem
The TikTok data team seeks to develop a machine learning model to assist in the classification of claims for user submissions. To begin, the data team needs to organize the raw dataset and prepare it for future exploratory data analysis.

## Response
The data team performed a preliminary investigation of the claims classification dataset with the aim of learning important relationships between variables.
Given the ask for a classification of user claims, the data team looked at the counts of claims and opinions in order to understand the count of each type of video content.

## Impact
The impact of this preliminary analysis will be evident in the next steps. In order to understand the impact of user videos, the data team identified two important variables to consider. The variables video_duration (in seconds) and video_view_count are both crusial factors to consider for future prediction models.

## Understanding the DATA
After reviewing the provided dataset, the variable claim_status seemed particularly useful, given the client's proposed project. The following screenshots  show important points of analysis required to understand the claim_status variable.
`data['claim_status'].value_counts()`
`claim 9608`
`opinion 9476`
`Name: claim_status, dtype: int64`

**Note**: The counts of each claim status are quite balanced. There are 9,608 claims and 9,476 opinions.

## Engagement Trends
The data team considered viewer engagement with each video in the claim and opinion categories. In order to understand viewer engagement, the data team considered the view count. The mean and median view count show the impact of each category of video. Specifically, the mean and median view counts for both categories show the association between content (claim or opinion) and the video views.
### Claims:
	* Avg. view count of videos with 'claim' : 501029.4527477102
	* Median view count of videos with 'claim': 5015555.0

### Opinions:
	* Avg. view count of videos with 'opinion' : 4956.43224989447
	* Median view count of videos with 'opinion' : 4953.0

## Key Insights
* There is a near equal balance of opinion versus claims. With this understanding, we can proceed with our future analysis knowing that there is a fairly balanced amount of claims and opinions for the videos included withing this dataset.
* With the key variables idenfified and the initial invesgigation of the claims classification dataset. the process of exploratory data analysis can begin.
