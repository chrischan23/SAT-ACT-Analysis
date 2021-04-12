![](http://upl.stack.com/wp-content/uploads/2013/02/ACT-and-SAT-629x421.jpg)
## SAT - Moulding the Future of America
>_“Education is the most powerful weapon which you can use to change the world”_ – Nelson Mandela

In the wake of a competitive standardized test market, young americans now have a plethora of tests to choose from. While we are seeing high participation rates across America, there are still areas with relatively lower rates which could be explained by the following:
* Compulsory requirement of another standardized test 
* Taking the path of less resistance: participating in an "easier" standardized test to score better.
* University and scholarship evaluation criteria based on other tests

We will analyze data trends to help us in identifying effective areas of focus, to better our SAT participation rates. 


## Problem Statement
* We will analyze SAT and ACT Participation Rates and test subjects scores for 2017 and 2018.
* Create visualizations and statistical inference from the data to spot trends and patterns.
* Recommend a state that we feel that allows us to increase SAT participation rates.

## Contents

- [2017 Data Import & Cleaning](#2017-Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Data Dictionary for All Data Used](#Data-Dictionary)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Data-Visualization)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data Dictionary

|<p style='text-align: left;'> Feature </p> |<p style='text-align: left;'> Type </p> |<p style='text-align: left;'> Dataset </p> | <p style='text-align: left;'> Description </p> |
|---|---|---|---|
|<p style='text-align: left;'> state </p> | Object  | SAT 2017 |<p style='text-align: left;'> US states where participants are from </p> |
|<p style='text-align: left;'> participation_sat_2017 </p>| Float  | SAT 2017 |<p style='text-align: left;'> Percentage of total students that participated in 2017 </p>  |
|<p style='text-align: left;'> erw_sat_2017 </p> | Float  | SAT 2017 |<p style='text-align: left;'> Mean score for Evidence-Based Reading and Writing in 2017 </p> |
|<p style='text-align: left;'> math_sat_2017 </p> | Float  | SAT 2017  |<p style='text-align: left;'> Mean score for Math in 2017 </p> |
|<p style='text-align: left;'> total_sat_2017 </p> | Float  | SAT 2017  |<p style='text-align: left;'> Total mean score(Evidence-Based Reading and Writing & Math) in 2017 </p> |
|<p style='text-align: left;'> participation_act_2017 </p> | Float  | ACT 2017  |<p style='text-align: left;'> Percentage of total students that participated in 2017 </p> |
|<p style='text-align: left;'> english_act_2017 </p> | Float  | ACT 2017  |<p style='text-align: left;'> Mean score for English in 2017 </p> |
|<p style='text-align: left;'> math_act_2017 </p> | Float  | ACT 2017  |<p style='text-align: left;'> Mean score for Math in 2017 </p> |
|<p style='text-align: left;'> reading_act_2017 </p> | Float  | ACT 2017  |<p style='text-align: left;'> Mean score for Reading in 2017 </p> |
|<p style='text-align: left;'> science_act_2017 </p> | Float  | ACT 2017  |<p style='text-align: left;'> Mean score for Science in 2017 </p> |
|<p style='text-align: left;'> composite_act_2017 </p> | Float  | ACT 2017  |<p style='text-align: left;'> Mean of total mean scores of (English, Math, Reading, Science) in 2017 </p> |
|<p style='text-align: left;'> participation_sat_2018 </p>| Float  | SAT 2018 |<p style='text-align: left;'> Percentage of total students that participated in 2018 </p>  |
|<p style='text-align: left;'> erw_sat_2018 </p> | Float  | SAT 2018 |<p style='text-align: left;'> Mean score for Evidence-Based Reading and Writing in 2018 </p> |
|<p style='text-align: left;'> math_sat_2018 </p> | Float  | SAT 2018  |<p style='text-align: left;'> Mean score for Math in 2018 </p> |
|<p style='text-align: left;'> total_sat_2018 </p> | Float  | SAT 2018  |<p style='text-align: left;'> Total mean score(Evidence-Based Reading and Writing & Math) in 2018 </p> |
|<p style='text-align: left;'> participation_act_2018 </p> | Float  | ACT 2018  |<p style='text-align: left;'> Percentage of total students that participated in 2018 </p> |
|<p style='text-align: left;'> english_act_2018 </p> | Float  | ACT 2018  |<p style='text-align: left;'> Mean score for English in 2018 </p> |
|<p style='text-align: left;'> math_act_2018 </p> | Float  | ACT 2018  |<p style='text-align: left;'> Mean score for Math in 2018 </p> |
|<p style='text-align: left;'> reading_act_2018 </p> | Float  | ACT 2018  |<p style='text-align: left;'> Mean score for Reading in 2018 </p> |
|<p style='text-align: left;'> science_act_2018 </p> | Float  | ACT 2018  |<p style='text-align: left;'> Mean score for Science in 2018 </p> |
|<p style='text-align: left;'> composite_act_2018 </p> | Float  | ACT 2018  |<p style='text-align: left;'> Mean of total mean scores of (English, Math, Reading, Science) in 2018 </p> |


## Conclusions and Recommendations

Recomend that we target **Iowa** as the state to improve SAT participation rate
* The most effective way is to increase participation is to make SAT mandatory.
* Iowa has currently no mandated SAT or ACT test requirements. Hence they will be easier to approach.
* Work with states to market SAT's strength in test preparation to provide assurance to states that they are able to achieve good scores. 


Additional data that we might have to better make a better assessement would be:
* College requirements for SAT and ACT for each state
* Percentage of successful admissions into college using either SAT or ACT
* Income of households that participants are from that choose SAT or ACT