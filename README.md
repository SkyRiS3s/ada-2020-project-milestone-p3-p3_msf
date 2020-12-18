# 1. Title
The effect of the Black Lives Matter movement on the arrestations of African American people in L.A.


# 2. Abstract
The purpose of our study is to observe the effect of the creation of the Black Lives Matter social movement on the arrests of African Americans. The movement was first created in July 2013, after George Zimmerman (an American citizen) was acquitted for shooting and killing Trayvon Martin, an African American of 17 years old.
To assess this question, we will perform a segmented regression analysis as it was done in the "Chilling Effects: Online Surveillance and Wikipedia Use" paper. Our goal is to show whether or not there is a change in the trend of the overall arrests of African Americans in L.A. since the creation of the movement in the U.S. We will also study the evolution of the arrests of the other races, in order to compare them with the trend of the arrests of African American people. 
As for the dataset we intend on using for our study, we will work on [Los Angeles Crime & Arrest Data](https://www.kaggle.com/cityofLA/los-angeles-crime-arrest-data?select=crime-data-from-2010-to-present.csv) which is provided by the City of Los Angeles.

# 3. Research Questions
- Since the creation of the Black Lives Matter movement, was there a change in the trend of the overall arrests of African American people in L.A.?
- How does the evolution of the trend of arrests of White people differ from those of the African American people ?
- Is there a difference in the number of arrestations between males and females African Americans ? What about after the Black Lives Matter movement ?

# 4. Proposed dataset
The dataset is hosted by the city of Los Angeles. The organization has an open data platform and they update their information according the amount of data that is brought in.

It contains information regarding the arrestations for each day from 2010 to 2019, the type of crime, the sex, race and age of the arrested person, etc. 

# 5. Methods
Data collection and wrangling: We will load the data and we will drop the variables not useful for the analysis. Only the variables `arrest date`, `sex code` and `descent code` (that specifies the race) are kept. 

First analysis: A first general analysis of the data will also be performed to obtain a first insight into the dataset and to remove any missing values and eventual outliers. Also, the means of the arrests, before and after the creation of the Black Lives Matter movement will be compared. 

Segmented regression analysis: The segmented regression analysis is the central method of our study. The disruptive event will be the strating point of the Black Lives Matter movement in July 2013. The arrest trends before and after this event will be compared. We will perform mainly two analysis. The first one will assess whtehter there is a change in the trend of the overall arrests of African American people in L.A. and it will be compared to the trends of our control group (i.e. White people). We will then check if there is a difference in the trends between males and females African Americans. To do so, a second regression analysis will be performed. 


# 6. Proposed timeline
- Week 1 : Downloading the dataset and completing the first sanity checks. Data wrangling will be performed as well as the mean comparison. 
- Week 2 : All the segmented regression analysis will be carried out.
- Week 3 : Wraping up the analysis and peparing the project presentation.

# 7. Organization within the team
Saoud will start by doing the first sanity checks and the data wrangling. He will also perform the mean comparison.
Fanny will focus on finding outliers within the dataset by using various methods seen in class (such as vizualisation, ...)
Marjolaine will focus on the segmented regression analysis. 
We will work tohgether on the interpretation of restults and on the video for the project.


# 8. Questions for TAs (optional)
NONE
