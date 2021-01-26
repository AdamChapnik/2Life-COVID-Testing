# 2Life Communities: Patterns in Responses to COVID-19 Testing Consent-Waiver
This is an analysis of 2Life Communities resident demographic data in relation to their responses to a COVID-19 testing consent waiver, in order to understand patterns among residents who declined to be tested for the purpose of efficiently and effectively reapproaching these residents to reconsider their decisions. I use mulitple logistic regressions with interactions for each of the five campuses, which I create via a series of algorithms that search for the best model for each campus dataset. I utilize the R functions gbm, bestglm, glmulti, as well as a series of custom genetic algorithms based on code published in a series of blog posts by Colin Priest (https://colinpriest.com/2015/07/10/efficiently-building-glms-part-1/). I find slightly different patterns in responses on each campus. Among these patterns, I find:

- older, less healthy, and more frail residents have a higher odds of consenting to be tested, although the effect of these decreases for residents with higher incomes;
- residents who demonstrate patterns of leaving their rooms often, such as those who work or own cars, have higher odds of consenting to be tested; and
- younger residents who live with at least one other resident have a higher odds than older residents in similar living situations to have only one resident of the pair consent to be tested.

Original datasets have been removed, and confidential information is not included, although the original code remains. The dataset 2Life_Data.csv contains all of the data necessary to run the code. The proper order of the code is COVID_Survey_Data&Exploration.Rmd, COVID_Models.Rmd, then Results&Discussion.Rmd. 

Results&Discussion.Rmd contains a complete summary and interpretation of the results of the analysis, as well as a discussion of implementation strategies, and was used as the official report.
