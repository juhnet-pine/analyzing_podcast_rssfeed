# analyzing_podcast_rssfeed
## Goal of Project
1. The overall goal of the project was to analyze the episode descriptions from the history podcast “Stuff You Missed in History Class”. 
2. I wanted to answer the following questions:
      * How many of the episodes focus on: Western vs Non-western history?, Female vs Male history?, White people, minorities/people of color, and LGBTQ? 
3. I chose this project because I love podcasts and learning. I also wanted to find a way to help one of my favorite podcasts in improving representation among their episodes, and, thus increase their number of listeners. 
4. So, when I have completed this project, my intention is to send the results to the podcast hosts, so they can have a better picture of where there is a dearth in representation in their show. 

## Process--Tools Used
1. Python. 
* I used Python to scrape the RSS feed of the podcast a website in XML, containing all the information about the podcast episodes like title, descriptions, publication date, etc. I looped through each episode on the feed and extracted the information I needed. 
* After scraping, I had to clean and prepare the unstructured data. I ended up scraping over 1800 episodes. New episodes are added each week, so my code will work for a long time, unless they change the URL to the RSS feed. 
2. SpaCy
* Because I was analyzing unstructured data, I had to use a Natural Language Processing software. Named Entity Recognition in spaCy was a good tool for this task. What this means is that spaCy has already classified certain entities like geopolitical entities such as countries. It uses context to infer what is a country, state, or city. I extracted these geopolitical entitiesfrom the descriptions for the first question of my project (How many episodes focus on Western vs. Non-western?)
3. Excel
* After looping through each episode description, I put the data into Excel so I could label countries as Western or Non-western. 
4. Tableau and Python 
* I used both Python and Tableau to do data visualization tasks, which can be seen in the PowerPoint presentation as well as the jupyter notebooks. 
