# ML-qsar-bod-classification
Machine learning-based QSAR classification model for Biochemical Oxygen Demand (BOD) prediction using 1,624 chemical structures and Random Forest classification.

## Objectives

- Develop QSAR-based machine learning models for biodegradability classification
- Predict whether compounds are Readily Biodegradable (RB) or Not Readily Biodegradable (NRB)
- Analyze the relationship between molecular descriptors and BOD activity
- Compare Random Forest and GA-LDA algorithms for classification performance
- Validate model robustness using ROC-AUC, MCC, Accuracy, and F1-score

## Dataset

The dataset was collected from:
- QSAR Toolbox
- ECOTOX Knowledgebase

Chemical compounds with experimentally verified Biochemical Oxygen Demand (BOD) endpoints were selected. Molecular structures were exported in SMILES format for descriptor generation and analysis.

## Methodology

1. Data Collection from QSAR Toolbox and ECOTOX
2. Molecular Descriptor Calculation using PaDEL-Descriptor
3. Descriptor Curation and Correlation Filtering
4. Data Preprocessing and Normalization
5. Labeling into RB and NRB classes
6. Feature Selection using Genetic Algorithm
7. Model Training using:
   - Random Forest (RF)
   - GA-LDA
8. Internal and External Validation
9. Statistical Performance Evaluation

## Project Highlights

- Developed QSAR-based machine learning models for biodegradability classification of chemical compounds
- Classified compounds as Readily Biodegradable (RB) and Not Readily Biodegradable (NRB)
- Processed a dataset of experimentally validated compounds retrieved from QSAR Toolbox and ECOTOX Knowledgebase
- Computed 1D and 2D molecular descriptors using PaDEL-Descriptor software
- Implemented and compared Random Forest and GA-LDA classification algorithms
- Performed descriptor filtering, preprocessing, normalization, and feature selection
- Evaluated model performance using Accuracy, ROC-AUC, MCC, Precision, Sensitivity, Specificity, and F1-score
- Achieved ROC-AUC scores of 0.9022 (training) and 0.9137 (test dataset)

## Results

### Internal Validation
- Accuracy: 100%
- Precision: 100%
- Sensitivity: 100%
- Specificity: 100%
- ROC-AUC: 0.9022

### External Validation
- Accuracy: 87.18%
- Precision: 78.38%
- Sensitivity: 80.56%
- Specificity: 90.12%
- ROC-AUC: 0.9137

  
