---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 5 Sec 35 V2         <br/>
**Topic**:  Random Forests and Grid Search<br/>
**Amount of time**: 60 minutes <br/>
**Author**: Greg Damico


***

#### Lesson Summary:

This lesson builds upon students knowledge of decision trees and introduces them to random forests. It starts with a quick review of building a decision tree and discusses issues of overfitting inherent in tree algorithms. From this, bagging is introduced before moving on to Random Forests. Finally, the lesson also briefly investigates how to use grid search to optimize parameters.

#### Topic:

Random Forests and Grid Search

#### Learning goals for this lesson:

* Students should be able to implement a random forest classifier using scikit-learn
* Students should be able to implement grid search to tune the hyperparamters for a random forest


#### Prerequisite knowledge:

* Students should have a strong working knowledge of importing, accessing and manipulating pandas DataFrames
* Students should have prior exposure to decision trees
* Students should have previous experience tuning and evaluating machine learning models, especially for classification
* While students do not have to have covered bootstrap sampling previously, bagging is a related method, and building off of their previous knowledge can strengthen student understanding

#### Prequisite Learn-Materials:

* [Ensemble Methods](https://github.com/learn-co-curriculum/dsc-ensemble-methods)
* [Random Forests](https://github.com/learn-co-curriculum/dsc-random-forests)
* [GridSearchCV](https://github.com/learn-co-curriculum/dsc-gridsearchcv)
* [Gradient Boosting and Weak Learners](https://github.com/learn-co-curriculum/dsc-gradient-boosting-and-weak-learners)

#### Post Learn-Materials:

* [Tree Ensembles and Random Forests - Lab](https://github.com/learn-co-curriculum/dsc-tree-ensembles-random-forests-lab)
* [GridSearchCV - Lab](https://github.com/learn-co-curriculum/dsc-gridsearchcv-lab)
* [Gradient Boosting - Lab](https://github.com/learn-co-curriculum/dsc-gradient-boosting-lab)
* [XGBoost](https://github.com/learn-co-curriculum/dsc-xgboost)
* [XGBoost - Lab](https://github.com/learn-co-curriculum/dsc-xgboost-lab)


#### Relevant learning goals from Airtable: 

*  ENSEMBLE.1.rec8nB7hd9mUAvq7l
*  ENSEMBLE.1.recXLJ6PyMHQ6ADEP
*  ENSEMBLE.2.recIfe8r135AHfIuM
*  ENSEMBLE.2.recWdr4bEUH29pRHF
*  ENSEMBLE.2.recu464GcODAyZe5V
*  ENSEMBLE.2.recvrgJNLEwmjnxYO
*  ENSEMBLE.3.recbrZJRzXM9I6FXO
*  ENSEMBLE.1.recBxP7Gcdob21Ems
*  ENSEMBLE.1.recLjSCaXPsKUf7u3
*  ENSEMBLE.1.recQI3ijckvGbGVY1
*  ENSEMBLE.1.recZtdaKHt6kT52tW
*  ENSEMBLE.1.recfEEHY0kf0xEoVy
*  ENSEMBLE.1.rechLX382hIDUOAYi
*  ENSEMBLE.2.rec8hwSt3yxbkWPK4
*  ENSEMBLE.2.recIfe8r135AHfIuM
*  ENSEMBLE.2.recLzzltnDLx4pQOO
*  ENSEMBLE.3.recvyzpEf4FjtxX0X
*  ENSEMBLE.1.recTlMXAPf9aUPLxd

#### Materials

* Ipython notebook

#### Vocab / Concepts 

* Random Forests
* Ensemble Methods
* Grid Search
* Hyperparameter
* Parameter space

#### Lesson Outline:

* Ensembles: From Decision Trees to Extra Trees
	* Review: Fitting a Decision Tree (10 minutes)
	* Bagging Trees (Bootstrap Aggregating) (15 minutes)
* Fitting a Random Forest (5 minutes)

*  Random Forest Algorithm (15 minutes)

Let's add an extra layer of randomization: Instead of using *all* the features of my model to optimize a branch at each node, I'll just choose a subset of my features.
* Fitting a Stand of Extremely Randomized Trees
	* Extra Trees Algorithm
		Sometimes we might want even one more bit of randomization. Instead of always choosing the *optimal* branching path, we might just choose a branching path at random. If we're doing that, then we've got extremely randomized trees.

* Gridsearching (10 minutes)

* Summary (5 minutes)
