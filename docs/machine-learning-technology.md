
# Machine Learning Technology

## Proposed Approach

The project will investigate supervised machine learning to estimate a defined spoilage-related outcome from suitable historical data.

## Candidate Models

- Decision Tree: interpretable baseline.
- Random Forest: combines multiple decision trees.
- XGBoost: gradient-boosted tree model.

## Proposed Workflow

1. Obtain a suitable labelled dataset.
2. Inspect and preprocess the data.
3. Split the data into training, validation,
   and test sets.
4. Train and compare candidate models.
5. Evaluate the selected model on held-out data.
6. Integrate eligible predictions into the
   inventory prioritization workflow.

## Evaluation

For classification, report precision, recall, F1-score, and a confusion matrix. For regression, report MAE and RMSE.

Compare the selected model with a simple rule-based baseline.

## Limitations

Model performance depends on data quality, target-label reliability, and the similarity between training data and actual household use.

A prediction must not be treated as a guarantee that food is safe to consume.

## Status

Proposed methodology. Model implementation and evaluation results are pending.
