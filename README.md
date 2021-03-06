# Drake Meets World
###### *Exploring Drake's growth through analysis of his lyrics*

![drake_facebook](https://user-images.githubusercontent.com/40477918/43699918-99f67422-9905-11e8-897c-128b13153f82.png)

## Summary
I love Drake. I think the main motivation for me to do this project was to disect what it is about Drake that has made him so successful and a staple of almost every radio station. I focused on analyzing Drake's lyrics and how complex and emotional he has been throughout the years. As I generated the metrics and visualizations, I explored where my favorite songs fell in and what topics I related to the most.

What I've learned is that he's just more relatable than other popular artists. He's an emotional curly haired person (like me), trying to figure out his life. Below, I briefly listed out the process I went through to complete my analysis and some insights I generated.

#### Process
1. Scraped lyrics using BeautifulSoup
2. Created metrics for Sentiment and Lexical Complexity
3. Created visualizations for metrics using Plotly
4. Conducted topic analysis using NMF Model
5. Created wordcloud of lyrics
6. Clustered songs using KMeans Clustering
7. Clustered songs using Ward Clustering

#### Before you go through the rest of this repository, I have a few suggestions:
1. Open the nbviewer link instead so you can hover to see specific songs: https://goo.gl/xqMXh5
2. Listen to Drake while you peruse. I have a spotify playlist ready for this occasion: https://goo.gl/uKVLRy

## A Few Insights

##### Note: 
 - Sentiment Score is how positive or negative the lyrics are. The score can be negative; however, since this is average by year, the numbers are positive.
 - I defined lexical complexity as the number of unique words out of the total words.
![avg_by_year](https://user-images.githubusercontent.com/40477918/44005307-4ea5a526-9e26-11e8-8068-d1bbf6d28fdb.png)
#### Average Sentiment & Lexical Complexity by Year
+ The sentiment and lexical complexity of Drake's songs seem to move in the same direction through out the years.
+ 2015 had the lowest sentiment score and coincided with the year he released a collaborative mixtape with Future, "What A Time to Be Alive" which focused on dealing with personal demons and insecurities.
+ 2017-2018 had the highest lexical complexity at an average of 0.43. 2017 was the year he released "More Life" an album sprinkled with Jamaican slang (potentially contributing to the higher lexical diversity) and in 2018 he released Scorpion, an album of 25 songs. 

##### Note: 
 - OVO is Drake's record label and stands for "October's Very Own".
![wordcloud](https://user-images.githubusercontent.com/40477918/44005310-5c6580b4-9e26-11e8-83df-8a62378997f1.png)
#### Word Cloud
+ Based on the prominent "I'm", I get the sense while I love Drake a lot, Drake loves Drake even more (or at least talking about himself).
+ Combined with the topic analysis, the most common theme is girls! Whether it's singing about girls or singing to them.
    + In the topic analysis, I noticed most of the topics are emotional with words like "love", "hurt" and "lonely" and generally have the word "girl" or references to a girl (i.e. baby).
+ Overall, I think Drake just wants to talk about his feelings and maybe that's why I like him so much.
 
## Next Steps
+ Look at sentiment score & lexical complexity by featured artist and by performance in charts
+ Topic analysis by album
+ Visualize cities Drake has sang about (including related sentiment scores for the songs)
+ Visualize profits for albums/songs by artist featured

