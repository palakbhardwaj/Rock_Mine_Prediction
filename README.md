# Rock_Mine_Prediction
# Rock vs Mine Prediction

This repository contains data and code for predicting whether a given sample is a rock or a mine. The dataset includes various features extracted from sonar signals, 
and the target is to classify each sample as either a rock (R) or a mine (M).

## Dataset

The dataset consists of samples with 60 features each, followed by the target label (R for Rock, M for Mine). Here’s a snippet of the dataset:


0	1	2	......................... 59	60
0	0.0200	0.0371	0.0428	...	0.0032	R
1	0.0453	0.0523	0.0843	...	0.0044	R
2	0.0262	0.0582	0.1099	...	0.0078	R
3	0.0100	0.0171	0.0623	...	0.0117	R
4	0.0762	0.0666	0.0481	...	0.0094	M


## Model

A logistic regression model is used for classification. Below are the details on how to train and evaluate the model using Python and the `scikit-learn` library.

### Requirements

- Python 3.x
- `numpy`
- `pandas`
- `scikit-learn`

### Installation

You can install the required packages using `pip`:

```bash
pip install numpy pandas scikit-learn
Results
The model achieves an accuracy of approximately 76% on the test set. (Replace XX with the actual accuracy obtained from running the code.)

