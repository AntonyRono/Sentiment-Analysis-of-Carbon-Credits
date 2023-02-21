# Sentiment Analysis of Carbon Credits

* Sentiment Analysis is the process of detecting the emotion (positive or negative) or perception in a text
* In our case, we want to **understand the overall perception of carbon credits in the market, using data from twitter**.
* There are various algorithms that can be used to achieve this, but can be generally categorized into 3 broad categories:
    1. **Rule-based systems**, where we use a set of manually crafted rules to help identify the polarity (i.e. negative, positive or neutral) and subjectivity (personal opinion, emotion or judgement) of an text
    1. **Automatics sysytems**, which rely on machine learning techniques to learn from data
    1. **Hybrid sytems**, which combines the two systems above

* The choice of which system to use is dependent on the size of data available and the level of accuracy we need to achieve.
    * While the machine-learning based systems are more often than not more accurate,you do need a lot of data to effectively implement them. 
* Since our data is quite limited, as well as our objective being to estimate the overall perception of carbon credits in the market, we have chosen to use the rule-based system.

## Steps:
1. Getting tweets on carbon credits from twitter.
2. Cleaning the tweets
3. Analyzing the tweets
4. Interpreting the results
    1. We will get the overall sentiments in form of the proportion of each polarity to understand the overall sentiment
    1. We will then look at the word frequency and see if we can get more information
