# QSAR - Quantitative Structure-Activity Relationship

A QSAR analysis investigating the bioactivity of compounds targeting the aryl hydrocarbon receptor (AhR). The structural features of compounds are correlated with their biological activities. A predicitive machine learning model is built based on molecular fingerprint descriptors.

![Open Jupyter Notebook](QSAR%20-%20Quantitative%20Structure-Activity%20Relationship.ipynb)

## Workflow

1. Collect dataset from chEMBL about biological activity of AhR: compounds that have been biologically tested for their activity towards the target
2. Process bioactivity data: calculate Lipinski descriptors to evaluate the likelihood of compounds to be a drug-like molecule
3. Exploratory data analysis of Lipinski descriptors to visualize the difference of active and inactive subsets of compounds
4. Calculate Pubchem fingerprint descriptors using PaDEL-Descriptor
5. Use the dataset of molecular descriptors to build a predictive regression model

## Background

Bayer is targeting what appears to be a key player in orchestrating immune escape: the **aryl hydrocarbon receptor (AhR)**: “More and more research suggests that the AhR, once activated, triggers events that suppress immune responses and promote tumor progression. The AhR appears to be a central mediator in the whole process, so inhibiting it may reactivate immune responses and provide a new therapeutic strategy for patients with cancer."

![AhR pathway](img/Bayer-Ahr-Rezeptor_EN_01_0.jpeg)

Source: https://www.bayer.com/en/pharma/targeting-ahr-promising-new-approach-cancer-immunotherapy
