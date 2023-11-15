# ImageRecommendation

This repository contains the code for social image recommendation.


due to the expansion of the Internet and social networks, people are faced with a huge amount of dynamic information. Recommender systems have been emerged in order to improve the problem of the phenomenon of information abundance by analyzing the background of the user's behavior and extracting the user's interests and preferences. 

Our proposed method, consists of two main parts: feature extraction and deep reinforcement learning to learn the recommendation process. 
For feature extraction, we have three components: emotion analysis, personality recognition, and style detection.


# Dataset Description

we used four datasets. 
1) The Flickr Style dataset[4] for recognizing image style. The original dataset consisted of 80,000 images with style labels, and was classified into 20 labels. We could not collect all the images because some were unlinked from Flickr. In this study, 15 style labels are used, and we have 2900 images for each style
2) The data set introduced in [2] was utilized for emotion detection in images. It encompasses eight emotions, which include amusement, anger, awe, contentment, disgust, excitement, fear, and sadness. The version of the dataset we used contains fewer images than the original due to some images being lost. 
3) PsychoFlickr dataset is used for personality analysis [3]. A collection of 60,000 images tagged as favorites by 300 Pro Flickr users (200 randomly selected favorites per user). 
4) To evaluate image recommendation, we employ part of the dataset used in  [1]. We consider a collection of 4000 images belonging to 20 users from Flickr. For each user, there are 200 images tagged as favorites. 

You can download the desired dataset from its original reference or access the used data through the links added in the README file.

.mat files containing features extracted for different users: https://drive.google.com/drive/folders/12NZOqZeoZNMQloW1U-areoad_1dZS8H8?usp=sharing

Images of users used for recommendations : https://drive.google.com/drive/folders/1SmkafqPmFsFJkFekuUXx5ew8u8xLYAAX?usp=sharing

PsychoFlickr_DataSet: https://docs.google.com/spreadsheets/d/19QsXk87LJPEmuiubMAjlm1k3EsXWG6-i/edit?usp=sharing&ouid=101202414552093252061&rtpof=true&sd=true
Emotion_DataSet: https://drive.google.com/drive/folders/1jFcjXkudaiKBY6pGGTZoU0XK_e1e3OgD?usp=sharing



# How to Cite

If you use this work in your research, please cite it as follows:

Somaye Ahmadkhani, Mohsen Ebrahimi Moghaddam. (2023). A social image recommendation system based on deep reinforcement learning. Available from https: https://github.com/Samadkhani/ImageRecommendation/blob/main/README.md


# References

1.	Lovato, P., et al., Faved! biometrics: Tell me which image you like and I'll tell you who you are. IEEE Transactions on Information Forensics and Security, 2014. 9(3): p. 364-374.
33.	You, Q., et al. Building a large scale dataset for image emotion recognition: The fine print and the benchmark. in Proceedings of the AAAI conference on artificial intelligence. 2016.
38. Segalin, C., D.S. Cheng, and M. Cristani, Social profiling through image understanding: Personality inference using convolutional neural networks. Computer Vision and Image Understanding, 2017. 156: p. 34-50.
45.	Karayev, S., et al., Recognizing image style. arXiv preprint arXiv:1311.3715, 2013.
