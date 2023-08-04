# Crowdfunding_Groovy_Time
First-pass excel analysis of very small subset of crowdfunding data. The Excel file shows the existing data (in the sheet called "Crowdfunding Data") and also gives alternative views of the data including:

* Outcome by parent category
* Outcome by parent sub-category
* Outcome by creation month
* Outcomes based on funding goal
* Summary statistics (backers)
  <br><br>

Below is the analysis contained in the Word file. 

<br><br>

**Crowdfunding Data Report**

Analyst: Julia Mossbridge

Date: 8/3/23

**Conclusions**

Given the limitations of the existing dataset (too small!) and based on the existing analysis (too brief!) we can tentatively make several conclusions about crowdfunding on platforms like IndieGoGo and KickStarter.

•	US-launched campaigns are more common than campaigns launched by citizens of any other country. 

•	Campaigns are most likely to focus on the arts (theater, music, and film), though technology and publishing projects are slightly more likely to be successful, and plays are by far the most common sub-category among all launched campaigns.

•	There is a bump in success for campaigns launched in June/July – and a dip around December. If on average campaigns lasted 6 months, this bump in summer could be explained by a campaign ending right around the holidays, when people are feeling generous to their friends and family members (could be tested further, see below). 

•	2017-2019 were better years for campaigns, which could be due to public education about what it takes as well as better support for campaigns via the crowdfunding sites themselves.

**Limitations**

With only 1,000 instances spanning 9 categories and 10 years, there’s just not a lot of data to go on, so we are basically guessing. The good thing is these guesses could lead to interesting further analyses, were we to get more data. Further, there’s almost no data from 2020 – which would be a revealing year (given COVID changes) for this particular industry. There is also no clarity on whether the amount pledged has already been converted to dollars or not – perhaps the native currency is given to show the original currency? Or maybe the conversion has not yet happened? Without answering that question it feels strange to compare amounts pledged. Finally, there is not much information about where the data came from – One site? Multiple sites? Were they all in English? What was the support level given by the crowdfunding sites to their users? What is the relative level of awareness of crowdfunding across industries? The answers to these questions and more will influence the conclusions we can draw as well as their implications.

**Additional Analyses on the Existing Dataset**

I am interested in this downward trend in successful campaigns launched during the holidays – and the potentially related peak in those launched during the summer months. I’d like to look at the deadline data to see if the hypothesis that the summer bump is due to ending the campaign around the holidays holds water – so a plot of deadline (by month) vs. outcome would be good. I also think it would be cool to do some text analysis on the blurbs to see if we can learn if certain blurb styles do better – I’m thinking looking for jargon, hyphenations, and positive vs. negative connotations would be one simple text analysis strategy. A stacked column chart with those 3 features as parameters for each of the 3 major outcome dispositions would work.

