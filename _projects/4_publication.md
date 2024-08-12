---
layout: page
title: publication 4
description: Extraction and Imputation of Eastern Cooperative Oncology Group Performance Status From Unstructured Oncology Notes Using Language Models
img: assets/img/Extraction and Imputation of Eastern Cooperative Oncology Group Performance Status From Unstructured Oncology Notes Using Language Models.jpg
importance: 1
category: 2024
---

Authors: Wenxin Xu, Bowen Gu, William E Lotter, Kenneth L Kehl

Published on: JCO Clinical Cancer Informatics

Purpose
Eastern Cooperative Oncology Group (ECOG) performance status (PS) is a key clinical variable for cancer treatment and research, but it is usually only recorded in unstructured form in the electronic health record. We investigated whether natural language processing (NLP) models can impute ECOG PS using unstructured note text.

Materials and Methods
Medical oncology notes were identified from all patients with cancer at our center from 1997 to 2023 and divided at the patient level into training (approximately 80%), tuning/validation (approximately 10%), and test (approximately 10%) sets. Regular expressions were used to extract explicitly documented PS. Extracted PS labels were used to train NLP models to impute ECOG PS (0-1 v 2-4) from the remainder of the notes (with regular expression–extracted PS documentation removed). We assessed associations between imputed PS and overall survival (OS).

Results
ECOG PS was extracted using regular expressions from 495,862 notes, corresponding to 79,698 patients. A Transformer-based Longformer model imputed PS with high discrimination (test set area under the receiver operating characteristic curve 0.95, area under the precision-recall curve 0.73). Imputed poor PS was associated with worse OS, including among notes with no explicit documentation of PS detected (OS hazard ratio, 11.9; 95% CI, 11.1 to 12.8).

Conclusion
NLP models can be used to impute performance status from unstructured oncologist notes at scale. This may aid the annotation of oncology data sets for clinical outcomes research and cancer care delivery.

The full paper is available at <a href="https://ascopubs.org/doi/abs/10.1200/CCI.23.00269">JCO Clinical Cancer Informatics</a>.