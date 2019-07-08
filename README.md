# Student-Drop-Out-Analysis
Analysis of Student Withdrawal in U.S. Colleges 

Using machine learning to predict student drop out rates:

This project aims to predict student drop out rates based on data provided by College Scoreboard (https://collegescorecard.ed.gov). The aim is to predict student drop outs rates that can be used by both students and colleges. The project aims to address issues faced by two different stakeholders: colleges vs. students.
Stakeholder # 1: Colleges

Our main stakeholders are colleges / universities. Student drop-out rate is a concern for colleges as it results in decreased revenue as well as causes reputational problems. It may also showcase opportunities of improvement in parts of colleges such as provided better resources and guidances for students that may benefit from it.

Stakeholer # 2: Students
Our second stakeholders are students who can use this data to see what schools / colleges have the lowest predicted drop-out rates in the future. They can use this to make decisions regarding their decision to attend a particular college vs. other. It might also be a tool for students to hedge their risks.

Data:
The data will look at various datasets from College Scoreboard. Each dataset is divided by years from 2007 - 2017. The dataset is quite extensive and when combined from 2010 - 2017, there are over 1,977 features and over 50,000 rows. To reduce complexity of the project and ensure we're addressing each stakeholder differently, I have decided to do analysis in two parts.

First Approach in Analysis for Colleges as Stakeholders:

As my initial stakeholders are colleges - I have decided to look at various factors that impact student dropout here acknowledging that colleges would be more interested in predicting what causes drop outs versus the actual rates of drop outs. Here, what is important is the features causing high drop out rates.
To do this, I have chosen to look at two different datasets. The target (drop out rate) will come from dataset 2016's Year 2 Drop-Out Columns (WDRAW_ORIG_YR2_RT) and the features will come from the year 2014-2015 dataset. This division is done as the Year 2 Drop Out Column in 2016 is referring to drop out rates from the cohort of 2014 - 2015.
I will set the Drop-Out Rate as a target and use features from year 2014 - 2015 to see what is influencing drop out rates through evaluating Feature Importance. I will also run this model through supervised / unsupervised learning models to predict drop out rates.

Second Approach, Part One: 

Here we will look at the problem from the prespective of the students. Here, we're assuming the students are only interested in the drop out rates.
To do this, I will find historical data on drop out rates by going back to each dataset and labelling the drop out columns by the cohort year.
Then, I will use the latest drop out rates we have (year is 2015 - actually referring to data from 2013 - 2014 cohort) and use that to predict future drop out rates.

Second Approach, Part Two: 

Using school characteristics as predictor for withdrawl rate:
Another way to predict withdrawal rate is by using various characteristics for schools such as regions for their location, tuition rates, admissions rates and others. These characteristics can be used to evaluate what areas in school's control results in higher withdrawal rate.
The way I did this was to take features that would impact withdrawal rate and then use that to see what feature that students should look out for the most in choosing schools (schools in certain locations maybe or schools with certain tuition etc).
For this, I only used date from one year (2014).
