---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 4               <br/>
**Topic**: Extensions to Linear Regression   <br/>
**Amount of time**: 60  minutes  <br/>
**Author**: Laura Colon-Melendez, Greg Damico

Ported from the ds-lesson-starters repository [here](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/interaction_regularization). 

***

#### Lesson Summary:

A brief reminder of multiple linear regression is presented to students to motivate a discussion on adding interaction and polynomial terms. We stress that when adding interaction and polynomial terms to the linear regression model, it remains a linear regression exercise because the coefficients are linear. Next, the bias-variance tradeoff is discussed by defining bias and variance, and relating them to model complexity and under/overfitting. Regularization is presented as a technique for dealing with overfitting and models that are too complex. Students use sklearn to compare the performance of a baseline linear regression model to a Lasso regression model fit to the Boston housing dataset. Optional sections include practice problems with creating interaction and polynomial terms, and a question on applying Ridge regression to the Boston housing dataset. 

#### Topic:

Extensions to Linear Regression: Interactions, Polynomial Regression, and Regularization


#### Learn.co material:

[Interactions](https://github.com/learn-co-curriculum/dsc-interaction-terms)

[Interactions - Lab](https://github.com/learn-co-curriculum/dsc-interaction-terms-lab)

[Polynomial Regression](https://github.com/learn-co-curriculum/dsc-polynomial-regression)

[Polynomial Regression - Lab](https://github.com/learn-co-curriculum/dsc-polynomial-regression-lab)

[Bias-Variance Trade-Off](https://github.com/learn-co-curriculum/dsc-bias-variance-trade-off)

[Bias-Variance Trade-Off - Lab](https://github.com/learn-co-curriculum/dsc-bias-variance-trade-off-lab)

[Ridge and Lasso Regression](https://github.com/learn-co-curriculum/dsc-ridge-and-lasso-regression)

[Ridge and Lasso Regression - Lab](https://github.com/learn-co-curriculum/dsc-ridge-and-lasso-regression-lab)


#### Prerequisite knowledge: 

* Students should be familiar with the basics of multiple linear regression, including the cost function. 

* Students should be able to solve multiple linear regression problems with scikit-learn.

* Students should understand the concepts of:
    * coefficient of determination
    * adjusted coefficient of determination
    * mean squared error 

#### Prerequisite Learn.co material:

[Project: Regression Modeling with the Boston Housing Dataset](https://github.com/learn-co-curriculum/dsc-regression-boston-lab)

#### Learning goals for this lesson:

* Students can define interactions in the context of modeling.  

* Students can use `PolynomialFeatures` from sklearn in Python to create additional polynomial and interaction terms.

* Students can explain the bias-variance tradeoff. 

* Students can explain what Lasso and Ridge Regression are, and how they are used in Regularization.

* Students can use sklearn to fit regularized (Lasso) linear regression models. 

#### Relevant learning goals from Airtable 

* EXT_TO_LINEAR_REG.1.recrjIuZwo191eiVN

* EXT_TO_LINEAR_REG.1.recHAgVHQXGMZddJL

* EXT_TO_LINEAR_REG.1.rec7QQyt7G25bPMBv

* EXT_TO_LINEAR_REG.1.recoY44Cp0uJpBkRW

* EXT_TO_LINEAR_REG.1.reciAKKIFYca9FXZN

* EXT_TO_LINEAR_REG.1.recbFQSL524djmtNH

* EXT_TO_LINEAR_REG.1.recTg9MfSJOIZnE48

* EXT_TO_LINEAR_REG.2.recUktwfnPEW7MnPy

* EXT_TO_LINEAR_REG.2.reclFIgVBpIV7iCqw

* EXT_TO_LINEAR_REG.2.recOIJleuxszIX0zi

* EXT_TO_LINEAR_REG.2.recmVITTItuyov6BF

#### Misconceptions / Notes

* A common misconception is that when we train models we want them to fit the data perfectly. 
    * We actually want models that can generalize to unseen data! 
   

#### Materials

- Ipython notebook

#### External Resources

[Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html) 

[Understanding the Bias-Variance Tradeoff](https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229)

[Overfitting vs. Underfitting: A Complete Example](https://towardsdatascience.com/overfitting-vs-underfitting-a-complete-example-d05dd7e19765)

[The Bias-Variance Tradeoff](https://djsaunde.wordpress.com/2017/07/17/the-bias-variance-tradeoff/)

#### Vocab / Concepts 

* Interactions
* Bias-Variance Tradeoff
* Regularization / Penalty term in cost function


#### Lesson Outline:

Interactions and Polynomial Regression (10 minutes)
* Interaction terms and polynomial terms can be added to linear models. 
    * Important concept to grasp: Models are still linear because they're linear in the coefficients.

Bias Variance Tradeoff (10-15 minutes)
* Connection to underfitting and overfitting. 

Regularization (20-25 minutes)
* Regularization as a technique to control for overfitting
* Modifications to the cost function
* Python implementation of Lasso regression
    * Baseline linear regression model compared to model with polynomial and interaction terms 
        * Overfitting
    * Lasso regularization as a technique to reign in overfitting and deal with model complexity.

Summary (5 minutes)

Wiggle room: 5 minutes 
