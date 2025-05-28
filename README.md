# Credit Risk Prediction App

A machine learning-based application developed to help financial institutions predict the credit risk of loan applicants. This project was created as part of a university assignment for Data Mining.

## 👥 Team Members

- M. Ali Imron Almuzaky (1202223312)  
- Muhammad Handra Haq (1202223014)  
- Rayhan Mulia Pratama (1202223240)  
- Arya Nugraha (1202220125)

## 📚 Background

Credit risk management is a critical aspect of financial institutions, particularly banks and lending entities. Credit risk refers to the potential for a borrower to default on loan obligations. This project implements a credit risk prediction model using machine learning to support better decision-making in loan approvals.

## 🔍 Project Objectives

- To predict loan applicant risk levels (High/Low)
- To minimize the likelihood of bad loans
- To assist financial decision-making using data

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-Learn
- Google Colab
- Google Drive (as data source)

## 📊 Dataset

The dataset is imported from Google Drive and contains:
- Applicant income
- Credit score
- Loan amount
- Employment status
- Other related features

Sample code to load dataset:
```python
import pandas as pd
url = 'https://drive.google.com/uc?export=download&id=1gqvlP-GwSg1rXht4NW5KMRBkcMZ9XcpH'
df = pd.read_csv(url)
df.head()
