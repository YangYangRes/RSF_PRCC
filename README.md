# TCGA_KIRP
##Summary
We constructed a prognostic model using machine learning algorithms based on the expression levels of nine genes to predict the prognosis of papillary renal cell carcinoma patients.
##Dependencies
```python
Python 3.9+
pip install pandas
pip install numpy
pip install scikit-survival
```
##Usage
To obtain the expression levels of nine specific genes from the patients, Log2(TPM+1) normalization was applied, and the data was formatted as sample.csv file. By replacing the sample.csv file in model.ipynb and running the code, the prediction results can be obtained.
