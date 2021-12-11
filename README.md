# ProCyclingStats Analytics

I have always been fascinated with pro cycling and I am a big fan of the major cycling events in Europe and in the rest of the world, such as the tour de France, ronde van Vlaanderen, Paris-Roubaix etc.           
Therefore, I wanted to know more about cycling and take a look into the data to make some kind of analysis. However, one problem is that there is nearly no data available on popular sites such as Kaggle or even the Google dataset search engine. Since there is no public and structured data available, I have to take a look at public and unstructured data and thankfully there is plenty of that.   
I eventually found a site called procyclingstats.com. It is mainly used to record the results of all noteworthy races. This way, they also give points to each rider's performance within a race based on certain weights and the importance or level of a race. Furthermore, they can create a ranking of those riders to objectively decide which riders perform better than others.
For the purpose of my analysis I decide to web scrape this website and hopefully get the information I need to get some findings.  

<u><b> Objective of the analysis: </b></u>  
First of all, I don't want to limit myself to only one question, since I feel like some of my data might just go to waste if I were to do that.  
  
* First of all, I would like to take a look at the nationality of the riders and create a visualization to see where most cyclists are from and hence in which countries it is considered an important sport.
* Second, I would like to give a look at the BMI, age and experience data of cyclists to see what the ideal 'configuration' is of a rider.
* Lastly, I will create a model to predict the PCS_points (without the UCI points, since the 2 rankings are very much alike and just use some different weights) and see to what extent this is possible.
