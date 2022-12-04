### Music app churn analysis

#### Description
Based on a dataset from the Sparkify music streaming app (like Spotify), analyze the data and identify which users are likely to churn.

#### Necessary information
The libraries which are necessary to run the code are: 
- pyspark.sql
- pyspark.ml
- py4j.java_gateway 
- numpy
- pandas
- matplotlib
- time
- datetime

#### Files in project: 
###### notebook
notebook_sparkify_clean.ipynb: main application

###### data
mini_sparkify_event_data.json: 125 MB dataset
sparkify_log_small.json 23 MB dataset used in the project!
sparkify_log_smallest.json 4 MB dataset

###### other
README.md: you're in it!
LICENSE: license file

###### Known bugs
The churn prediction machine learning models need more tunings since the fit scores seem too good to be true!

Blogpost: https://medium.com/@KwoVadis/sparkify-music-app-churn-analysis-93a4fe34c2e8

(C) MIT License

#### Acknowledgements:
###### Definition of metrics:  
Huilgol, Purva. 3 Sep., 2020. Precision vs. Recall — An Intuitive Guide for Every Machine Learning Person. https://medium.com/analytics-vidhya/precision-vs-recall-an-intuitive-guide-for-every-machine-learning-person-796a6caa3842
Zeya, LT. 9 Nov., 2021. Precision and Recall Made Simple. https://towardsdatascience.com/precision-and-recall-made-simple-afb5e098970f 
Pandkar, Niraj. GitHub Sparkify project. Last save: 24 March, 2019. Accessed: 4 December, 2022. https://github.com/nirajpandkar/sparkify/blob/master/Sparkify.ipynb
###### Help in spark:
https://www.udacity.com/ 
https://sparkbyexamples.com
https://spark.apache.org

