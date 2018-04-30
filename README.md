# support-vector-machine-python

# Dataset used:  
Breast Cancer Dataset built-in sklearn library

# Objective:   
To build a system that can predict whether a female has breast cancer or not.

# Features/Variables:  
__* 'mean radius',
__* 'mean texture',
__* 'mean perimeter',
__* 'mean area',
__* 'mean smoothness',
__* 'mean compactness',
__* 'mean concavity',
__* 'mean concave points',
__* 'mean symmetry',
__* 'mean fractal dimension',
__* 'radius error',
__* 'texture error',
__* 'perimeter error',
__* 'area error',
__* 'smoothness error',
__* 'compactness error',
__* 'concavity error',
__* 'concave points error',
__* 'symmetry error',
__* 'fractal dimension error',
__* 'worst radius',
__* 'worst texture',
__* 'worst perimeter',
__* 'worst area',
__* 'worst smoothness',
__* 'worst compactness',
__* 'worst concavity',
__* 'worst concave points',
__* 'worst symmetry',
__* 'worst fractal dimension'

# Method: 

1. Raw SVM
2. Fine tuned SVM using C and Gamma(Ref: SVM notebook)

# Result:
1. Raw SVM

             precision    recall  f1-score   support

          0       0.00      0.00      0.00        63
          1       0.63      1.00      0.77       108

avg / total       0.40      0.63      0.49       171  
  
2. Tuned model
precision    recall  f1-score   support

          0       0.97      0.94      0.95        63
          1       0.96      0.98      0.97       108

avg / total       0.96      0.96      0.96       171


