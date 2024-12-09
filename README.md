# Where to Find Files

## Three Class Files

* Meral Baseline and BERT Modeling: baseline modeling and the BERT classifier work. 
* Meral ClimateBERT Modeing: ClimateBERT classifier work
* Meral GridSearch Analysis: Analyzing exported grid search work for BERT and ClimateBERT. The resulting parameters from each analysis were plugged back into the BERT and ClimateBERT notebooks.
* Meral Test Results Analysis: Analyze the test results, look at trends in errors.
* Meral Results Folder: Where hyperparameter tuning and test results for BERT and ClimateBERT are.

Please Note: There are errors that come up when running the CLS token verison of the BERT and ClimateBERT models. These are identical to the errors in the BERT lesson notebook when using the CLS token, and we believe they are the result of the model not using the pooler layers.

## Seven Class Files

* ClimateBERT Political Leaning Classes+T5 Modeling.ipynb: all BERT modeling and text generation modeling, including data transformations
* generated_political_statements.csv: full list of machine-generated texts produced by T5 model; contains 700 sentences total (7 classes, 100 sentences each)
