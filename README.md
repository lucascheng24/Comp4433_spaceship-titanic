
# This is a Kaggle competition - [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic)

A group project of comp4433, Data Mining


Dataset:
| No.| File Name                | FilePath                                          | description                     |
|----|--------------------------|---------------------------------------------------|---------------------------------|
| 1  |  spaceship_train.csv     |   `spaceship-titanic_rawData\spaceship_train.csv` |   Original Training             |
| 2  |  spaceship_test.csv      |   `spaceship-titanic_rawData\spaceship_test.csv`  |   Using for prediction          |
| 3  |  splittedData_01.csv     |   `preprocess_dataset\splittedData_01.csv`        |   -  Splitted the Cabin & Name into multi-columns <br> -  filled-in the NaN data |
| 4  |  encodedData_01.csv      |   `preprocess_dataset\encodedData_01.csv`         |   -  Apply one-hot encoding to the categorical variables and label encoding to the First_Name, Last_Name. <br><br>-  Adjust the dataset to be easier for constructing models <br> - filled-in the NaN data                                   |
| 5  |  normalizedData_01.csv   |   `preprocess_dataset\normalizedData_01.csv`      |   - normalized the numeric data <br>  - filled-in the NaN data
| 6  |  rmNaNDate_01.csv        |   `preprocess_dataset\rmNaNDate_01.csv`           |   -   remove the numeric NaN data (remaining null columns: HomePlanet, Cabin, Destination & Name. can drop them)
