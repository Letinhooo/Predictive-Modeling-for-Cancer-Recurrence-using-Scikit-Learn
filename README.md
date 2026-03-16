# Predictive-Modeling-for-Cancer-Recurrence-using-Scikit-Learn
1. Project Overview

The goal of this project was to predict breast cancer recurrence based on clinical and geometric features of cell nuclei.
2. Key Workflow

    Exploratory Data Analysis (EDA): Visualized class distribution and feature correlations using Seaborn.

    Preprocessing: Handled missing values in lymph_node_status and mapped categorical targets to numeric values.

    Model Comparison:

        Decision Tree: Optimized depth and split criteria.

        Gradient Boosting: Focused on ensemble learning performance.

        SVM: Implemented within a Pipeline with StandardScaler.

    Feature Engineering: Used RFE (Recursive Feature Elimination) to select the most significant features like Time, texture1, and tumor_size.

3. Results

The Gradient Boosting model achieved the highest baseline accuracy (~80%). Feature selection helped maintain high performance while significantly reducing model complexity (from 33 to 8 features).
