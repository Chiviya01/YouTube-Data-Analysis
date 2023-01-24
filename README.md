# YouTube-Data-Analysis

Spark Hive PySpark Hadoop MapReduce

___
_How to get into trends? How fast can a video go viral? Do trending videos with negative sentiment refer to a bigger number of dislikes? Any common trends in English-speaking countries?_
__ 

### Project Status
Project is: _complete_

_This project was completed in collaboration with [swiatej](https://github.com/swiatej)_

## Table of Contents
* [General Info](#general-information)
* [Project Components](#project-components)
* [Room for Improvement](#room-for-improvement)

## General Information
This project is about analysing trending videos on Youtube over the period of 2 years, from 2020 to November 2022. It highlights differences in tendencies over time in trending videos over the three English-speaking countries (USA, Canada, GB). Analysis include such aspects as:
* How long does it takes a video to reach the trending page – i.e. how many days it takes from the day the video was published till the moment it became trending.
* Semantic Analysis of video title. Correlation between semantic meaning of a video title and the number of its likes / dislikes.
* Seasonality in trending videos in 3 countries.

## Technologies used
The project was completed in **Spark**. The cluster was deployed on Spark. 
Data cleaning and simple analysis in **Hive**.
More complex Data Analysis, Natural Language Processing and Machine Learning tasks were completed in **PySpark**. 

### Project Components
1. [**Report**](). A pdf document that includes the general information, inspiration, dataset description, summary of the analysis and conclusions of the project. 
2. **Dataset** compiles data on daily trending YouTube videos. The dataset is updated daily (link here: https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset). For this project the newest version of the dataset was used, dated 12/08/2020 - 1/12/2022. Only data from English-speaking countries was used - the USA, Great Britain, and Canada. Each region’s data is in a separate file. The video categories are the same for all regions and are contained in a .json file. 
3. [**Simple Analysis in Hive**](). It is a Jupyter Notebook that includes initial EDA of data and conclusions driven from it.
4. [**Complex Data Analysis, NLP, ML in Pyspark**](). It is a Jupyter Notebook that includes Data Visualisation, Complex EDA, Sentiment Analysis and ML.
5. **Visual Data Representation** In this project repository 3 data visualisations can be found. [GB]() [Canada]() [USA]() Each png image is a visual data representation for each of the countries, data from which was used for this project.
