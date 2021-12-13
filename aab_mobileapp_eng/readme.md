## Training project "A/A/B Test in a Mobile App"
[Open the project in nbviewer](https://nbviewer.org/github/Emiranunuka/Yandex_Practicum_Data_Analyst_Training_Projects_English/blob/main/aab_mobileapp_eng/avdonina_aab_mobileapp_eng.ipynb)

### Tasks
There're presented data on operations in a mobile application of a startup that sells food products.
* to study users' behavior: sales funnel, conversions and failures (how many users get "stuck" and at what steps, how many users reach a purchase step).
* to examine results of A/A/B experiment with changing fonts in the app (designers want to change fonts, but managers are afraid that users would feel unusual). Based on the results of the A/A/B test (users were divided into 3 groups: two control with old fonts and one experimental - with new ones), to find out which fonts are better and decide which fonts to keep.
### Stack
Python, pandas, numpy, math, scipy, stats, proportions_ztest, matplotlib, plotly express, graph_objects
### Analysis
EDA and preprocessing: date format, duplicates, outliers. Exploratory analysis of the test groups: distribution of users by test groups, distribution of events by dates of experiment, number of events per user by groups, studying the sales funnel and sequence of steps, comparison of conversions through the funnel between control A/A groups and between control and test groups A/A/B. Multiple comparisons and Sidak's correction. Asessment of statistic significance of the differences by z-tests.
### Conclusions
There's found no a strict sequence of passing the steps through the funnel so it can't be asserted that users get "stuck" at any steps. Conversions in the test group decreased on the most screens of the app comparing with the control groups, but all the changes turned to be not statistically significant. There're supposed reasons caused such not significant results.
### Status of the project
+ Completed.
