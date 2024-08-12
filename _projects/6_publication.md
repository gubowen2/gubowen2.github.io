---
layout: page
title: publication 6
description: LIRIC predicts Hepatocellular Carcinoma risk in the diverse U.S. population using routine clinical data
img: assets/img/LIRIC predicts Hepatocellular Carcinoma risk in the diverse U.S. population using routine clinical data.jpeg
importance: 3
category: 2024
---

Authors: Kai Jia, Bowen Gu, Pasapol Saowakon, Steven Kundrot, Matvey B. Palchuk, Jeff Warnick, Irving D. Kaplan, Martin Rinard, Limor Appelbaum

Published on: medRxiv

Background and Aims Hepatocellular Carcinoma (HCC) is often diagnosed late, limiting curative treatment options. Conversely, early detection in cirrhotic patients through screening offers high cure rates but is underutilized and misses cases occurring in individuals without cirrhosis. We aimed to build, validate, and simulate the deployment of models for HCC risk stratification using routinely collected Electronic Health Record (EHR) data from a geographically and racially diverse U.S. population.

Methods We developed Logistic Regression (LiricLR) and Neural Network (LiricNN) models for the general (GP) and cirrhosis populations utilizing EHR data from 46,79 HCC cases and 1,128,202 controls aged 40-100 years. Data was sourced from 64 Health Care Organizations (HCOs) from a federated network, spanning academic medical centers, community hospitals, and outpatient clinics nationwide. We evaluated model performance using AUC, calibration plots, and Geometric Mean of Overestimation (GMOE), the geometric mean of ratios of predicted to actual risks. External validation involved HCO location, race, and temporal factors. Simulated deployment assessed sensitivity, specificity, Positive Predictive Value, Number Needed to Screen for each risk threshold.

Results LiricLR and LiricNN (GP) achieved test set AUCs of AUC=0.8968 (95% CI: 0.8925, 0.9010) and AUC=0.9254 (95% CI: 0.9218, 0.9289), respectively, leveraging 46 established (cirrhosis, hepatitis, diabetes) and novel (frequency of clinical encounters, platelet, albumin, aminotransferase values) features. Average external validation AUCs of LiricNN were 0.9274 (95% CI: 0.9239, 0.9308) for locations and 0.9284 (95% CI: 0.9247, 0.9320) for races. Average GMOEs were 0.887 (95% CI: 0.862-0.911). Simulated model deployment of LiricNN provides performance metrics across multiple risk thresholds.

Conclusions Liric models utilize routine EHR data to accurately predict risk of HCC development. Their scalability, generalizability, and interpretability set the stage for future clinical deployment and the design of more effective screening programs.

The full paper is available at <a href="https://www.medrxiv.org/content/10.1101/2024.05.28.24307949v1">medRxiv</a>.