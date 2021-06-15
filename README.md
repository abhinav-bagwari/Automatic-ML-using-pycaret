# Automatic-ML-using-pycaret

PyCaret is a deployment ready Python library which means that as you perform an experiment, all steps are automatically saved in a pipeline which can be deployed into production with ease. PyCaret automatically orchestrates all dependencies in a pipeline. Once a pipeline is developed, it can be transferred to another environment to run at scale. All preprocessing and the data preparation tasks are part of a pipeline in PyCaret 

# Content

All attributes except Category and Sex are numerical.
Attributes 1 to 4 refer to the data of the patient:
1) X (Patient ID/No.)
2) Category (diagnosis) (values: '0=Blood Donor', '0s=suspect Blood Donor', '1=Hepatitis', '2=Fibrosis', '3=Cirrhosis')
3) Age (in years)
4) Sex (f,m)
Attributes 5 to 14 refer to laboratory data:
5) ALB
6) ALP
7) ALT
8) AST
9) BIL
10) CHE
11) CHOL
12) CREA
13) GGT
14) PROT

The target attribute for classification is Category (2): blood donors vs. Hepatitis C patients (including its progress ('just' Hepatitis C, Fibrosis, Cirrhosis).
