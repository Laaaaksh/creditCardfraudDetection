# creditCardfraudDetection

A Jupyter notebook that trains a random forest classifier on the classic Kaggle credit card fraud dataset, from mid-2021 (commits 2021-07-14 to 2021-08-11).

## What it is

A single notebook (`creditcardfraud_randomforest.csv.ipynb`) that loads the [Kaggle credit card fraud dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), does basic EDA (class balance, amount distributions, a correlation matrix), splits the data, trains an `sklearn` `RandomForestClassifier`, and reports accuracy/precision/recall plus a confusion matrix. The existing README mentions trying to "develop and deploy" the project, but there is no deployment code (no Flask app, no saved/pickled model, no API) in the repo — it's the training/evaluation notebook only.

## Stack

- Python, Jupyter notebook (built for Google Colab — the notebook expects the CSV to be uploaded there)
- pandas, numpy, matplotlib, seaborn
- scikit-learn (`RandomForestClassifier`, train/test split, classification metrics)

## Running it

Requires downloading `creditcard.csv` from the Kaggle link above (not included in the repo, it's ~150MB) and running the notebook against it, in Colab or locally with the packages above installed. Not executed as part of this review — no dataset file was fetched.

## Status

A learning-exercise notebook from mid-2021 exploring a standard classification benchmark; not maintained, and not a deployed application despite the original description implying one.
