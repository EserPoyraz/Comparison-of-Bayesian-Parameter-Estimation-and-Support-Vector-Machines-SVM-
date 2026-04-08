# Comparison-of-Bayesian-Parameter-Estimation-and-Support-Vector-Machines-SVM-
The primary objective of this project is to evaluate and compare the performance of classical statistical pattern recognition methods with modern machine learning approaches in medical diagnostics, specifically targeting multi-class fetal health classification.
Within the scope of this study, a classical parametric method, Bayesian
Decision Theory (implemented with Maximum Likelihood Estimation), and a
current "State-of-the-Art" (SOTA) classifier, Support Vector Machines (SVM), will
be trained and comparatively analyzed.

The project methodology consists of the following stages:

Data Acquisition and Exploration: Obtaining the fetal health dataset,
handling missing values, and testing statistical distributions of continuous
sensor data to verify the Gaussian assumption.

Classical Method Implementation: Estimating the parameters (μ and σ^2)of
the class-conditional probability density functions for three distinct classes from
the training data using the Maximum Likelihood Estimation (MLE) framework.

State-of-the-Art Method Implementation: Training the SVM model utilizing
a Radial Basis Function (RBF) kernel and a One-vs-Rest (OvR) strategy to
effectively capture the non-linear features of the multi-class dataset, followed
by hyperparameter optimization.

Comparative Evaluation: Objectively comparing the trained models utilizing K-Fold
Cross Validation across multiple metrics, specifically focusing on Macro-Averaged
Accuracy, Precision, Recall, and F1-Score to account for class imbalance.
