# Speed_Dating_Project

Project Proposal
===

# COMP257 - Data Science Proposal
Eddie Zeng 44786344, Billy Mihalarias 45266026, Tofayel Ahmed Topu- 44282443, Karl Stewart 44828330

**Purpose**
1. Investigate how personal characteristics of participants are related to the likelihood of them to ‘match’ or have unrequited feelings towards another participant.
2. Secondarily this project will look at whether this can be reversed, if a person likes or rates another person highly does give any idea about the rating that they will receive from this person. If there is a pattern can distinct groups of people be found that are more likely to match with people in a distinct group of people form the opposite sex.

**Dataset**

The [primary dataset]( https://data.world/annavmontoya/speed-dating-experiment) will be from Fisman, Iyengar, Kamenica and Sinonson’s 2004 study of racial preferences in dating. Although this study was primarily about the racial preferences of participants data was collected about many attributes, including education, physical characteristics, interests and demographics.

A [larger dataset](http://www.occamslab.com/petricek/data/) of online dating information will also be analysed. Information from LibimSeTi, a Czech online dating site, contains user ratings of potential matches as well as their gender. This set has already been partially cleaned and prepared by Lukas Brozovsky and Vaclav Petricek of Charles University. This dataset does not include any other demographic, personal or survey information.

**Data cleaning**

The Fisman et al dataset is in a csv format and as this data was created for a research study it is relatively clean. There is however quite a few variables that only exist for some people, if it is determined that these may are pertinent to this project then the subjects that these missing records pertain to may need to be excluded.

The second data has a much less detailed set of information for each individual and match, but has many more records. This data is in the form of two dat files, one file contains the ratings that each person gave to each other person in the format of userID, potentialmatchID, rating, the other file contains the gender of each user. These files first need to be converted to a more usable format. Using python they can be transformed into dataframes and hence csv’s for future storage with relative ease. The gender will have to be matched to each user. As the reciprocal (users who have given ratings to each other) records are of most interest these will have to be found and converted into an appropriate format.

**Methodology**

For studying the initial first purpose regression analysis will be used, a view has not yet been formed on the most appropriate type of regression to use, this will be studied during the project. K-means clustering will also be utilised to analyse whether using given criteria distinct groups of people who are more likely to match with other or have unrequited attempts to match occur. This will all be conducted suing the first data set created by Fisman et al.

For the second purpose, the project will look at whether if one user gives another user a higher (or lower) rating then average is this action likely to be done in the reverse direction as well. If this does happen, can we use this to determine distinct groups or patterns within the data. To look for patterns a form of regression analysis, most likely linear regression will be used. When looking at whether distinct groups form k-means clustering will be used.
 
**Project Plan**

By the end of the following weeks we will endeavour to complete the below actions:

**8** Initial visualisation of data complete to inform research direction, Detailed analysis method decided on

**10** Draft of analysis of first purpose complete (visualisation not complete but method of visualisation clear)

**11** Draft of analysis of second purpose complete, with some rough visuals

**12** All analysis completed, with most of the data presented in a presentation level visualisation





