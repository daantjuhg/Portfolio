naam: Daan Gielen
Studentnummer: 19072074


## Portfolio

## DataCamp course 
60%

## reflection on own contribution to the poroject
starr: 
situatie
  - wanneer
  - wie 
  - hoe
taak
  - wat was mijn taak 
    - wat heb ik gedaan 
    - wat wilde ik bereieken
    - wat werd er van je verwacht
 actie
  - hoe heb je het opgelost en waarom 
  - hoe heb je het gedaan
  - waarom zo leg uit aan de hand van  theoretische concepten the minor or theoretische info van de research
  - werkte het en waarom
reflectie
  - wat heb je geleerd
  - hoe denk je dat je het hebt gedaan
  - was je tevreden met het resultaat
  - wat is de essentie van wat je hebt geleerd.
  - wat zou je kunnen verbeteren. 
  - kan je het toepassen in andere situaties.-
 

## reflection on own learning objectives


## evaluation on the group project as a whole


## Domain knowledge 
### introduction to the subject field and literature research
Data is everywhere, from Netflix to google maps, we use and make data daily without noticing. This data is what this minor is all about. it can be used to predict/classify all sorts of different subjects, from predicting the cheapest day refilling your car to classifying which plant is which based on the color/length of the petals. Personally, I classified wheelchair movements with my project group. Below is an introduction into this subject with scientific proof researched by me. 
     
