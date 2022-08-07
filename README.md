# Clinical-Trial-Data-Analysis

The increasing prevalence of diabetes in the 21st century ia a problem, an epidemic even.

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
