# Machine-Learning-for-Disease-Treatment-Response-Prediction
# Background
Breast cancer is the most common cancer in the UK for women. Chemotherapy
is a commonly used treatment strategy to reduce the size of locally advanced
tumour before surgery. However, chemotherapy is a toxic process to human
body and it is not aways effective to everyone. Complete tumour resolution at
surgery, known as pathological complete response (PCR), has a high
likelihood of achieving cure and longer relapse-free survival (RFS) time. RFS
is the length of time after primary treatment for a cancer ends that the patient
survives without any signs or symptoms of that cancer. However, only 25% of
patients receiving chemotherapy will achieve a PCR, with the remaining 75%
having residual disease and a range of prognosis. Better patient stratification
and treatment could be achieved if PCR and RFS could be predicted using
information prior to chemotherapy treatment.

# Aim
To use advanced machine learning method to predict PCR
(classification) and RFS (regression) using both clinically measured features
and features derived from magnetic resonance images (MRI) prior to
chemotherapy treatment.

# Data
Based on the public dataset from The American College of Radiology Imaging
Network (I-SPY 2 TRIAL), a simplified dataset is generated for this assignment.
Each patient in this dataset contains 10 clinical features (Age, ER, PgG, HER2,
TrippleNegative Status, Chemotherapy Grade, Tumour Proliferation, Histology 2
Type, Lymph node Status and Tumour Stage) and 107 MRI-based features.
The image-based features were extracted from the tumour region of MRIs using
a radiomics feature extraction package (known as Pyradiomics:
https://pyradiomics.readthedocs.io/en/latest/ ). You do not need to understand
the meaning of these clinical feature and image-based features to complete this
assignment but worth reading background information on the I-SPY 2 Trial
website. “999” in the spreadsheet means a missing data value. A training
dataset (trainDataset.xls) is provided and available on Moodle that contains
400 patients. A test dataset that contains N patients is reserved (hidden from
you) for final performance evaluation. You can assume that the test set and
training set are sampled from the same data distribution, but the ratio of PCR
positive and negative could be different.
