---
title: "Probabilistic Race and Ethnicity Prediction Using Group-Specific Name Lists"
collection: publications
category: preprint
permalink: /publication/2026-lbisg
excerpt: "This paper proposes $\ell$BISG, a method for obtaining group membership probabilities from names and geography when only lists of distinctive or common names for each group are available as well as *possibly* some prior geographic information. Such probabilities are important for estimating social disparities when group membership is missing."
date: 2026-05-08
venue: "arXiv"
paperurl: "https://arxiv.org/abs/2610.06273"
citation: "Chasalow, Kyla, Noah Dasanaike, and Kosuke Imai. 2026. Probabilistic Race and Ethnicity Prediction Using Group-Specific Name Lists. arXiv preprint arXiv:2610.06273."
---

### Abstract

Statistically valid estimation of racial and ethnic disparities often requires inferring the probability that an individual belongs to a particular racial or ethnic group given only their name and geographic location. The standard approach, Bayesian Improved Surname Geocoding (BISG), relies on group population frequencies for each name. Although the U.S. Census Bureau provides such information for common names and a limited set of racial categories, comparable data do not exist for many racial and ethnic groups and are rarely available outside the U.S. We propose the list-powered BISG (ℓBISG) method, which can be used to derive calibrated group probabilities from group-specific name lists. These lists may be compiled based on expert knowledge or generated synthetically using large language models (LLMs), and thus may be subject to unknown biases. Representing names as embeddings, we treat list membership as a proxy prediction task and apply a correction based on proximal inference to recover the target group probabilities. We validate the method on U.S. voter files with self-reported race, on the full-count 1900 U.S. Census, and on the Lebanese voter registry. We find that LLM-generated name lists yield accurate and well-calibrated probabilities as well as precise disparity estimates comparable to those obtained using methods that require name-race data. Thus, ℓBISG substantially broadens the applicability of probabilistic race and ethnicity prediction to settings where name-race data are unavailable. 
