# Predict Secondary School Student Alcohol Consumption
This is the final project we did for the machine learning course CS 6923 at NYU Tandon School of Engineering under the guidance of Professor Sandoval.

We propose to predict secondary school student alcohol consumption levels based on an individual student’s demographic statistics. Thus, in our case, the data instance would be a single student and their associated descriptive statistics. We envision the eventual model to potentially be deployed either annually or semi-annually using demographic and survey data from all secondary school students in the associated schools to classify them per their risk of developing unhealthy drinking habits.

### Data Set
Our dataset is from University of California Irvine Machine Learning repository. 
The link to the data set is as follows:
http://archive.ics.uci.edu/ml/datasets/STUDENT+ALCOHOL+CONSUMPTION

### Data Understanding
As a data mining problem, this would likely fall into category of classification, with the target variable that we intend to predict using the dataset being a binning of the average alcohol consumption. The data has two fields: “Workday alcohol consumption” and “Weekend alcohol consumption” and we think that merging the two fields into a single indicator of alcohol consumption variable would be more useful as a target variable. The merging can be done by taking a weighted average of the two original fields (As workday consumption is more likely to be related to a problem we would need to provide it more weight against weekend consumption). 

There are currently a total of 31 features in the dataset, though more could be engineered if necessary.

### Business Understanding

Finally, on completion the model could be very valuable in providing insights about the alcohol consumption of various students and, like a business problem targeting churn, it could help schools optimize the use of their limited resources to provide interventions and counseling for those students who have a higher alcohol consumption than a threshold and are most at risk of developing dangerous alcohol consumption habits. It would also allow school administrators to target individuals who display low to medium alcohol consumption habits with seminars on alcohol abuse prevention to prevent the problems from developing.

### Technology Used
We used IPython notebooks for modeling and statiscal evaluation of the problem.
