# univarient-analysis
# AIM

To read the given data and perform analysis by statistical study of data which describes the pattern of response to the variable.

# ALGORITHM

STEP 1 Read the given Data

STEP 2 Get the information about the data

STEP 3 count the values

STEP 4 Analyse count plot

STEP 5 Analyse Box plot

STEP 6 Analyse Hist plot

# CODE
#get the data
data = pd.read_csv('/content/gdrive/MyDrive/diabetes.csv')
data.head(10)

data.info()

data['Age'].value_counts()

sns.boxplot(x="BMI",data=data)

sns.countplot(x="BMI",data=data)

sns.displot(data["BMI"])

sns.histplot(x="BMI",data=data)

# SUPERSTORES

#get the data
data = pd.read_csv('/content/gdrive/MyDrive/SuperStore.csv')
data.head(10)

data.info()

data['Sales'].value_counts()

sns.boxplot(x="Sales",data=data)

sns.countplot(x="Sales",data=data)

sns.displot(data["Sales"])

sns.histplot(x="Sales",data=data)

# OUTPUT
![image](https://user-images.githubusercontent.com/107982953/235744806-f54c6626-bdb8-4272-b4c9-9fb404c66c19.png)
![image](https://user-images.githubusercontent.com/107982953/235744887-dab58652-4807-4c5c-b30a-087c83cfb3d3.png)
![image](https://user-images.githubusercontent.com/107982953/235744982-d3e6478a-2383-41a4-b668-ebb52d84ec9c.png)
![image](https://user-images.githubusercontent.com/107982953/235745034-c5903fa0-5d7a-42bc-bd35-8d0e32a2da5f.png)
![image](https://user-images.githubusercontent.com/107982953/235745110-7919f7c2-3a70-48a7-b123-9eac886eba76.png)
![image](https://user-images.githubusercontent.com/107982953/235745163-ca01403a-13d0-4838-b135-7c7ea68ce55f.png)
![image](https://user-images.githubusercontent.com/107982953/235745243-cc55116e-982b-4e2d-a490-46abb8aaea25.png)
![image](https://user-images.githubusercontent.com/107982953/235745296-9f4e57c4-72bd-4e55-ad40-cf28fc19dd17.png)
![image](https://user-images.githubusercontent.com/107982953/235745361-26a21f37-e899-424c-a22f-c38e8177a48a.png)
![image](https://user-images.githubusercontent.com/107982953/235745425-ec64876f-9c4a-42db-8ed0-d5d26d94bb81.png)
![image](https://user-images.githubusercontent.com/107982953/235745487-73db5ec1-ac5e-46a6-b0c3-32a40da64f6c.png)
![image](https://user-images.githubusercontent.com/107982953/235745546-255990d5-79c5-4fca-b3cd-8998fdfb8f9d.png)

# RESULT
Thus, we have analyzed the vvariables of the dataset using univariate analysis
