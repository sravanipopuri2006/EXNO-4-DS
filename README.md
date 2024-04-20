# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
```
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.
```
# FEATURE SCALING:
```
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).
```

# FEATURE SELECTION:
```
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method
```

# CODING AND OUTPUT:
![Screenshot 2024-04-20 104028](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/745ef722-cff9-4abb-8b59-8d7834977d8c)
![Screenshot 2024-04-20 104041](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/5ba7278e-c9f5-4851-82e2-ac149ff73ea1)
![Screenshot 2024-04-20 104054](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/e4a0316f-d122-4c21-95dd-9e0476cee968)
![Screenshot 2024-04-20 104104](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/f28bed2b-5c9f-43cc-b36e-a892d8ed9e13)
![Screenshot 2024-04-20 104114](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/505276d9-1af7-404f-9237-eaa18a71b3fe)
![Screenshot 2024-04-20 104131](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/9e9da291-cfbc-48f6-8042-ff9ea1ed6f1a)
![Screenshot 2024-04-20 104149](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/5f3f19b7-fe08-4de0-9138-54efc42ec698)
![Screenshot 2024-04-20 104224](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/ca5a5efa-4e9b-4a90-829b-edbc0adb3046)
![Screenshot 2024-04-20 104234](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/8dec504f-f2e1-47c2-b608-4ab09e910065)
![Screenshot 2024-04-20 104244](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/24ed6437-1d0e-4825-8761-2a86ba22c47f)
![Screenshot 2024-04-20 104252](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/5324e39b-59ef-4793-bcba-db16bc42a2bd)
![Screenshot 2024-04-20 104308](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/ff2e82e5-28b7-4039-893a-92e5d58bc3a1)
![Screenshot 2024-04-20 104324](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/5ab9d580-8504-4ae7-951d-3441d3fc8a75)
![Screenshot 2024-04-20 104348](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/08d01c96-3361-49f2-99e1-065ed8280cad)
![Screenshot 2024-04-20 104448](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/63561369-b4d3-4dc4-bcd5-9e15d7eb2018)
![Screenshot 2024-04-20 104459](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/a0b0c1fc-8a52-4fbf-b4c7-178212e89ece)
![Screenshot 2024-04-20 104459](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/8e1b5ce5-5587-4579-93bf-ffd85a0eef98)
![Screenshot 2024-04-20 104526](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/efc783da-fd06-44a3-a788-c8c6e4f1cd75)
![Screenshot 2024-04-20 104534](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/71410ece-20c5-48c2-b3e6-305c205fb3c6)
![Screenshot 2024-04-20 104616](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/cb8df361-bb4a-4475-81bb-af9eed721a40)
![Screenshot 2024-04-20 104649](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/83b26932-809b-46e4-bc2e-5bb64eea4306)
![Screenshot 2024-04-20 104701](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/4990610c-319f-408b-9706-de6bd36d91ed)
![Screenshot 2024-04-20 104714](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/077d8a1e-d932-46df-8ff3-03a4d597a58a)
![Screenshot 2024-04-20 104732](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/a7ed4066-9bab-4d28-8ce5-63ad3cd8bfb6)











![Screenshot 2024-04-20 104335](https://github.com/sravanipopuri2006/EXNO-4-DS/assets/139778301/1455ab76-e2c2-4ea3-8e86-fff33f53bc5f)














       
# RESULT:
Thus the feature scaling and feature selection is performed for the given data set.

       
