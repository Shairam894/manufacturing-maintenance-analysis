# Manufacturing Maintenance Analysis

## Project Overview

This project analyzes industrial machine maintenance and failure records to evaluate maintenance patterns and identify machines that may require additional attention.

The analysis uses the Microsoft Azure Predictive Maintenance dataset.

## Objectives

- Clean and validate maintenance data
- Analyze machine maintenance frequency
- Analyze machine failure patterns
- Compare maintenance activity with failure occurrence
- Compare machine categories/models
- Examine failure activity before and after maintenance
- Identify machines with high maintenance and high failure counts
- Train a Decision Tree model
- Evaluate model performance
- Provide practical maintenance recommendations

## Dataset

The analysis uses:

- Maintenance records
- Machine information
- Failure records

The selected public dataset does not directly contain downtime hours or production volume. Therefore, failure occurrence and maintenance frequency are used as operational indicators.

## Visualizations

1. Maintenance Frequency by Machine
2. Failure Count by Machine
3. Maintenance Frequency vs Failure Count
4. Failure Type Distribution

## Machine Learning

A Decision Tree Classifier was trained to predict whether a machine had a recorded failure based on available machine-level characteristics and maintenance activity.

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Feature Importance

## Key Findings

- Maintenance frequency varies across machines.
- Failure events are concentrated among certain machines.
- Some machines show both high maintenance activity and high failure counts.
- Failure patterns vary across machine models.
- Failure-type distribution can help prioritize maintenance activities.
- Decision Tree feature importance identifies variables associated with failure prediction.

## Recommendations

- Prioritize machines with repeated failures.
- Investigate machines with high maintenance and high failure counts.
- Review recurring failure types.
- Develop maintenance strategies according to machine model.
- Use failure history to prioritize inspections.
- Monitor maintenance effectiveness using measurable operational indicators.

## Limitation

The public dataset does not directly provide downtime hours or production volume. Therefore, the project does not claim a direct reduction in downtime. Failure occurrence is used as an operational proxy.