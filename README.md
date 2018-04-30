# support-vector-machine-python

# Dataset used:  
Breast Cancer Dataset built-in sklearn library

# Objective:   
To build a system that can predict whether a female has breast cancer or not.

# Features/Variables:  
__* 'mean radius',
+ 'mean texture',
+ 'mean perimeter',
+ 'mean area',
+ 'mean smoothness',
+ 'mean compactness',
+ 'mean concavity',
+ 'mean concave points',
+ 'mean symmetry',
+ 'mean fractal dimension',
+ 'radius error',
+ 'texture error',
+ 'perimeter error',
+ 'area error',
+ 'smoothness error',
+ 'compactness error',
+ 'concavity error',
+ 'concave points error',
+ 'symmetry error',
+ 'fractal dimension error',
+ 'worst radius',
+ 'worst texture',
+ 'worst perimeter',
+ 'worst area',
+ 'worst smoothness',
+ 'worst compactness',
+ 'worst concavity',
+ 'worst concave points',
+ 'worst symmetry',
+ 'worst fractal dimension'

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


​