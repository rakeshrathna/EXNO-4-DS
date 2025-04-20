# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Ds exp 4 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/c316a149-7caa-47f9-9237-c11b2a0aee7d)
![Ds exp 4 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/ccddaba5-a96d-41f8-b37a-4ee37ccf0870)
![Ds exp 4 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/1f5f815d-e393-4dd5-b3d0-b09c8575d4ad)
![Ds exp 4 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/d7eda482-3a2c-4c08-88f1-25dc1054387d)
![Ds exp 4 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/41892467-f593-4043-858b-ead8b3d0d190)
![Ds exp 4 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/fd6150d9-20d1-4065-ab9e-28ba81a7c79f)

       
# RESULT:
Thus we have read and performed  Feature Scaling and Feature Selection process.


