# Machine Learning II - Exam-Project

## Motivation
### Problem
In my company I have to process a lot of receipts. I get them in  pdf-, jpeg- and png-format and I need to rename them in the following pattern: "yyyy-mm-dd <commpany-name>". To do so, I have to open all the receipts and search for the date and the company-name, which takes a lot of time and errors could occure if this has been done manually.

### Goal
I'd like to create a program that opens the documents and finds the date and the company-name and saves the file with the correct pattern. The file should then be stored in a MongoDB.

### Addition
I'd like to create a frontend, where people can upload the receipts, so they will be stored in the database with the relevant information. The webapp should show the analysed results, to ask the people if the analyzed date and company-name are correct, so they can answer "yes" or "no". If they answer "no", they should have the possibility to enter the correct name.


## Data Collection
I use the following data:
- my own receipts
- receipts from different Kaggle-Datasets
- synthetically generated
- collected via webapp from users


## Effort
The Kaggle-Dataset needed to be flatten, because there were many subfolders.
