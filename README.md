# BIU-Data-Science-Workshop

Dear tester,
This is our project for the data science workshop cours.
That README file is designed to make it easier for the tester to test our model and project in general.

All the trained weights of our network and the data needed for training and testing the model can be automatically downloaded by pre-written commands (using gdown).
Training the model requires very strong processing power and takes a lot of time, so we recommend using the "EDA_Training" notebook for reference only. All outputs are there of course.
We created another notebook that is intended for testing the model only and which we recommend running (Testing.ipynb).
The Testing.ipynb notebook makes use of a test set (which the model did not see in the Train phase of course).  downloaded by gdown 
The test set will be automatically downloaded by gdown when clicking "Run All".

<b>It should be noted that we have invested time in writing a detailed report that explains our workflow and the thinking behind the implementation of the project in general, we would be glad if you will read it while going through our notebook.</b>


## This repository contains the following files:
- requirements.txt
- Crimes_in_Chicago_EDA_Training.ipynb
- Testing.ipynb
- ds_worshop_report.pdf

## Installation and dependencies
1. Clone the repository
2. Create a new python environment
3. run: pip install -r requirements.txt in your shell

## Train Model (Not recommended - takes a long time)
1. Enter to "Crimes_in_Chicago_EDA_Training.ipynb"
2. Run All Cells

## Test Trained Model
1. Enter to "Testing.ipynb"
2. Run All Cells
