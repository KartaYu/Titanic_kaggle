# Titanic | kaggle
### Basic Package (基本套件)
* Pandas
* numpy
* matplotlib
* scikit-learn
* xgboost
### Data Analysis (資料分析)
1. The relationship between gender and survival rate
   * We can see that males have lower survival rate and females have the opposite.
   ![image](https://github.com/KartaYu/Titanic_kaggle/blob/main/Data%20Visualization/gender%20and%20survival%20rate.png)
2. The relationship between class and survival rate
   * We can see that the higher rank of class have the higher survival rate.
   ![image](https://github.com/KartaYu/Titanic_kaggle/blob/main/Data%20Visualization/plcass%20and%20survival%20rate.png)
3. The relationship between cabin , fare and survival rate
   * the survived passengers have Higher fare especially in plcass1 and plcass2.
   ![image](https://github.com/KartaYu/Titanic_kaggle/blob/main/Data%20Visualization/fare%20and%20survival%20rate.png)
4. The relationship between age distribution and survival rate in p class1 and pclass2
   * we can find that the part of people is younger than 16 years old, most of them survived, and the death rate at 40 years old is higher than that of those who survived.
   
   ![image](https://github.com/KartaYu/Titanic_kaggle/blob/main/Data%20Visualization/plcass%20age%20survival%20rate.png)
 
### Data processing (資料處理)
1. Fill missing data of the age
2. Fill missing data of the fare
3. Discrete data

### Moedl selection (模型選擇)
1. Random Forset
    * In this case, wa have a lot of missing data, It has an effective method for estimating missing data and maintains accuracy when large proportion of the data are missing.
2. XGBoost
    * It is designed to handle missing data with its in-build features.

### Result (結果)
1. Random Forset
![image](https://github.com/KartaYu/Titanic_kaggle/blob/main/Data%20Visualization/random%20forest.png)
2. XGBoost
![image](https://github.com/KartaYu/Titanic_kaggle/blob/main/Data%20Visualization/xgboost.png)
