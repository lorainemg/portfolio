---
title: "A Meta-Learning Strategy for Generic AutoML Pipelines."
date: 2021-11-17T11:25:05-04:00
description: "A Meta-Learning proposal to improve the performance of AutoML systems,, recommending initial ML algorithms to start the search."
menu:
  sidebar:
    name: Meta-Learning for AutoML
    identifier: project-10
    weight: 10
    parent: school
tags: ["Data Manipulation", "Machine Learning", "Recommender Systems", "AutoML", "Programming", "Probability & Statistics", "Data Visualization", "Hypothesis Testing"]
categories: ["Basic"]
---
#### Summary

The field of **Automated Machine Learning (AutoML)** has been highlighted as one of the main alternatives to finding good solutions for complex machine learning problems. Despite the recent success of AutoML, many challenges remain. Learning AutoML is a time-consuming process and can be computationally inefficient. Meta-learning is described as the process of learning from past experiences by applying various learning algorithms to different types of data and thus reducing the time needed to learn new tasks. One of the advantages of meta-learning techniques is that they can serve as efficient support for the AutoML process, learning from previous tasks the best algorithms to solve a certain type of problem. In this way, it is possible to speed up the AutoML process, obtaining better results in the same period of time. The objective of this thesis project is to design a meta-learning strategy for generic domains in machine learning.

The implemented meta-learning proposal is capable of addressing a wide variety of tasks by selecting features capable of representing the space defined by them. AutoGOAL has been replaced as a complementary AutoML system, which stands out for its ability to generate effective solutions for a wide range of domains, allowing you to solve a large number of tasks. AutoGOAL is used for pipeline generation algorithms to create the knowledge base and pipeline search initialized with the designed meta-learning approach.

The developed meta-learning approach consists in the selection of a set of algorithm pipelines to be recommended in the initialization of the optimization process of an AutoML system. The choice of this set of pipelines is done by a ranking approach, where for a new dataset the k best algorithm pipelines are selected. For this, several strategies were implemented. Experimental evaluation performed on a large number of datasets shows that these meta-learning strategies performed better in terms of algorithm pipelines found than AutoGOAL without meta-learning, without any consideration of specific domain or problem.

{{< figure src="project10 - adquisition.jpg" title="First phase of the meta-learning proposal, were the adquisition of the knowledge is done." >}}

{{< figure src="project10 - application.jpg" title="Second phase of the meta-learning proposal, were the knowledge of the previous machine learning problems is used to recommend a pipeline for the solution of the current task." >}}

#### **Skills**

- Scikit-Learn
- XGBoost
- Model Training
- Model Selection
- Programming
- Docker

#### Resources
- [Solution Code GitHub Link](https://github.com/lorainemg/autogoal)
- [Experiments Code GitHub Link](https://github.com/lorainemg/experiments-thesis)
- [Dissertation GitHub Link](https://github.com/lorainemg/dissertation)
