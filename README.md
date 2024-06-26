# Heart-Diseases-Prediction
Heart Disease Prediction using Logistic Regression model
### Problem:
According to the World Health Organization, heart diseases are responsible for approximately 12 million deaths globally each year. In the United States and other developed nations, cardiovascular diseases account for half of these fatalities. Early detection of cardiovascular diseases can facilitate crucial lifestyle adjustments for high-risk patients, ultimately reducing the likelihood of severe complications. This research aims to identify the most significant risk factors for heart disease and predict overall risk using a logistic regression model.

### Solution:
The objective is to forecast whether a patient has a 10-year risk of developing coronary heart disease (CHD).

To achieve this, I have implemented a Logistic Regression Model to predict Coronary Heart Disease.

#### What is Logistic Regression?

Logistic Regression is a powerful statistical and machine-learning technique used to classify records within a dataset based on input field values. It predicts a dependent variable by analyzing one or more sets of independent variables. Logistic Regression is suitable for both binary and multi-class classification tasks.

### Data Information:
The dataset, available on the Kaggle website, originates from an ongoing cardiovascular study in Framingham, Massachusetts. It comprises over 4,000 records and 15 attributes, detailing comprehensive patient information.

The dataset is preloaded in the repository ([here](https://drive.google.com/file/d/1cl7M5T1tMvXdb10YuDedXlxvCIbcKGrH/view?usp=sharing)).

The Framingham Heart Study dataset encompasses several demographic risk factors:

- **sex:** male or female
- **age:** age of the patient
- **education:** levels categorized as 1 for some high school, 2 for a high school diploma or GED, 3 for some college or vocational school, and 4 for a college degree.

Additionally, the dataset includes behavioral risk factors related to smoking:

- **currentSmoker:** whether or not the patient is a current smoker
- **cigsPerDay:** the average number of cigarettes smoked per day.

Medical history risk factors include:

- **BPMeds:** whether or not the patient is on blood pressure medication
- **prevalentStroke:** whether or not the patient has previously suffered a stroke
- **prevalentHyp:** whether or not the patient is hypertensive
- **diabetes:** whether or not the patient has diabetes

Risk factors derived from the initial physical examination of the patient:

- **totChol:** total cholesterol level
- **sysBP:** systolic blood pressure
- **diaBP:** diastolic blood pressure
- **BMI:** Body Mass Index
- **heartRate:** heart rate
- **glucose:** glucose level
- **TenYearCHD:** 10-year risk of coronary heart disease (TARGET VARIABLE)

### Libraries Used:
- Pandas (for data manipulation and analysis)
- Matplotlib (for creating static, animated, and interactive visualizations)
- Seaborn (for statistical data visualization)
- Scikit-Learn (for data modeling and machine learning)

### Contents:
1. **Importing the required libraries**
2. **Loading and examining the dataset**
3. **Conducting Exploratory Data Analysis (EDA)**
4. **Data Preprocessing**
5. **Visualizing the data**
    - Generating a Correlation Matrix
    - Creating Pairplots
    - Plotting Countplots
6. **Building the Model**
    - Separating features and target variable
    - Splitting the data into training and testing sets
    - Training the model
    - Making predictions
    - Evaluating prediction scores
    - Assessing model accuracy
    - Generating a Classification Report
    - Creating a Confusion Matrix
    - Plotting the confusion matrix
