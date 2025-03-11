# 🚀 Employee Retention Prediction - Salifort Motors  
**Google Advanced Data Analytics Capstone Project**  

## 📌 Project Overview  
This project is part of my **Google Advanced Data Analytics Certificate** program.  
The objective is to analyze **employee retention** at Salifort Motors using **machine learning** and **data analytics techniques**.  

## 🎯 Problem Statement  
Salifort Motors, an **alternative energy vehicle manufacturer**, is experiencing **high employee turnover**.  
The company wants to understand the **key factors behind employee attrition** and **develop data-driven strategies** to retain talent.  

## 📊 Dataset  
The dataset consists of **employee survey data**, including:  
- **Satisfaction Level**  
- **Last Performance Evaluation Score**  
- **Number of Projects**  
- **Average Monthly Hours Worked**  
- **Years at the Company**  
- **Work Accidents & Promotions**  
- **Department & Salary Level**  
- **Attrition Status (Left the company: Yes/No)**  

## 🔍 Key Insights  
- **Number of projects** is the strongest predictor of whether an employee stays or leaves.  
- **Overworking (high monthly hours)** is **strongly correlated with employee attrition**.  
- **No significant correlation between department and attrition.**  
- **Low satisfaction scores are associated with higher employee churn.**  

## ⚙️ Machine Learning Models  
The following models were tested:  
✔ **Decision Tree (Champion Model)** - Best performance  
✔ **Random Forest**  
✔ **XGBoost** (Planned for future improvement)  

### **Champion Model (Decision Tree) Results:**  
| Metric           | Score   |
|-----------------|---------|
| **Precision**   | 96.23%  |
| **Recall**      | 93.09%  |
| **F1-Score**    | 94.63%  |
| **Accuracy**    | 97.48%  |
| **AUC Score**   | 98.11%  |

## 📌 Next Steps  
- **Fine-tune hyperparameters** for model optimization.  
- **Implement Random Forest & XGBoost** to compare results.  
- **Provide business recommendations** based on insights.  

## 🛠️ Installation & Setup  
To run this project locally:  
1. Clone the repository:  
   ```bash
   git clone https://github.com/watashiaashishgurung/Salifort-motors-capstone-project.git
   cd employee-retention
```
2. Install dependencies
    ```bash
    pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook 

    ```bash
    jupyter notebook 
    ```
4. Open Salifort_Motors_Capstone.ipynb
    
