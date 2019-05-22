**EXECUTIVE SUMMARY**
Problem statement: Is it possible to classify a story as fact or fiction with machine learning? My research says yes. 

Using a variety of techniques I was able to fit a Natural Language Processor model and score with 91% accuracy into classifying real and fake stories posted to an online forum

**Procedure**
Aquiring The data:
  Using an API and a webscraping function I brought in almost 5000 posts total from two different sections of the forum Reddit.com.
  After cleaning the data and removing deleted posts, I isolated the the "self Text" data to be my feature.
The we vectorized the data into a bag of words model to ultimately score over 90% correct on our classifications 

**Moving forward**
Continuing this project further I would like to write a function that takes a story and applies the model to predict fact or fiction in real time
More processing time on the Gridsearch to optimize my model further.

**Hardships**
Portions of this project I found really difficult would include using RegEx and applying it to clean the formatting characters out of the text body. My original function included use of .re() but I had to pull it out after it wasn't eliminating the characters correctly
