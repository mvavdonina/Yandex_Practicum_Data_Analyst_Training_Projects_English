## Training project "EU A/B Test's Analysis"
[Open the project in nbviewer](https://nbviewer.org/github/Emiranunuka/Yandex_Practicum_Data_Analyst_Training_Projects_English/blob/main/ab_test_eng/avdonina_eu_ab_test.ipynb)

### Tasks
Assessment of A/B test:
* evaluation of the test's correctness (intersection with other tests and marketing events by time and audience);
* the A/B test results' analysis.
### Stack
Python, pandas, matplotlib, graph_objects, scipy, stats, proportions_ztest
### Analysis
EDA. Preprocessing: dates format, gaps, duplicates. Evaluation of the test's correctness: choice of the test timing, intersection of the test's audience with a competing test and marketing campaigns, users' affiliation by region, necessary percent of new users, distribution of users by test groups. Exploratory analysis of the test groups: number of events per user by groups, distribution of events by dates by groups, comparison of conversions through the funnel in A and B groups. Asessment of statistic significance of the differences by z-tests (one-side and two-sided). Multiple comparisons and Sidak's correction.
### Conclusions
There're defined few reasons why the test should be considered as invalid. According to the data obtained, the metrics of the test group B have not been improved, but on the contrary have been significantly deteriorated, and the difference is statistically significant. The new payment funnel should not be "rolled out" to the audience - it performed poorly on this not entirely correct test.
### Status of the project
+ Completed.
