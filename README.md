
# This is a Kaggle competition - [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic)

A group project of comp4433, Data Mining


<h1 b>Dataset:</h1 b>

| No.| File Name                | FilePath    | description                     |
|----|--------------------------|-------------|---------------------------------|
| 1  |  spaceship_train.csv     |   `spaceship-titanic_rawData\spaceship_train.csv` |   Original Training             |
| 2  |  spaceship_test.csv      |   `spaceship-titanic_rawData\spaceship_test.csv`  |   Using for prediction          |
| 3  |  splittedData_01.csv     |   `preprocess_dataset\splittedData_01.csv`        |   -  Splitted the Cabin & Name into multi-columns <br> -  filled-in the NaN data |
| 4  |  encodedData_01.csv      |   `preprocess_dataset\encodedData_01.csv`         |   -  Apply one-hot encoding to the categorical variables and label encoding to the First_Name, Last_Name. <br><br>-  Adjust the dataset to be easier for constructing models <br> - filled-in the NaN data                                   |
| 5  |  normalizedData_01.csv   |   `preprocess_dataset\normalizedData_01.csv`      |   - normalized the numeric data <br>  - filled-in the NaN data
| 6  |  rmNaNDate_01.csv        |   `preprocess_dataset\rmNaNDate_01.csv`           |   -   remove the numeric NaN data (remaining null columns: HomePlanet, Cabin, Destination & Name. can drop them) |


<br>
<h1 b>Prediction scorces:</h1 b>

| No.| Classifer Model          |               FilePath                                | Score |   description   |
|----|--------------------------|-------------------------------------------------------|-------|-----------------|
| 1. | Decision Tree            | `classifers\decisionTree\DT_01.ipynb`                 |0.77484|                 |
| 2. | Logistic Regression      | `classifers\logisticRegression\LogisticReg_01.ipynb`  |0.77811|                 |
| 3. | KNN                      | `classifers\kNN\Assignment 5KNN.ipynb`                |0.75964|                 |
| 4. | RandomForest             | `classifers/RandomForest/randomForest.ipynb`          |0.79354|                 |
| 5. | SVM                      | `classifers/svm/svm.ipynb`                            |0.78021|                 |
| 6. |                          |                                                       |       |                 |
| 7. |                          |                                                       |       |                 |
|    |                          |                                                       |       |                 |
|    |                          |                                                       |       |                 |

