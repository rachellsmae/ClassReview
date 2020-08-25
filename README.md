# ClassReview
A statistical machine learning approach to Penn Course Ratings. Supervised Machine Learning to predict course rating, statistical analysis to understand potential rating bias, unsupervised text based learning to perform class based clustering

## Introduction
Penn Course Review has historically been the go-to place for Penn students to find relevant information on the quality of classes and plays a crucial role in course selection by students.

## Problem Statements
Our problem statements are highly tied to this topic and can be broken down into three main parts. Overall, we aim to tackle not only students behavior when it comes to course ratings but also offer tangible recommendations to the Penn Community on class construction and classification:

### Task 1
The first problem statement is that while end-of-semester ratings are useful, the data is only available after the course is offered. We believe that through the development of an accurate predictive model that utilizes pre-semester course information, we could help the school pick the best classes to offer. This could also allow for strategic decisions such as what classes to prioritize at the peak time (a.k.a. The time where classes are best received). We think that it is in the best interest of the school to offer courses that are going to be well received by the students given the constraints to the amount of classes that can be offered. 

### Task 2
The second problem statement is that there may be biases associated with course ratings. We hypothesize that the ratings (course quality in particularly) are highly correlated with the demographic profile of professors, how “nice” the professor is and how convenient the class is (i.e. Less amount of workload, better class time and etc.) and are might not be a good proxy for class quality. We aim to single out these biases underlying the ratings.

### Task 3
The third problem statement is that while classes largely get clustered under departments, classes under each departments or even cross departments can certainly be further broken down into smaller clusters (i.e. STAT 471, 422 and ACCT 270 could largely fall under predictive modelling, while STAT 432 and 442 could be classified as theoretical statistics). Therefore, our goal is to cluster courses based on the course descriptions. Using text analysis, we aim to cluster these classes into smaller more meaningful clusters for students to choose classes at ease across different Penn schools.

## Significance
We believe the insights from this paper can have a number of applications. Firstly, by garnering perspectives on what exactly Penn students look for in a class, the class curriculum can be better designed to suit certain preferences. Secondly, if clear biases are found in the assessment of course quality associating with the instructor involved in the class, intervention may be needed to correct said problem. Thirdly, by having a better clustering system for classes that go beyond department label, this feature can be incorporated into tools like Penn Course Review to provide people with a better sense of the class itself. Fourthly, this can help Penn strategically launch classes that students may like.
