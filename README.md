In this Kaggle competition, we developed machine learning models that emulate subgrid-scale atmospheric physics in an operational climate model—an important step in improving climate projections and reducing uncertainty surrounding future climate trends.

We used a custom R-squared metric for evaluation, but on a weighted solution.

Dataset was extremely larges, so initially we prepeard compressed batches of the dataset.

Then trained the model in each batch and ensembled the result.
