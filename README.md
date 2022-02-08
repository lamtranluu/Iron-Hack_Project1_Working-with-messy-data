# <p align='center'> Iron-Hack_Project1_Working-with-messy-data 📃
## Project 1: Working with messy data (string &amp; numeric format)
by Team Obelix <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">: Lam Luu, [Josep Trota] & [Angela Wang](https://github.com/newgala), January 2022

🔎 **Identify 2 main objectives:**
1. **Which location has more job opening for Data Science roles ?**
2. **Which kind of skills, talent for Data Science roles ?**

![alt text](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/Images/DjeaDGAWsAEkdPD.jpeg)
  
***
* [Contribution guidelines for this project](https://github.com/student-IH-labs-and-stuff/BCNDATA0122/blob/main/Projects/Messy_data/Messy_Data.md)

The data source  was used from [Kaggle Pages](https://www.kaggle.com/sl6149/data-scientist-job-market-in-the-us?select=alldata.csv/), Job posts from Indeed around August, 2018

## 📋 Table of Content:
* [Challenges](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/README.md#challenges) 
* [Tools & Process](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/README.md#tools-process)
* [Data Insight](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/README.md#data-insight) 
* [Key Take Away](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/README.md#key-take-away) 

## Challenges <img src="https://media.giphy.com/media/TGR2xO6HopOhraWYDo/giphy.gif" width="80px">
* Use the given data set that contains over 6900 job posts from Indeed forr Data Science roles in US market, August 2018  <img src=https://img.shields.io/badge/file%20size-26.9%20Mb-lightgrey>
* Analyse & identify the most frequent keywords from job descriptions, job positions to answer 2 main objectives above
## Tools & Process
 ![](https://img.shields.io/badge/Tableau-Visualisation-informational?style=flat&logo=tableau&logoColor=white&color=2bbc8a)
 ![](https://img.shields.io/badge/Python-JupyterNotebook-informational?style=flat&logo=python&logoColor=white&color=2bbc8a)
1. Notebook: Read the csv file with pandas
2. Data cleaning & wrangling in Python: 
  - Split string from column[location] to obtain information of states and cities in each job posts
  - Standardzie all uper case letters to lower case letters
  - Remove all special characters
4. Analyse & identify the frequent keywords>
  - Use Python function (for_loop) to count the frequency of relevant keywords and extract to csv file to execute visualisation
5. Visualisation:
  - Import all csv file and visualize the data to answer 2 main objectives
## Data Insight
![state](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/Images/Screenshot%202022-02-08%20at%2023.18.55.png)
![city](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/Images/Screenshot%202022-02-08%20at%2023.19.03.png)
![skill](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/Images/Screenshot%202022-02-08%20at%2023.21.02.png)
![roles](https://github.com/lamtranluu/Iron-Hack_Project1_Working-with-messy-data/blob/main/Images/Screenshot%202022-02-08%20at%2023.21.20.png)
