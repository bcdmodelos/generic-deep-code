## Deep Learning for Kernel Selection in Gaussian Process Regression

### Kernel-possibilities code
* Data Reading:  loads a time series from a CSV file.
* Kernel Combinations: generates combinations of Gaussian kernels using sum and multiplication operations.
* Validation: checks if the resulting combinations produce positive definite covariance matrices.
* Save: saves the valid combinations in a CSV file.

### Kernel-library code
* Data Reading: loads and prepares the time series.
* Function Definition:  defines functions to evaluate kernels and calculate performance metrics.
* Reading Kernels: loads possible combinations of kernels from a CSV file.
* Batch Processing: evaluates kernels in batches.
* Evaluate and Save: evaluates each kernel, calculates performance metrics, and saves the results in a CSV file.

### model-deep-kernel code
* Data Reading: data is loaded and prepared for model training.
* Model Building and Training: a deep learning model is used for predicting the R²teste metric.
* Evaluation and Prediction: the model is evaluated, and predictions are made for all the data.
* Identification of the Best Kernel: the best kernel is identified and printed.