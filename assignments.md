---
title: Assignments
layout: home
menuItem: Assignments
menuPosition: 6
---

## Assignment 1, Expert forecasts of the 2020 US Election

Pre-registration due: Monday, November 2, 2020 11:59pm ET
Final results due: Tuesday, November 24, 2020 11am ET (before last class)

This activity will give you practice:
- Developing a research question about prediction
- Picking a measure of predictive performance
- Pre-registering research projects

Tetlock (2005) evaluated the predictions of experts by creating a forecasting tournament that asked questions about the probabilities that the event will take place across many domains. Then, he compared those estimated probabilities to the true outcome of the events. In this activity, your group will create your own forecasting tournament around the 2020 US election, pre-register your design, and then submit your results.  Like Tetlock's project, you should have multiple approaches to making predictions and you should have each approach make predictions for several events.

### Helpful information

#### Pre-registration

We recommend that you post your pre-registration on the [Open Science Framework](https://osf.io/prereg/), but you can use any platform you wish.

We recommend that you read [Nosek et al. (2018)](https://www.pnas.org/content/115/11/2600) to learn more about pre-registration.

#### Project ideas

There is a large literature about forecasting elections.  Here are some rough ideas for hypotheses that you might want to pursue:

- Hypotheses about different types of elections (e.g. are people better at predicting House races or Senate races?)
- Hypotheses about how predictions change as the election approaches
- Hypotheses about the accuracy of different approaches to prediction (e.g., individuals vs teams)

Here are some papers that might provide more ideas:

- Nadeau, R., Dassonneville, R., Lewis-Beck, M., & Mongrain, P. (2019). [Are election results more unpredictable? A forecasting test](https://dx.doi.org/10.1017/psrm.2019.24). _Political Science Research and Methods_.

## Assignment 2, Replication and extension of [Muchlinksi et al. (2016)](https://doi.org/10.1093/pan/mpv024): Random forest vs logistic regression

Due: Friday, October 9, 2020 11:59pm ET (right before fall break begins)

1) Replicate the corrected version of [Muchlinksi et al. (2016)](https://doi.org/10.1093/pan/mpv024). Specifically you should make the separation plots (Fig 1), ROC curves (Fig 2), F1-scores (Fig 3), and Table 1 for the main models in the paper.

2) Extend their result in some way.  Here are some suggestions, but please don’t feel limited to these ideas.
- For which cases does the random forest do better and why? Can we use what this learned from the random forest to build a better logistic regression model? For example, is the random forest discovering interactions between variables or non-linearities or both? For some ideas about how to use random forest and logistic regression together, see Colaresi and Mahmood (2017).
- Find another setting and compare the results from logistic regression and random forest.  For some other possible ideas, see https://doi.org/10.1016/j.jclinepi.2019.02.004
- Reduce or expand the set of predictor variables and see how the results change.  Is it fair to compare the Fearon and Laitin (2003), Collier and Hoefeller (2004), and Hengre and Sambanis (2006) models which have a small number of predictors to the random forest model, which has a large number of predictors?
- Compare the performance of in-sample and out-of-sampling predictions for the models.
- Train the models on one part of the world and then attempt to use them to predict civil wars in a different part of the world?  Which models generalize better?
- Explore alternative approaches to cross-validation, beyond those proposed in Neunhoeffer and Sternberg (2019). The cross-validation was organized around country-years. Do cross-validation where you drop out years or drop out countries.  Do the results change? How do you think cross-validation should be done for this research question? How does the relative performance of the models vary by the year used to separate training and test sets. In footnote 2, Muchlinksi et al. (2019) argue that 1989 is a particularly unusual year.