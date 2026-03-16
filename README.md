# CSC4009 Fairness Analysis

This repository contains my analysis of bias and fairness in the Adult Census Income dataset. The project focuses on how protected attributes such as sex and race relate to income outcomes and how different machine learning choices affect fairness metrics.

## What the Repository Does

The notebooks cover four parts of the assignment:

- `data_exploration.ipynb` explores the dataset structure, class balance, and protected attribute distributions.
- `cause_of_unfairness_notebook.ipynb` examines dataset bias using contingency tables, chi-square tests, and visualizations.
- `group_fairness_analysis.ipynb` trains a classifier and measures group fairness across sex and race using metrics such as accuracy, true positive rate, false positive rate, and selection rate.
- `method_analysis_notebook.ipynb` compares classifier choices and imbalance-handling strategies to study the trade-off between predictive performance and fairness.

## Included Assets

- `CSC4009-AI-Fairness-datasets/adult.data.csv` is the dataset used by the notebooks.
- `charts/` contains generated figures used in the fairness analysis.

## Main Findings

The analysis shows clear representation and outcome differences across protected groups in the dataset. It also shows that model configuration changes can shift both accuracy and disparity, so fairness is not fixed by the dataset alone and must be evaluated at the modeling stage as well.

## Notes

This repository intentionally excludes lecturer starter files, duplicate auto-generated Python exports of notebooks, and personal report drafts so that the uploaded project only contains the core analysis work.
