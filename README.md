# Youtube-Trending

Data Analysis on USA YouTube videos in 2017-2018, for 40949 records.


![image](https://user-images.githubusercontent.com/43325087/45801187-b2671e80-bc78-11e8-9cd6-39c0ebe29b0f.png)


About the data:
The dataset website can be find in the resource. There are 40949 rows and 16 columns in total in the USvideos.csv, containing video_id, title, category_id, tags, time about publish and trending, and most important -- audiences' reflection stats. Another useful file contains category name, mapping to the category_id.

Here I demonstrate the trending of YouTube in USA on:
1)Distribution of categories, rates.
2)Visulization of categories and audiences' reflection, such as views, commonets,likes etc.
3)Correlation betweeen Youtube audiences' actions
4)Time of publishing and trending

Applied packpage:
1)pandas
2)numpy
3)matplotlib.pyplot
4)seaborn
5)json
6)WordCloud

Key finding:
1)The counting on views decides the virality of a video, plus counting on likes decide the popularity of a videos. 
2)The counting on dislikes and comments don’t influence that much on the virality and popularity. 
3)In this dataset, the most welcomed category are Entertainment, Music, Howto & Style, News & Politics, Comedy and Sports, and the most influenced channel are almost from above category. 
4)The best publish time for a youtuber would be winter, either day, while better before 15th.

Comment:
I really enjoy this project. This could be my favorite project while learning at Udacity. It’s also my last project. Trying to be a data analyst, I always regard plots and graphs as the best tool to explain insights. Through this chapter and the project, I know how to choose a better plot, how to make use of proper maker and color, how to polish graph for a more accurate explanation. I appreciate everything here I learn.

Resource:
https://www.datacamp.com/community/tutorials/wordcloud-python
https://www.kaggle.com/datasnaek/youtube-new
https://stackoverflow.com/questions/18674064/how-do-i-insert-a-column-at-a-specific-column-index-in-pandas
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html

