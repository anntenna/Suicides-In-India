# Suicides In India
An analysis of suicide rates in India

With a population of 1.3 billion, it isn’t surprising that India ranks high in suicides. As a child growing up in India, news of farmers committing suicide to avoid paying debts was common every summer. As the summers grew hotter, these suicide rates kept increasing. The urbanization of India does not seem to have had a positive effect on suicide rates. The government of India has made available [public data](https://data.gov.in/dataset-group-name/accidental-deaths-and-suicides) caused by accidents and suicides starting from the year 1967 to 2015. A [subset of this data is available on Kaggle](https://www.kaggle.com/rajanand/suicides-in-india), with a surprising amount of detail available for the cause of suicides starting from 2001.
![Total suicides by Year](https://github.com/anntenna/Suicides-In-India/blob/master/image-4.png "Total suicides by Year")

## Causes of Suicide
The list of causes reads like a list of triggers for depression, something that might call for a visit to a psychologist or a psychiatrist, and perhaps even a list of life events that occur in a lot of people’s lives (love affairs, divorce, family problems, fall in social reputation, to name a few). Not to trivialize individual situations, but a lot of these causes seem highly preventable. My aim with this dataset is to use it to use patterns in the data to identify the reasons for the rapid rise of suicide rates in India, and find out what can be done to prevent them. 

## Analysis Plan
To identify a cause, I plan to analyze and compare suicide rates to demographic indicators such as literacy rates over time, access to health services, access to the Internet in urban and rural India. Because the data is rich enough that there is a cause associated with most suicide counts, I will be able to localize the cause to a state, year, and age group, and match it with local trends. This will also let me identify at-risk demographic groups in each state.
![Top 10 causes of suicide](https://github.com/anntenna/Suicides-In-India/blob/master/image-1.png "Top 10 causes of suicide")

For example, the states of West Bengal, Maharashtra, Tamil Nadu, and Andhra Pradesh are known to produce large volumes of candidates for competitive examinations, and these states are among the top 5 for the cause of suicide ‘Failure in Examination’. 
Once a trend is identified, it can be used to pinpoint areas in which the government or non-profits can intervene to provide the necessary services. 
![Top 5 state + age groups](https://github.com/anntenna/Suicides-In-India/blob/master/image-2.png "Top 5 state + age groups")
![Proportion of suicides by education level](https://github.com/anntenna/Suicides-In-India/blob/master/image-3.png "Proportion of suicides by education level")


