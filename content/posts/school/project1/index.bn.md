---
title: "Schizophrenic Classification"
date: 2018-05-09T10:58:08-04:00
description: "Classification of schizophrenic patients by applying the wavelet transform to evoked potentials and machine learning."
summary: The objective of this work is to generate a model that allows distinguishing schizophrenic patients from healthy patients using the visual paradigm of the P300 and applying the discrete transform of wavelets as a method of extracting characteristics.
menu:
  sidebar:
    name: Schizophrenic Classification
    identifier: project-1
    weight: 10
    parent: school
tags: ["Data Modeling", "Machine Learning", "Data Manipulation", "Importing & Cleaning Data"]
categories: ["Basic"]
hero: hero.png
---

Schizophrenia is a psychiatric disorder that affects a large part of the world’s population. Among its symptoms are the inability to process information, mainly in attention tasks and work memory. That is why the use of evoked potentials related to events is a useful tool to support the subjective decision processes of medical specialists. The objective of this work is to generate a model that allows distinguishing schizophrenic patients from healthy patients using the visual paradigm of the P300 and applying the discrete transform of wavelets as a method of extracting characteristics.

#### Summary

* The database used has records of evoked potentials of 54 healthy subjects and 54 patients matched by age and sex.
* The discrete wavelet transform was applied with the Daubechies mother wavelet of order 4 and level 5.
* 180 characteristics were extracted per subject and SVM was applied as a learning algorithm using cross-validation to obtain a 62.93 % accuracy.

<img src="project1.png" alt="Fourier Transform" style="width:100%;" title="Calculation of the Fast Fourier Transform of the reconstructed signal from the A5 coefficients that represents the Delta band [0.5-4Hz]"/>

#### **Skills**

- Machine Learning
- SVM
- Time-Series Analysis
- Scikit-Learn
- Wavelet Transform
- Evoked Potential

#### Resources

- [GitHub Link](https://github.com/lorainemg/schizophrenic-classification)

