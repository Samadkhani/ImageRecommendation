# ImageRecommendation

This repository contains the code for social image recommendation.


due to the expansion of the Internet and social networks, people are faced with a huge amount of dynamic information. Recommender systems have been emerged in order to improve the problem of the phenomenon of information abundance by analyzing the background of the user's behavior and extracting the user's interests and preferences. 

Our proposed method, consists of two main parts: feature extraction and deep reinforcement learning to learn the recommendation process. 
For feature extraction, we have three components: emotion analysis, personality recognition, and style detection.


# Dataset Description

we used four datasets. 
1) The Flickr Style dataset[45] for recognizing image style. The original dataset consisted of 80,000 images with style labels, and was classified into 20 labels. We could not collect all the images because some were unlinked from Flickr. In this study, 15 style labels are used, and we have 2900 images for each style
2) The data set introduced in [33] was utilized for emotion detection in images. It encompasses eight emotions, which include amusement, anger, awe, contentment, disgust, excitement, fear, and sadness. The version of the dataset we used contains fewer images than the original due to some images being lost. 
3) PsychoFlickr dataset is used for personality analysis [38]. A collection of 60,000 images tagged as favorites by 300 Pro Flickr users (200 randomly selected favorites per user). 
4) To evaluate image recommendation, we employ part of the dataset used in  [1]. We consider a collection of 4000 images belonging to 20 users from Flickr. For each user, there are 200 images tagged as favorites. 

You can download the desired dataset from its original reference or access the used data through the links added in the README file.

.mat files containing features extracted for different users: https://drive.google.com/drive/folders/12NZOqZeoZNMQloW1U-areoad_1dZS8H8?usp=sharing

Images of users used for recommendations : https://drive.google.com/drive/folders/1SmkafqPmFsFJkFekuUXx5ew8u8xLYAAX?usp=sharing

PsychoFlickr_DataSet: https://docs.google.com/spreadsheets/d/19QsXk87LJPEmuiubMAjlm1k3EsXWG6-i/edit?usp=sharing&ouid=101202414552093252061&rtpof=true&sd=true
Emotion_DataSet: https://drive.google.com/drive/folders/1jFcjXkudaiKBY6pGGTZoU0XK_e1e3OgD?usp=sharing



## How to Cite

If you use this work in your research, please cite it as follows:

Your Last Name, Your First Name. (2023). Your Project Title (Version 1.0.0) [Software]. Available from https://github.com/yourusername/yourrepository. DOI: xxxxxxx

For more details, see the CITATION.cff file in this repository.
