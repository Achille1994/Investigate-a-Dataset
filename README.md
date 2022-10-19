# Project: Investigate a Dataset 
For this project, I decided to analyse the TMDb movie data set provide by Kaggle <a href="https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub"> dataset<a>. This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. I analyze a dataset and communicated my findings about it. I used the Python to explore TMDb movie data. But what determines if a movie is considered as good or bad? There could be several factors influencig the quality of a movie, as for example the budget, genre, etc. This little project helped the author to improve his data analytics skills and explore some of the success criteria for movies.

# Questions to answer
For this data set, I will answer some interesting questions :
- What is the best runtime for a movie ?
- Which genre has the most movies ?
- Which genres are most popular?
- Which genre has the longest average runtime ?
- Which genre has the longest average vote count ?
- Which genre has highest average budget ?
- Which genre has highest average revenue ?
- Which genre has highest average profit ?
- Which release year has the highest revenue and budget ?
- Which release year has the highest average Profit?
- Which release year has the highest average Popularity ?
- Which release year has the highest average vote count ?
- What kinds of properties are associated with movies that have high revenues?
- Which genres are most popular from year to year?

Details
We have organized the current notebook into the following sections:
## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

# Exploratory Data Analysis

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis

# Finding
Please you can see my notebook for all answer to my questions

# Tools
Python, Pandas, Numpy, Matplotlib, StatsModels, Scipy Jupyter Notebook
# Conclusions
Firstly, if we are not take year in account we can conclude that :

- The best runtime for a movie is around 100 min
- The Drama genre has the most movies than others genres
- The war genre has the longest average runtime than others genres
- This mean that the Adventure genre is more popular
- The western,Fantasy and Adventure genres have highest average budget,followed by Action,Animation and Familly genres
- The Adventure genre has highest average revenue, followed by Fantasy genre
- The Adventure,Fantasy genre has highest average profit,followed by Familly and animation genre

Secondly, If we are take year in compte we can conclude that :

- Average Budget, average popularity, average revenue, average vote count and average profit vary over year and it characteristics was very low from 1985 and 2015
- The profit is highly related to the popularity, budget, revenue, and vote count
- The runtime isn't highly related to the popularity, budget, revenue, and vote count

# Limitations
The gbobal analyse show that the profit was very low when year grown. In reality, it'is difficult to predicit the behaviour on profit over the year because, the profit vary over year. But, deep analyse on correlation is the way where the company can focus efforts to make more profit over the year