Phones track steps and different sport activities, able bodied people have their movement info at their fingertips. Research from [badar ud din Tahir,S., etall.(2020)](https://ieeexplore.ieee.org/document/9055944)shows that machine learning models are able to classify 12 different movements, walking forwards/walking left/ etc., correct with 73.33% accuracy. And a Study by [Zengtao Feng, etall.(2015)](https://ieeexplore.ieee.org/document/7319532) shows that people are still improving their training speed and test accuracy and stability for these movements through different predictive models.This second study also shows that random forest based models work better than more commonly used classifications and non-ensemble classifiers(KNN SVM BN J48). For wheelchair sports we see a slight research gap. Within wheelchair sports the research into classifying movements or sports in lacking. But in the paper from [R.M.Avan der Slikkeab, M.A.M.Berger, etall.,(2015)](https://www.sciencedirect.com/science/article/abs/pii/S0021929015003231?via%3Dihub) research we can conclude wheelchair sport analysis is on the rise. Wheelchair kinematic analysis may be the first and crucial push this field needed to expand the knowledge of wheelchair movements. 
Further research into the project will be explained later in the portfolio.

## Research project
### Task definition 
Like I said before, abled persons have the ability to easily track and monitor their activities throughout the day. With only a phone you can already see your steps, activity time and calorie count. Most phones even have an app with which you can track your performance in trainings like running, swimming or cycling. We see a pattern here; all commonly available sports trackers are focused on steps. But wheelchairs roll you might say, yes, they do. But just like walking has a rhythm, so does riding. This would mean that wheelchair riding could also be monitored.

This is where our project comes into play, IMU’s are used to track wheelchair movements in basketball games.  Our goal is to apply this data in machine learning models and extract selected wheelchair movements like sprints.  to reach this goal, the project group set up the following research question with some sub questions, to reach the end goal.

- How can IMU data be used to identify wheelchair basketball-specific movements?
  -	Which form of data processing will be used?
  -	Which specific movements can be detected?
  -	Which sensor data is used for each movement?
  -	Can movements be used to predict fatigue?
  -	Can movements be used to detect overload? These sub question will help us to get an answer to the main research question.

further research and supporting reasons for these questions can be found in the [Plan of Approach](https://github.com/daantjuhg/Portfolio/blob/main/Planofapproach.pdf).

### planning
To reach the end goal of this project in a orderly way the team set up a azure devops, https://dev.azure.com/Wheeeeeeeeeeeeeeels/wheels/_boards/board/t/wheels%20Team/Stories_m_. it was a bit getting used to in the beginning and because of time issues it was also hard to finish it up, but this website helped us a lot keeping track of tasks. Our daily standup would start at 9:30 to discuss/evaluate everyone’s assignments from the day before and explain the planning for today. This would keep the team up to date on the process so we could help each other easily if necessary. Sprints within this project are 2 weeks short, we would evaluate the sprints through a retrospective. In this meeting we would take the time to talk about the group’s strengths and weaknesses. This list would be summed up into three categories, keep/remove/improve. We would also take these times to settle debates between group members and made sure everyone was okay. After the retrospective we would also discuss the new sprint planning. In which we would come up with user stories to complete over the next couple of weeks. Finally, we would determine which user story was most important and how much time it would take to complete. Time for completion gave the group possibility to divide the workload equally. 

In the [Plan of Approach](https://github.com/daantjuhg/Portfolio/blob/main/Planofapproach.pdf) Is also an attachment, called ‘planning’, I made for the group. Looking at this planning from time to time gave us an overall overview of how many weeks we still had and helped set up for the next step in the project. Looking back on it the planning was quite short and hefty at the start. Personally, I should have planned more time for research and setup of the project. Personally, I did a few other things and was not so committed to the research part. It should have been my job to communicate better about the planning of the research and discuss this with the group.

### conclusions
From my research, [stated above Zengtao Feng, etall.(2015)](https://ieeexplore.ieee.org/document/7319532),  we found that an RFC model outperforms other models. Martijn found a few papers that would use neural networks for the classification of IMU data. One even stated [Muralidharan, K., Anirudh, R., (2021)](https://www.sciencedirect.com/science/article/pii/S2666307421000140) that when using smartphone sensor data to classify different movements RNN would severely outperform RFC wich stands in contradictio to my papers. Therefore, later in the project we focust on these two models. 

In this project we developed a method to classify wheelchair movements through IMU data. In our case this was done by expanding our dataset which only had 2.3% defined for movements, in our case the movement is sprinting.  The group used the RFC and RNN models to collect/compare and analyze false positive data predictions to define the dataset. We improved the dataset to 17.1% tagged sprints. we found that the RFC model was more accurate on the training ad validation set by 4%, we decided to proceed to testing with this model. The test set consist of unknown data from another unanalyzed player. The RFC classified sprints with a precision of 91.67% recall and accuracy are unfortunately unknown because of the unidentified dataset. Anyhow, these results show that (even) partially defined IMU data can be used to classify sprints through RFC and RNN model. 


### evaluation
Within this project the main goal shifted a bit because of time problems. Instead of trying to classify movements in wheelchair basketball matches, we started focusing on solely sprints. the main question would stay the same as one movement would still show the possibilities of the IMU recordings. 

This question was answered indeed by showing the precision in which the sprints are classified. But this is only the beginning, from here on out the method could be used to classify other movements. The most important part for these new classifications is that movements need to be further researched. Right now, the movements do not have definition or meaning. So further research should be done for patterns in different wheelchair movements.

This project group focused the study on players within the same paralysis level. Within wheelchair basketball paralysis levels are used to classify players. During matches the teams can create a lineup with a maximum number of points. Athletes with higher paralysis levels have a lower score. With this first step to classifying movements. We believe it may be possible to classify the same pattern movements between players with different paralysis levels. Personally, I think this research should focus on the feature engineering most because there is a lot to gain. 

Besides using this technique for athletes only, we hope it is possible to convert this classification study for daily use. Research should look into the characteristics of normal wheelchair push offs using phone or smartwatch accelerometers instead of IMU’s. this way wheelchair users can track their activities just like we can every day. 

## Predictive analytics
  ### selecting a model
The first models: 

At the start of the project, I wanted to jump into coding with machine learning models. Since I had no previous experience with coding except for MATLAB. I wanted to try things within jupyter and help the group.  I stared training models like KNN, decision tree and SVC, because these models are explained quite quickly in the data camp course. With no clear goal in mind than just learning how to use jupyter and prepare models. 

A little time later decision tree was found to be useful. More on that in the training subject. 

RFC:

The following papers used RFCs to classify human movement analysis with IMU data. these papers i found [badar ud din Tahir,S., etall.(2020)](https://ieeexplore.ieee.org/document/9055944) [Zengtao Feng, etall.(2015)](https://ieeexplore.ieee.org/document/7319532) are comparing RF classifier to other machine learning algorithms. They compare accuracy, stability and training time, in which RFC comes on top. Both of these papers use sensor data, one of which uses similar to IMU sensors; 3-axis gyroscope and 3 axis accelerometers, to investigate and classify movements or sports. 

  ### Training and configuring a model
After I setup the two models I trained them using the dataset we explored from player A.

The first time running the decision tree model I split the chunk data, created by martijn, in 80% training 20% validation. the whole dataset contained +- 6000 datapoints from which 100 were tagged sprints. this means the validation set had +- 25 tagged sprint points in +- 1500 datapoints. I tuned this decision tree to 100% recall. In the document [Decision tree](https://github.com/daantjuhg/Portfolio/blob/main/decision%20tree%20sprints.ipynb) you can see that I got a lot of false positive results, these results were stored in a csv file for evaluation later. In the evaluation I will elaborate more on the evaluation of this method. 

For the [RFC model](https://github.com/daantjuhg/Portfolio/blob/main/RandomForrestCLassifier%20sprints.ipynb) we used later in the project i split the data in two parts a training part and validation part, 75% to 25%. First time selecting two features the RFC underfitted this was visualized by plotting a confusion matrix, precision: 86.25% and recall: 69.9%. which is not too bad for a first try, how this is possible will be explained in the chapter data preparation/visualization. After this first try, I made a gridsearch to find better hyperparameters. I made sure to run the model every time with random_state = 42, this way my findings would be comparable. The hyperparameters I tuned were: n_estimators, min_samples_leaf, criterion and max depth. 

From gridsearch and the graphs we can see that gridsearch gives us: 80, 2, gini, 14 as best numbers from the test. But in the RFC below we can see that I eventually went with the numbers: 100, 3, gini, 14. I did this because the numbers I chose had a better recall score by 3% by losing precision of less then 1%. This is important for our project because missing sprints in your match analysis is bad. (plus, we don’t know for certain if the dataset is fully tagged so false positives could be correct sprints. 

  ### evaluating a model
  
Evaluating models was not as easy as it seemed. The dataset provided by our problem owner was not complete. After I first made the [Decision tree](https://github.com/daantjuhg/Portfolio/blob/main/decision%20tree%20sprints.ipynb) model, martijn created a [false positive visualization](https://github.com/MartijnKok/Portfolio/blob/main/Data_Visualization/Check_False_Positives.ipynb)(links you to martijn his github). This code helped martijn and I to check the first false positives of the code. We found that +-50% of the data was positive sprints, we used this to further complete the dataset and let Collin rerun this process one or two more times. After this method we spoke with Jeroen and found another way to find and correct the false positives, this is explained within the research paper page … Alinea … After this method we are positive that the data is complete enough to run valid, training validation ad testing. 

  ### visualizing the outcome of a model
  
## Domain knowledge
  ### introduction of the subject field
  The student has written a good and complete introduction of the subject field.

  ### Literature research
  
  
  ### Explanation of Terminology, jargon and definitions
  
## Data procesing
  ### Data exploration 
    The student properly examined and visualized the data, distributions, outliers, correlations and used that analysis to give directions for an early hypothesis.
    in the early stages of the project i have looked at a lot of graphs. we would first look at fast breaks and fast defences. the movements could be split in two movements,
    rotations and sprints. within those graphs me and martijn came to the conclusion that there are two features that define a sprint. the first and most important feature
    for sprints is the wheelrotationalspeedX, this shows the wheelturning speed, it will show the push offs of the player. the second feature is the framerotationalspeedZ,
    this shows the turning speed of the wheelchair, it wil show if the wheelchair is moving in a straight line. 
  
  ### Data preperation 
  The student prepared the data in an appropriate way, where necessary transforming data, removing outliers, filling in missing values, etc.

    preparing the dataset was my main focus. i looke at the data and searched for paterns in the different features we got from rienk.
    for this visualization a program was written that i studied and changed for usage. the first changes that were made was simplle multiplications. 
    this way the numbers were all around the same numbers. +- 500. after i started working with means, and low pass filters. 
  
  
  ### Data explanation 
  
  ### Data visualization 
  
## communication 
  ### Presentations
  
  
  ### Writing paper
