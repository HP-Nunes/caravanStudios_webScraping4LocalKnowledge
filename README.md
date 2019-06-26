<a href="https://www.caravanstudios.org/about" target=_blank title="Caravan Studios"><img align="left" width="200" height="200" src="img/csLogo.png" target=_blank/></a>
# <center>EU Commission Grant Exploratory Research: Polish Discourse on Social Media on Air Pollution</a></center>
<br>

## Background

As the Citizen Science Research Intern at Caravan Studios, I was tasked to explore the air pollution discourse online for Poland, the EU country with the worst air pollution record. My aim was to 1) gain a temporal and spatial understanding of the interest about air pollution in Poland and 2) have a sense of the popular discourse about air pollution. To expand on the latter: how did Poles express themselves about air pollution (whom did they blame, how did they describe the impact of pollution on daily life etc.). 

I investigated different social media sources, including: Twitter, Facebook, Reddit, Wykop, NK.pl, and Google Trends. Here's the summary of my outputs per sources below:

* <b>Google Trends</b>: I was able to generate charts showing browsing frequency over the last 5 years, using a set of keywords relevant to the subject of air pollution. Additionally I was able to compare the frequency of those searches between the whole of Poland and the southwestern region of Lesser Poland, known to be the region heavily impacted by smog.

* <b>Facebook</b>: Due to changes in Facebook's API, I was unable to query for meaningful content. I considered a web scraping approach but Facebook browsing features limits to 5 posts over a narrow time period. Thus I dropped the site from my inquiries.

* <b>Reddit</b>: I made <a href='https://www.reddit.com/r/Polska/comments/b3gsrf/cze%C5%9B%C4%87_rpolska_i_need_your_help_researching_public/' target=_blank>a post</a> on r/Polska, the <em>Polish Subreddit</em>, soliciting inputs about air pollutions from Polish individuals directly. I was able to gather over half a dozen responses. The objective of my sollicitation was to inform my research process and use local testimonies to cross-examine with news story and subsequent data I gathered.

* <b>NK.pl</b>: A Polish forum site, which I rapidly found to be lacking in the content I was researching. Futhermore a poster on r/Polska kindly informed me that "NK.pl is dead".

* <b>Twitter Analytics</b>: Using the Twitter's API, I queried Tweets from the last 7 days (a limitation of the public access API) geotagged to Poland with the mention of smog. Although the scope of temporal granularity is quite limited, the API nonetheless provides a snapshot of the "current discourse". I was able to both generate a timeseries and word clouds from the Tweets collected.

* <b>Wykop</b>: The "Polish Reddit". Wykop was my richest source of information: I was able to scrape over 7,000 posts, dating as far back to 2012, mentioning smog. I was able to generate a timeseries of the frequency of the posts, in addition to a word cloud. 

## Method: Scraping all posts mentioning 'smog' on Wykop.pl

<center><img src="img/Wykop_flowchart (2).png"/></center>
