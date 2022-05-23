# A-date-day-using-the-Naive-Bayes-algorithm

For unclear data, the Naive Bayes classification technique is used. Based on the weather and temperature, we'll predict whether it's a good day to go on a Date.

The Naive Bayes classifier posits that the influence of one feature in a class is independent of the effect of other characteristics. A loan applicant, for example, is desirable or undesirable based on his or her income, previous loan and transaction history, age, and geography. Even if these features are interdependent, they are still considered separately. Because this assumption simplifies computing, it is seen as naive. This is known as class conditional independence.

By Naïve Bayes theorem,
  
  a) The probability of going for a date,
    
    P(Date= Yes | Weather=Overcast, Temp=Mild) = P(Weather=Overcast, Temp=Mild | Date = Yes)P(Date =Yes) ..........(1)
    
    P(Weather=Overcast, Temp=Mild | Date = Yes)= P(Overcast |Yes) P(Mild |Yes) ………..(2)
    
  b) Probability of not going,
    
    P(Date = No | Weather=Overcast, Temp=Mild) = P(Weather=Overcast, Temp=Mild | Date = No)P(Date =No) ..........(3)
    
    P(Weather=Overcast, Temp=Mild | Date = No)= P(Weather=Overcast | Date =No)
    
    P(Temp=Mild | Date =No) ………..(4)

• Given an example of weather and going on a date. You must compute the likelihood of going on a date. Based on the weather, we must now determine if the person will go or not.


Algorithm:

The probability of an occurrence is calculated by the Naive Bayes classifier in the following steps:

  a) Determine the prior probability for each class label.
  
  b) Determine the likelihood probability for each attribute for each class.
  
  c) Enter these values into the Bayes Formula and compute the posterior probability.
  
  d) Determine whether class has a greater likelihood, given that the input belongs to the class with a higher probability.

In the following steps, create a model using the naive bayes classifier:

  a) Import libraries.
  
  b) Assign features and labels to variables before encoding them as numbers.
  
  c) Develop a naïve Bayes classifier.
  
  d) Train the classifier on the dataset (features: weather, temperature, with label: Date).

  e) Make a prediction.


![image](https://user-images.githubusercontent.com/59199696/169858024-1b6e8fc5-b590-4455-84a7-65b5098a68b2.png)
