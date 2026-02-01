# Lithology-Prediction-using-ML-Models
This project focuses on lithology prediction using well log data and supervised machine learning models. Advanced preprocessing and feature extraction were applied on large datasets, achieving 91% accuracy with a Neural Network. The model supports improved reservoir characterization and drilling efficiency.

This repository contains a complete machine learning workflow for lithology (facies) classification using well logging data. Multiple supervised classification algorithms are implemented and evaluated using standard performance metrics such as accuracy, precision, recall, and F1-score. The project also includes detailed data analysis, visualization, and interpretation of the well log dataset.

# Dataset Information

The dataset used in this project is based on a class exercise from the University of Kansas. It consists of well log measurements collected from two of the largest gas-producing fields in North America: the Hugoton and Panoma Fields.

Lithology facies (rock types) were identified from core samples taken at half-foot intervals and then correlated with corresponding wireline log readings at each well location.

Feature Variables

The dataset includes seven input features:

GR: Gamma Ray log measuring natural radiation

ILD_log10: Log-transformed resistivity measurement

PE: Photoelectric effect log

DeltaPHI: Difference in porosity index

PHIND: Average neutron-density porosity indicator

NM_M: Nonmarine–marine environment indicator

RELPOS: Relative stratigraphic position

# Facies Classes

The target variable consists of nine lithology facies types, representing different rock formations:

SS – Nonmarine Sandstone

CSiS – Nonmarine Coarse Siltstone

FSiS – Nonmarine Fine Siltstone

SiSh – Marine Siltstone and Shale

MS – Mudstone (Limestone)

WS – Wackestone (Limestone)

D – Dolomite

PS – Packstone-Grainstone (Limestone)

BS – Phylloid-Algal Bafflestone (Limestone)

These facies are not sharply separated and often transition gradually into neighboring rock types. Therefore, classification errors between adjacent facies are expected due to their geological similarity.

# Adjacent Facies Relationships

Certain facies groups are closely related and may overlap in characteristics. Below are some expected neighboring facies:

SS ↔ CSiS

CSiS ↔ FSiS

MS ↔ WS

WS ↔ D ↔ PS

PS ↔ BS

# Project Highlights

Exploratory Data Analysis (EDA) of well log features

Training and comparison of multiple classification models

Evaluation using precision, recall, accuracy, and F1-score

Lithology prediction to support reservoir characterization
