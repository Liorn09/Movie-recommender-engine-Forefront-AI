# Streamlit-based Recommender System
#### EXPLORE Data Science Academy Unsupervised Learning Project

## 1) Overview

![Movie_Recommendations](resources/imgs/Image_header.png)


#### 1.1) What is a Recommender System?

[![What is an API](resources/imgs/What_is_a_recommender_system.png)](https://youtu.be/Eeg1DEeWUjA)

Recommender systems are the unsung heroes of our modern technological world. Search engines, online shopping, streaming multimedia platforms, news-feeds - all of these services depend on recommendation algorithms in order to provide users the content they want to interact with.

At a fundamental level, these systems operate using similarity, where we try to match people (users) to things (items). Two primary approaches are used in recommender systems are content-based and collaborative-based filtering.  In content-based filtering this similarity is measured between items based on their properties, while collaborative filtering uses similarities amongst users to drive recommendations.

Throughout the course of this Sprint, you'll work on defining this brief explanation further as you come to understand the theoretical and practical aspects of recommendation algorithms.     

#### 1.2) Description of contents

Below is a high-level description of the contents within this repo:

| File Name                             | Description                                                       |
| :---------------------                | :--------------------                                             |
| `recommender_base.py`                 | Base Streamlit application definition.                            |
| `recommenders/collaborative_based.py` | Simple implementation of collaborative filtering.                 |
| `recommenders/content_based.py`       | Simple implementation of content-based filtering.                 |
| `resources/data/`                     | Sample movie and rating data used to demonstrate app functioning. |
| `resources/models/`                   | Folder to store model and data binaries if produced.              |
| `utils/`                              | Folder to store additional helper functions for the Streamlit app |

