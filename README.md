# CMSS-Project-2026
Unsupervised Detection of Political Homophily Through Positive Mention Networks on X During the 2024 U.S. Presidential Election

## Project Overview
Social media platforms such as X (formerly Twitter) enable political interaction, but it often raises concerns that people mainly interact with others who already share their views.

In this project, we investigate whether users who mention each other during the 2024 U.S. election tend to form politically similar groups.

To do this, we build an interaction networks from election-related tweets (from May-July and October) and apply the Louvain community detection algorithm to find groups of users.

We then analyse how likely these communities are echo chambers with the E/I index and we use degree centrality to understand which users are most influential inside each community.

## Key Findings
- Strong evidence of political homophily across all detected communities  
- Echo chambers are present in both time periods (May-July and October)
- Communities in October are surprisingly slightly less closed than in May  
- We also observe smaller thematic groups like media-related and crypto-related clusters

## Data
The dataset used in this project comes from: https://github.com/sinking8/x-24-us-election

It contains X (Twitter) interaction data related to the 2024 U.S. Presidential Election.
The dataset is used under its original license and is not included in this repository. Please refer to the original source for access and licensing details.

## Notebook

[CMSS_Project_Code.ipynb](CMSS_Project_Code.ipynb)

## Full Report

[Download full report (PDF)](report.pdf)
