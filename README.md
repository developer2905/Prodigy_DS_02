# Prodigy_DS_02

Welcome to the Titanic Survival Analysis project! This project was done under prodigy infotech. This project provides an exploratory data analysis (EDA) of the Titanic dataset using Python. The goal is to gain insights into the factors that influenced survival rates during the tragic sinking of the Titanic. Below, we provide a detailed overview of the code and its components. 🌊🔍

## Overview
The project consists of three main datasets: train.csv, test.csv, and gender_submission.csv. The train.csv dataset is used to train the model and perform the EDA, while the test.csv dataset is used to test the model's performance. The gender_submission.csv file provides a sample submission format.

Dataset Example:  https://www.kaggle.com/c/titanic/data

## Exploratory Data Analysis (EDA) 📊
### 1. Data Loading and Basic Information 📥
First, we load the datasets using pandas and display basic information, such as the data types and summary statistics. This helps us understand the structure and contents of the datasets.
![pic1](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/a8dabc6d-9767-4e87-890e-0f7ff87606f8)
![pic2](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/1761053a-648b-4b72-8f02-960dbb77905b)
![pic3](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/a819601c-48f6-435d-9e84-493f3720ce52)
![pic4](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/e35b6b25-b354-42be-b17e-2b422dd490ee)
![pic5](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/3f0880d2-0262-42e9-b73c-5b2b76625c9e)
![pic6](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/905b4443-52e2-4f8f-9592-c4e923820bc2)
![pic7](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/8b1e49af-9887-4663-9967-b8686ec40885)
![pic8](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/615e005f-0747-417e-847a-89e13fcb59fe)
### 2. Data Inspection and Missing Values 🔍
We inspect the first few rows of each dataset and check for missing values. This step is crucial for data cleaning and preprocessing.
![pic9](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/a2d6fa08-0fe6-49ed-b9ff-7172830ec9b1)
![pic10](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/4fb9f677-cccb-4ac1-ab66-5b80ccd0d460)
![pic11](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/0c90969b-b0f1-4546-9c94-1a98932de544)
![pic12](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/81e9ce89-d09e-44bc-acd4-9dbaa02f2db5)
![pic13](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/4cbba100-c8c1-4199-a56f-797080314fc0)
![pic14](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/f37c03c2-a2cb-4e00-8d5b-9e29c94548b3)
![pic15](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/daf2e98c-603d-4d17-b79c-761d7806f85d)
![pic16](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/f7d4c6f5-0c61-4d05-afed-3e3b8c07f22e)
![pic17](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/eef10822-20f2-4604-a5ae-572de36e7a72)

### Making the Report
![pic18](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/ea63cdfa-f808-457b-8581-e3a9ee0df457)
![pic19](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/77ad18a3-c363-4cd6-a3a7-73454f9fca92)
![pic20](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/6a253f9c-463f-4d1d-b6ba-9a4e6f406983)
![pic21](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/5ba4a110-0553-468c-bc87-2d73e944d1ef)
![pic22](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/22f8cc82-e58e-4c41-a6f8-0924affbd4c3)

### 3. Visualizations and Insights 📈
We use Seaborn and Matplotlib to create various visualizations to uncover patterns and relationships in the data. The visualizations include:

- Age Distribution: A histogram to visualize the distribution of passengers' ages.
![pic23](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/c75f8245-e7ef-474c-8bc4-39bf4d1df1fa)
![pic24](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/63f03fb4-a82f-4f69-957d-ed443bbc29fb)

- Survival Count: A count plot showing the number of survivors and non-survivors.
![pic25](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/ea9d01a9-7eec-483d-96a7-6906647b82d8)
![pic26](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/06eaa072-fbed-4e2b-8fe3-bc425cfe7b82)

- Passenger Class vs. Survival: A count plot showing survival rates by passenger class.
![pic27](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/7147dd26-2b2c-4787-9b91-8f5fb5b21178)
![pic28](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/1954f0f3-f06b-4146-9e6c-8fa530d1ef89)

- Sex vs. Survival: A count plot showing survival rates by gender.
![pic29](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/6cc0852a-8c90-430f-9bc9-44c389246d1c)
![pic30](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/da238270-e55b-4051-8511-0917a19d2fa9)

- Fare Distribution: A histogram to visualize the distribution of fares paid by passengers.
![pic31](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/0038e3a2-812b-467e-85d9-92050d2c08f9)
![pic32](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/01075a1a-328b-453c-a342-70e85d304ca1)

- Age vs. Passenger Class: A box plot to show the age distribution across different passenger classes.
![pic33](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/d30afdb5-d149-4c88-93a3-b6ce2e488e44)
![pic34](https://github.com/developer2905/Prodigy_DS_02/assets/168186520/e4c09143-e01e-4071-b2b1-484d310ca56b)


## Conclusion 🎬
This project provides a detailed exploratory analysis of the Titanic dataset, showcasing the power of data visualization and statistical analysis in uncovering meaningful insights. We hope you find this project informative and inspiring for your data science journey! 🚀

This work was completed under the guidance and support of Prodigy Infotech. Feel free to explore, fork, and contribute to this project. Let's dive into the data and uncover the stories it holds! 🌊📈



