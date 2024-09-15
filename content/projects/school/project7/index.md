---
title: "eHealth-KD Challenge 2021"
date: 2021-07-20T11:25:05-04:00
description: "UH-MMM submission for the eHealth-KD Challenge, hosted at the 3rd Iberian Languages Evaluation Forum."
menu:
  sidebar:
    name: eHealth-KD Challenge 2021
    identifier: project-7
    weight: 10
    parent: school
tags: ["Natural Language Processing", "Machine Learning", "Deep Learning", "Importing & Cleaning Data", "Programming"]
categories: ["Basic"]
---


### Summary

This is the solution presented by the UH-MMM group to the eHealth-KD challenge at IberLEF 2021.

* Two main subtasks for knowledge discovery were defined: entity recognition and relationship extraction.
* The evaluation of the task is divided into three scenarios: one corresponding to the detection of entities, one corresponding to the detection of relations between such pair of entities, and the third one corresponding to the extraction of both entities and relationships.
* For both subtasks, our proposal makes use of BiLSTM as contextual encoders and Dense layers as the tag decoder architecture of the model.
* In the challenge, the system ranked fifth in the main scenario, fourth in the scenario evaluating the first task, and fifth in the last scenario.
* The score obtained in the relationship extraction task shows that the proposed approach needs to be further explored.


{{< figure src="project7.jpg" title="Neural network architecture used in the first subtask" >}}

### **Skills**

- `Scikit-learn`
- Named Entity Recognition
- Relation Extraction
- `Keras`
- `NLTK`
- `Spacy`
- Neural Networks
- LSTM
  

### Resouces

- [GitHub Link](https://github.com/lorainemg/eHealthKD-competition)
- [Paper](https://github.com/lorainemg/eHealthKD-competition/blob/main/docs/ehealth_paper4.pdf)
- [Challenge Link](https://ehealthkd.github.io/2021)
