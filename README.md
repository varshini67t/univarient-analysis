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

# RESULT
Thus, we have analyzed the vvariables of the dataset using univariate analysis
