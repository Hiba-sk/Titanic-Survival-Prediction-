# 🚢 Titanic Survival Prediction - Classification Example

##  📖 Project Overview : 
This project predicts passenger survival on the Titanic using supervised
machine learning algorihtms.

## Dataset :
- Titanic Dataset (Kaggle)
- Features include : Passengers, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.

## 🧰 Libraries used :
- Numpy
- Pandas
- Matplotlib & Seaborn
- Tensorflow
- Scikit-learn
- XGBoost
- LightGBM 

## ⚙️ Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training & Evaluation  
5. Model Comparison  

    ### 1. Datacleaning & Preprocessing: 
        Checked for null values filled then with median, and droped non essential column which was cabin.

     ### 2.Exploratory Data Analysis (EDA):
        Cleaned, Processed and Evaulated and Visualized the data using different libraries 
    
    ### 3.Feature Engineering :
        Using StandardScaler, scaled fetaures due to different ranges also useful for discrertization of Sex. Helped in cloosing important features which were later used in Random Forest & XGBoost.

    ### 4.Model Training & Evaluation:
        The dataset was trained on different alogorihtms to calculated precision, recall, f1-score, support,   accuracy for each.

    ### 5.Model Comparison :
        Achieved highest accuray by Random Forest with f1-score accuracy of 82.0 followed by Logistic Regression with 80.0 
        
## 🛠️ Algorithms Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- XGBoost  
- LightGBM

> All listed algorithms are **supervised learning methods**.




