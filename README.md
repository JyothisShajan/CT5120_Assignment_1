Hate Speech Rationale Extraction
This project focuses on detecting hate speech in text and explaining model decisions by extracting specific parts of text—called rationales—that justify hate or offensive labels. It aims to build models that are both accurate and interpretable.

Project Overview
Goal: Beyond classification, extract textual spans that explain why a statement is flagged.

Approach: Use TF-IDF vectorization and interpretable models like Logistic Regression or Random Forests.

Evaluation: Measure rationale extraction quality with token-level Jaccard similarity and classification metrics.

Outcome: Transparent hate speech detection supporting ethical AI principles.

Dataset:			
The datasets (train.csv, dev.csv, and test.csv) are provided separately as a ZIP file in this repository. Download and extract them before running the code.

Getting Started:
Unzip the dataset files to a local directory.
Update file paths in code if necessary to point to extracted CSV files.
Run the training, rationale detection, and evaluation scripts as needed.

Requirements:
	Python 3.x
	scikit-learn, pandas, numpy, requests (for downloading data if needed)

Install dependencies with:

	pip install -r requirements.txt

Usage:
Examples for training the rationale model, detecting rationales on test data, and evaluating them are included in Jupyter notebooks and Python scripts.
