Title : 
An Analysis of Tweets Surrounding the Aftermath of the Midterm 2022 Election 

Submitted by :
Adam Haney
Harishma Ashok
Shiram Sreedhar

Overview:
Our report centers around the aftermath of the Midterm elections in the United States and analyzing the current state of the discourse surrounding the current political landscape using Twitter data to form a network of communities of interacting users. We aim to see what figures and issues are topics of discourse, as well as what accounts are gaining significant traction or influence, and whether communities of users related to different topics or political ideologies are intreracting in any significant amount or whether echo chambers have been formed. Our findings indicate much disconnect between communities, with the broader discourse centering around the run-offs in Georgia, Kari Lake's fraud claims in the Arizona election, and criticism of the GOP for their underperformance in the midterms. While we did find a component of connected communities, many of these communities, especially the ones that revolve around conservative news outlets, are only connected by one or two users to other communities, showing that there are some echo chambers in the network and that users in these communities are not interacting with the wider discourse or the specific accounts of key figures such as Kari Lake or Herschel Walker. We also zooomed in on each major community and sampled tweets to understand what the general discourse was and which figures had gained the most interaction and thus the most good or bad controversy.


Files:
There are three folders:
1. Data gathering - MidetermsData
	- AllHashtags.xlxs : It contains the raw data scraped from twitter

2. Data cleaning
	- AllHashtagsNew.xlxs : input file
	- Data preparation - The code for data cleaning
	- edgeInfo.csv : output file, contains the details of the nodes in the graph
	- nodesInfo.csv : output file, contains the details of the edges in the graph like source, target and weights 

3. Implementation:
	- edgesInfo.csv
	- nodesInfo.csv
	- Final Project - An Analysis of Tweets Surrounding the Aftermath of the Midterm 2022 Election : It is an .ipynb file which conatins the actual implementation of the project
	