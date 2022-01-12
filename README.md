<img width="1165" alt="Screen Shot 2022-01-12 at 16 58 57" src="https://user-images.githubusercontent.com/68494141/149086952-211270a3-98fe-4f01-a6d2-9d3361923185.png">

# A Quantitative Investigation of 5 of Hollywood's Leading Men
## ~ Examining the quantity, revenue, ROI, and vote score of movies starring Robert Downey Jr., Nicolas Cage, Leonardo DiCaprio, Tom Cruise, and Brad Pitt between 1986 and 2015 ~
#### [_Udacity - Data Analyst Nanodegree:_](https://www.udacity.com/course/data-analyst-nanodegree--nd002) _Project 2 - Introduction to Data Analysis_
## Table of Contents

1. [Introduction](#intro)
2. [Requirements](#requirements)
3. [Project Movitivation](#motivation)
4. [Key Files](#files)
5. [Summary of Findings](#summary)
6. [Acknowledgements](#acknowledgements)

### 1. Introduction<a id="intro"></a>
I choose to do my first ever project using the TMDb movie data set. It contains information from about 10,000 movies gathered from [The Movie Database (TMDb)](https://www.themoviedb.org/), including user ratings and revenue. I choose this project and this database because of my interest in movies.

This is my very first data science project so the types of questions I thought of were perhaps somewhat amateurish. After opening the database and peaking around at the columns and their contents, I brainstormed what questions I thought were interesting to investigate. Initially, I came up with these questions (for example):

- Which film has the best budget to revenue ratio?
- What is the average runtime for comedies versus dramas?
- Which production companies make the highest-grossing films?
- Which year(s) had the highest-grossing films?
- What is the most common actor combination?

I refined my questions and narrowed my scope after realizing my skill level limited me as to what I could do. So rather than opting for a general but scattered investigation as I've seen in some similar projects, I chose to focus on just my five favorite actors and compare them using various metrics and figure out who was, out of those five, the _best_ actor for Hollywood. I mainly looked at these four metrics: quantity of movies, revenue of movies, return on investment (ie, value) of movies, and popularity. My four questions are the following:

**1. Who had the highest movie output and movies output rate between 1985 and 2015?**\
**2. Who had the highest average revenue and highest total revenue?**\
**3. Who had the highest average revenue ROI and what is the correlation between ROI and revenue?**\
**4. Who had the highest vote average and what is the correlation between vote average and revenue?**

### 2. Requirements<a id="requirements"></a>
This project was created in a Jupyter Notebook made available via Anaconda and written in python. 
The following versions of languages and libraries were used in creating this project:
- matplotlib==3.5.1
- pandas==1.3.5
- scipy==1.7.3
- seaborn==0.11.2

### 3. Project Motivation<a id="motivation"></a>
As per Udacity, the purpose of this project was to:

- Know all the steps involved in a typical data analysis process
- Be comfortable posing questions that can be answered with a given dataset and then answering those questions
- Know how to investigate problems in a dataset and wrangle the data into a format you can use
- Have experience communicating the results of your analysis
- Be able to use vectorized operations in NumPy and pandas to speed up your data analysis code
- Be familiar with pandas' Series and DataFrame objects, which let you access your data more conveniently
- Know how to use Matplotlib to produce plots showing your findings

### 4. Key Files<a id="files"></a>
- `tmdb-movies.csv`\
Provided by Udacity, this dataset was (partially) cleaned from original data on [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata). This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
- `Investigate_a_Dataset_Udacity_Project_2.ipynb`\
This Jupyter Notebook contains all code from importing, assessing, wrangling, visualizing, and reporting. 

### 5. Summary of Findings<a id="summary"></a>
Please see [`Investigate_a_Dataset_Udacity_Project_2.ipynb`](https://github.com/keenan-cooper/A-Quantitative-Investigation-of-5-of-Hollywoods-Leading-Men/blob/main/Investigate_a_Dataset_Udacity_Project_2.ipynb) for full analysis by actor and visualizations leading to the findings.

- **Tom Cruise** takes the crown as the best for Hollywood out of these five actors. Based on average and total revenue and best ROI by nearly double, he has filled pockets of Hollywood executives the most and does it consistently with the best value. He does so enjoyably too, scoring a 6.5 vote average, just behind Dicaprio and Pitt, meaning that the action movies he stars in not only make a lot of money but are well-received. In particular is 80s movies "Top Gun", "Rain Man", and "Born on Fourth of July" were incredibly well-received based on their stellar ROI value.

<p align="center">
  <img width="1003" alt="Screen Shot 2022-01-12 at 18 44 14" src="https://user-images.githubusercontent.com/68494141/149113337-2eaed9a3-ee23-49af-947b-3e9d20ebcad2.png">
</p>

### 6. Acknowledgements<a id="acknowledgements"></a>
This project was completed as part of the Udacity's [Data Analyst Nanodegree](https://github.com/keenan-cooper/WeRateDogs-Twitter-Data-from-2015-to-2017/files/7847764/nd002-syllabus_2018-June_v9.pdf).\
All data provided and sourced by [Udacity](https://www.udacity.com). 
