# ml-predict-bank-deposit

The classification aim is to predict if client will decide to take a term deposit 

**This is my final project for Kodolamacz Data Science Bootcamp.**

# Summary
During this case study I wanted to analyse bank marketing dataset for classification purposes.

Due to the fact that data has been highly unbalanced, using the standard way of modeling and checking the output based on accurency metric makes no sense. As only 11% of clients decided to take bank term.

To deal to with the unbalanced data I decided to check SMOTE, upsampled and downsampled techniques.

Performance increased after balancing the dataset.

XGBoost classifier using the upsampled method gives the best F1 score result.

I also tested if splitting customers into new and existing ones gives any interesting insights.

On the dataset related to new clients the F1 score was really low, which means that this model cannot accurately predict getting a bank term by a new customer.

On the dataset related to existing clients the F1 score shows much better results. I think such a model can be used to predict getting a bank term by an existing customer.
