# Clinical Trial Data Analysis

## Project Overview

The increasing prevalence of diabetes in the 21st century is a problem, an epidemic even.

Since the discovery of insulin as an intervention, the default method of administration is by a needle, multiple times a day.

Wouldn't it be great if diabetics could take insulin orally? This is an active area of research, but historically the roadblock is getting insulin through the stomach's thick lining.

In this project, we're going to work on a phase II clinical trial data for a new inovative oral insulin called auralin. This trial tests the efficacy and dose responsiveness of the drug and its adverse  reactions. 

In this clinical trial data, we have 350 patients split into two groups, 175 are treated with the new oral insulin "auralin", and the other 175 are treated with the popular injectable insulin called novodra. 

By comparing key metrics between these two drugs, we can determine if auralin is effective, the most important metric HbA1c levels, and specifically, HbA1c change.

HbA1c is a property of the blod that measures how well your blood sugar levels have been controlled over the past few months, with higher levels being bad. 

If auralin, the new oral insulin can reduce HbA1c_levels at a similar standard as the injectable insulin novodra from some standard pretrial baseline, like say they both decrease HbA1c_levels from 7.9% to 7.4%, that is a 0.5% drop. 
If we can get a 0.4 change, we've got ourselves a major medical breakthrough in the dramatic quality of life improvement for diabetes all over the world.

Before we can get to that point of recommendation, we've got ourselves another problem. 
Healthcare data is notorious for it's errors and disorganization, and its clinical trial data is no exception. 
For example, human errors during the patient registration process means we can have duplicate data, missing data and inaccurate data. 
And this common healthcare data issue is reflected in this clinical trial data. 

In this project, we're going to take the first step in fixing this issues. 
We're going to assess this data sets quality and tidiness, and take note of all these issues. 

We'll then clean all these issues using python and pandas.

The end goal, being able to create a trusrworthy analysis, and hopefully, eventually recommend this new drug, this new oral insulin, to continue to large scale-production and improve the lives of diabetics all over the world. 


## Findings
### Adverse Reactions
Some of the common adverse reactions are cough, headache, nausea, and a big one is hypoglycemia which is low blood sugar caused by insulin overdose.

Between these two drugs, Auralin and Novodra, the pure counts of each adverse reaction are pretty similar, with the exception of throat irritation for Auralin, an oral insulin, which should be expected because this pill is taken orally and passes by the throat before it gets to the stomach. The injection site discomfort, which is peculiar to the injectable insulin should also be expected, as it's a common known reaction for injectables because of needles. This is actually one of the big reasons why we want oral insulin.

![Adverse Reactions of Auralin](https://user-images.githubusercontent.com/104560999/183288702-90b56c9f-7014-45e5-9e9e-ce89c7ce38d8.png)
![Adverse Reactions of Novodra](https://user-images.githubusercontent.com/104560999/183288709-d001f170-4e92-492f-8e15-0709d959c045.png)

## Pre-trial/Post-trial Mean HbA1c change ( in %)
The HbA1c change is 0.40% for Novodra and 0.39% for Auralin.
That smaller difference in the mean is much clearer in the bar plot.

![Mean HbA1c change](https://user-images.githubusercontent.com/104560999/183288798-892b0343-b59e-4123-88ca-4a0e3ce7c883.png)

## Conclusion
Auralin is similarly effective to the injectable insulin, Novodra, according to the analysis of this clinical trial.

This means that Auralin has passed the Phase II clinical trial, hence there is a good chance of this new drug making it past phase III trial, the regulatory review process, as well as making it to the market. If this does, this oral insulin would be an enormous breakthrough in treating type 1 and type II diabetes melitus patients, as freedom from daily injections would liberate patients, help reduce missed doses, and therefore reduce irritating and sometimes serious complications from diabetes
