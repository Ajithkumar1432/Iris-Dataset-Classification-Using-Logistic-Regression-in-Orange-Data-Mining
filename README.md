# Iris Dataset Classification Using Logistic Regression in Orange

## Description
This workflow in Orange demonstrates a classification process using the Iris dataset. The Datasets widget loads the data, which is then explored using the Data Table and visualised with a Scatter Plot. A Data Sampler splits the dataset into training and testing subsets. The Logistic Regression model is trained on the sampled data and makes predictions. Results are evaluated using the Test and Score widget, and the Confusion Matrix visualises the model’s accuracy and classification performance. This setup provides a complete, easy-to-follow pipeline for supervised learning in Orange.

## Tools & Technologies
- Orange Tool
- Logistic Regression
- Dataset (Iris)

<img width="1387" height="952" alt="Snap" src="https://github.com/user-attachments/assets/dc3f9ea7-e551-4849-ab55-a7302a3de91d" />

## How to Run
1. Open Orange and load `iris_dataset.ows`.
2. Ensure all widgets are connected as shown in the screenshot.
3. Run the workflow to see predictions and evaluation metrics.

## Key Results
- Logistic Regression achieved high accuracy on the Iris dataset.
- The confusion matrix shows that most predictions are correct.
- The project provides multiple options, each presenting specific attribute values from the Iris dataset for analysis and visualisation.

## Conclustion
The workflow successfully demonstrates how Logistic Regression can accurately classify the Iris dataset using Orange. The pipeline—from data exploration to evaluation—shows high performance and provides a clear example of supervised learning in practice.

## Future Works
- Experiment with other classification algorithms (e.g., Decision Trees, Random Forest, SVM).
- Apply feature selection or dimensionality reduction techniques for deeper insights.
- Test the workflow on larger or more complex datasets.
- Explore hyperparameter tuning to further improve model accuracy.

