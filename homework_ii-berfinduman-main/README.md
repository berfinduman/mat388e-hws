
| Befin Duman                           | Grade | Comments                                                                               |
|---------------------------------------|-------|----------------------------------------------------------------------------------------|
|                                       |       |                                                                                        |
| A)   (55)  Question 1:                |       |                                                                                        |
| 1)    (10) Data description:          | 10    |                                                                                        |
| 2)    (10) Information on Elastic-Net | 10    |                                                                                        |
| 3)    (30) Implementation             | 25    | implementation throws an error, see your GitHub repo, i cannot reproduce your results  |
| 4)    (5) Conclusion:                 | 5     |                                                                                        |
|                                       |       |                                                                                        |
|                                       |       |                                                                                        |
| B)    (45) Question 2:                |       |                                                                                        |
| 1)    (10) Data description:          | 10    |                                                                                        |
| 2)    (30) Implementation             | 25    | implementation throws an error, see your GitHub repo, i cannot reproduce your results  |
| 3)    (5) Conclusion                  | 5     |                                                                                        |
| Overall                               | 90    |                                                                                        |




# Assignment II

I want to an explanation before my homework is checked, I would like to point out that many of the data sets I researched contained too many features. However, these data sets contained not only numerical but also categorical data. As it is known, feature selection can be more important and essential than model training, and since Pearson correlation could not be performed in datasets containing categorical variables, frankly, I did not know what to do and searched for different data. For this assignment, I did not do it that way, and I calculated Pearson correlation for numerical values, Chi-Square Test for features containing binary values, and Point-Biserial-Correlation for categorical and numeric variables. I researched these and added them to the assignment, I would like to point out that I did these in addition to the parts of the assignment that were asked of me. However, if you find the opportunity and examine it, I am also curious about my mistakes.

Some general information: 

When i was doing both questions, i took same error: ConvergenceWarning: The max_iter was reached which means the coef_ did not converge. This error says model cannot optimize these situation, we increase number of  max_iter, which is set default 1000. But if we increase number of this, I would spend a lot of time. Even in this case grid_search takes too much time; 
* Anyway, since the results in question 2 were satisfactory, I decided not to touch it. (~+90 accuracy)
* For the 1st question, the data must be examined, because the model was stuck at a certain accuracy rate, and unfortunately there was no noticeable increase when I increased max_iteration.

For now, I will not add anything specific to the 1st question, but I believe that if an outlier is detected, the result can be improved and the model can enter the learning process and finish learning without warning.

But right now, I added a code box that allows not to show warnings at the beginning of the questions, in case seeing warnings might bother you. Unfortunately, you can see the warnings in the codes I'm currently running because I added them after I finished all my work.

In the third assignment, if I can find time, I want to deal with some more outliers.

Thank you for reading, have a nice day.
References: 
Especially about elasticnet: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html  
Chi-square test: 
https://www.statology.org/correlation-between-continuous-categorical-variables/
Point-Biserial-Correlation:
https://thinkingneuron.com/how-to-measure-the-correlation-between-two-categorical-variables-in-python/
https://www.statology.org/correlation-between-continuous-categorical-variables/

Datas: 
Body signal of smoking: 
https://www.kaggle.com/datasets/kukuroo3/body-signal-of-smoking
Mobile-Price Classification: 
https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification 
