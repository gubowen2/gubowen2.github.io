---
layout: page
title: project 1
description: Experimental Study of PAGA and COVID-19 Patient Classification
img: assets/img/PAGA.jpg
importance: 1
category: Computer Science
---

This project aims at classifying the stage of COVID-19 patients (recovered, non-ICU, and ICU) according to the abundance of different types of cells in their blood samples using KNeighborsClassifier.

This project achieved the following:
<ul>
<li> Gathered blood samples from 20 recovered, 5 non-ICU, and 10 ICU COVID-19 patients. </li>
<li> Used python Scikit-Learn’s LASSO and LinearSVC functions to conduct dimension reduction on the samples and studied on the top 5 dominate cell types. </li>
<li> Used Python Scikit-Learn’s StratifiedKFold function to split the data into 5 training sets and 1 validation set and conducted supervised learning. </li>
</ul>

The GitHub repository of this project can be found at <a href="https://github.com/gubowen2/COMP-495-Research-Project/tree/master">here</a>, which includes both the code and the results.