# Text Analytics

Text classification workflow for structured NLP experiments with train/eval splits and model comparison.

## Problem

Classify unstructured text into predefined categories with a reproducible baseline pipeline.

## Approach

`Classification_v1.ipynb` covers:

- Text cleaning and tokenization
- Feature extraction (bag-of-words or embeddings)
- Classifier training and validation metrics

## Reproducibility

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Tech stack

Python 3, Jupyter, scikit-learn, pandas

## Limitations and next steps

- Export trained model with joblib for batch inference
- Add cross-validation and confusion matrix reporting
- Split notebook into `src/` modules and a thin orchestration notebook
