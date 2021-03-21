# Data Analysing and Exploration 
This repository contains jupyter notebooks that provides data analysis on public datasets.

# Getting started
* Download Anaconda. We recommend downloading Anaconda’s latest Python 3 version (currently Python 3.5). https://www.anaconda.com/
* Install the version of Anaconda which you downloaded, following the instructions on the download page.

For experience Python users, you can install Jupyter using pip.
Important! Jupyter installation requires Python 3.3 or greater.

Install Jupyter using Python’s package manager, pip, instead of Anaconda. 
* Ensure that you have the latest pip; older versions may have trouble with some dependencies. `pip3 install --upgrade pip`
* Install Jupyter notebook using `pip3 install jupyter`

The analysis is in the jupyter notebook **netflix_insights.ipynb**.<br/>
The dataset used is in the file **netflix_titles.csv**.<br/>
Both are  included in this repository.

# Business Understanding
I am a big fan of Netflix! I think everybody is especially during this pandemic situation, I would say it has helped me, my family and friends stay calm and sane in this crazy state we are in. At work it also became a means of bonding with co-workers and helps break the ice by sharing stories on the latest movie or shows they’ve watched during video calls and virtual coffee sessions.

Netflix is in the business of entertainment and it does it by streaming movies and shows of different genres for a subsription fee. It would be interesting to see the diversity of the content it produces base on it's current data.

# Data Understanting- Netflix TV Shows and Movies
The dataset used for this analysis is the netflix tv shows and movies from Kaggle https://www.kaggle.com/shivamb/netflix-shows, which consists of tv shows and movies available on Netflix as of 2019.

There are very interesting features with the dataset and after looking at it I got really excited and come up with this questions:
1. Who is the director with the most movies/shows directed?
2. Who is the actor/actress with the most number of shows/movies casted in
3. Which country produced the most content
4. What is the longest running TV Show
5. What movie has the longest running time.

# Data Preparation
I have used the following python libraries for this analysis.
1. pandas and numpy for data wrangling
2. seaborn and matplotlib for data visualization

The analysis is in the jupyter notebook **netflix_insights.ipynb**, which is included in this repository.

The dataset used came from Kaggle www.kaggle.com https://www.kaggle.com/shivamb/netflix-shows

Base on the questions that I have come up for this dataset, the features that would give us the answers would be coming mostly from the director,country, title and cast columns. After inspecting the data I needed replace the country and ratings column with the mode and drop the other fields that do not have any values and will not have a big effect on the questions that we want to answer. I also needed to split the cast and duration columns to be able to answer the 1,4 and 5th questions.
# Modeling
I did not use any machine learning model for this analysis , descriptive statistics would suffice for the questions being asked.
# Evaluation
Using descriptive statistics , most of the questiongs raised were answered. Below is the summary.
1. Who is the director with the most movies/shows directed? **Tie between Raul Santos and Jan Suter**
2. Who is the actor/actress with the most number of shows/movies casted in? **Anupam Kher (Indian Actor)**
3. Which country produced the most content? **United States followed by India**
4. What is the longest running TV Show? **Grey's Anatomy**
5. What movie has the longest running time.? Black Mirror: Bandersnatch **(312 minutes or roughly 5 hours)**
# Setting Out
I have discussed the results of this analysis in this medium post [Wow I did not know that about Netflix](https://sonnygob.medium.com/).
