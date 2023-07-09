<h1 align="center">My Data Science Projects 🚀</h1>

Over the past few months, I've been self-studying data science skills during my free time and this repo contains all of my personal projects as a way to hone and showcase those skills. The projects are ranging from EDA, Machine Learning Projects and Tableau Dashboarding Projects.

<h2>🛠️ Technical Skills</h2>

**Programming:**</br>
<pre>
📌 SQL
📌 Python 
      ▫️ Pandas
      ▫️ Numpy
      ▫️ sklearn
</pre>

**Data Visualization:**</br>
<pre>
📌 Tableau
📌 matplotlib
📌 Seaborn
</pre>

<h2>💡Projects Preview</h2>

<h5 align="center">Keywords: Sklearn | Python | Pandas | Matplotlib | Seaborn | NLP | API | Tableau | Amazon RDS</h5>

👩‍💻 **Project 1: TED YouTube API Analysis**

*Description:* The objective of this project is to analyze the TED YouTube data by implementing API scraping technique on the YouTube Data API. I'll extract the data and then load it into a pandas dataframe so that further analysis can be done. Finally, a simple visualization using seaborn library will also be made to present the insights gathered by performing an exploratory analysis on the data.

*Data Source:* This project started by first creating a YouTube API Key which will be our credential to access the YouTube data. Once the API Key is generated, the documentation prepared by google is skeemed over to learn how to use the API Key in order to access different YouTube data. One more important key is the TED YouTube channel id that can be obtained from YouTube itself.

*Libraries:* 
- The google-api-python-client method is imported prior to this project so that I can make the API call.
- Pandas is use to build the dataframes, performing analytical tasks on the dataframes.
- Seaborn is a visualization libraries that are build on matplotlib and is used to visualize insights.
- NLP for human language processing in order to generate a wordcloud of the videos' titles.

*Sections Covered:*
- Data Acquisition
- Data Pre-processing/Data Cleaning
- Data Exploration & Visualization
- Cloud Database

*Data Visualization Preview:* 

![viz preview](https://user-images.githubusercontent.com/88192027/228398103-fcb56fab-eeba-4377-a328-8ff618edd784.png "Wordcloud for Video Title")

*Dashboard Preview:*

*Conclusions:*
- The violing plot is used as it shows the quantitative data across the categorical variable which is the channel itself. From the plot, we can say that although most of TED's videos receive relatively around the same number of views, there are videos that have way more number of views than the rest. This result indicates that, the outliers may affect the average number of views and the next step is to identfy those videos.
- Next, a barplot is used to visualizes the numbers. From the plot we can deduce that the best performing videos on TED channel in relation to the number of views is titled "Tim Urban: Inside the mind of a master procrastinator" with over 52 million views.
- Scatter plot is used to study the relationship between the number of views with likeCount and commentCount. From the plot, it can be said that a video doesn't necessarily have high like and comment count even when it has higher views.
- A scatter plot is used to observe relationships between the viewCount and duration_by_secs variables. It can be seen that most videos have shorter duration and this helped their views performance, since the long duration videos are having less views.
- In this analysis, the number of videos uploaded each month is studied. First, the dataset need to be grouped and sorted by month. Thus, the data is group by each month and we can see the size of that data monthly. Since python don't know the order of the month, we need to manually sort the order. Then, the index is set categorically based on month. A barplot is used to visualize everything, and we can see that more videos were uploaded in Jan while less videos were uploaded in Aug.
- The wordcloud is used to find the most common keyword from the videos title. Hence, will give us better understanding on which topics were uploaded most frequently.

👩‍💻 **Project 2: Credit Card Fraud Detection Analysis**

*Description:*

*Data Source:* [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

*Libraries:* 
- Pandas
- Seaborn
- Sklearn model selections (*GridSearchCV & cross_val_score*)
- Sklearn ML libraries (*linear_model, svm, neighbors & tree*)

*Sections Covered:*
- Data Pre-processing/Data Cleaning
- Data Exploration
- Undersampling Skewed Dataset
- ML Model Selection
- Accuracy Score using AUPRC

*Data Visualizations Preview:*

![viz preview](https://github.com/alyani-fr/DataSciencePortfolio/assets/88192027/750a610d-7b64-4937-801a-4124d0c8a686)


*Conclusions:*


👩‍💻 **Project 3: Amazon Best-Seller Books Analysis**

*Description:*

*Data Source:*

*Libraries:*

*Sections Covered:*

*Data Visualizations Preview:*

*Conclusions:*

<h2>💡Tableau Dashboard Projects</h2>

👩‍💻 **Project 1: Netflix Movies & TV Shows Dashboard**</b>

*Description:* The aim for this project is to create a Tableau dashboard that can help users gain insights of an existing dataset for Netflix's movies and tv shows. The dashboard will show visualizations of the numbers of movies and tv shows being distributed on Netflix per year, by genres, countries, and ratings. The total number of each movies and tv shows dstribution will also be visualized to compare the statistics between the two.

*Data Source:* [Netflix Dataset](https://github.com/DataScienceRoadMapDSRM/Tableau-Dashboards-info/raw/main/netflix_titles.csv)

*Dashboard Preview:* 

![Netflix Dashboard](https://user-images.githubusercontent.com/88192027/227789462-c6fb6f37-a2df-4917-ba5d-6d0af1140be8.png "Dashboard Preview")

🔗 [Dashboard Link](https://public.tableau.com/views/NetflixDashboard_16794243269210/NetflixDashboard?:language=en-GB&:display_count=n&:origin=viz_share_link)

👩‍💻 **Project 2: Covid-19 Worldwide Vaccine Tracker**</b>

*Description:* The purpose of this project is to create Covid-19 vaccination tracker to see how they are performing across the world. The users will be able to see the different distributions between percentage of people that are fully vaccinated and partially vaccinated for every country and if the GDP per capita of a country affect the vaccination programs. 

*Data Source:* [Covid-19 Vaccine Dataset](https://docs.google.com/spreadsheets/d/1oMrHuOkbXAoXibN6UzHUkNrwqvjQVFOU8CuqFMVZiUo/edit?usp=share_link)

*Dashboard Preview:* 

![Covid-19 Vaccine Tracker](https://user-images.githubusercontent.com/88192027/227790302-79d86980-c268-46c8-993a-d8eb1c9ac529.png "Dashboard Preview")

🔗 [Dashboard Link](https://public.tableau.com/views/Covid-19VaccineTracker_16794478786730/covid-19vaccinetracker?:language=en-GB&:display_count=n&:origin=viz_share_link)
