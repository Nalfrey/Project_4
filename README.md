## Project 4 Stock Market Predicting

Final project for OSU Data Analystics Bootcamp to utilize machine learning (ML) to learn stock market buying and selling effiency.


## Requirements

Google Colab
https://colab.research.google.com/

Google Authenticator
Android: 
https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en_US&pli=1
IOS:
https://apps.apple.com/us/app/google-authenticator/id388497605

Alpaca account
https://app.alpaca.markets/paper/dashboard/overview

Alpaca API keys
https://app.alpaca.markets/user/profile#manage-accounts
Scroll to the bottom of the page to get to the "Paper Account"

## Goal
Create a ML tool to give at least 75% accuracy or .8 r-squared value.
Use tool to make money

## Overview
Trying to predict the stock market based on Vangaurd "VOO" stock
Determining if the market will be bearish or bullish based on the moving average (MA) of 50 days and 200 days
Running from January 1st 2021 to February 1st 2025
Avoiding 2020 and earlier due to Covid-19 bias

## Models Used
Clustering
Random Forest
Support Vector Machine (SVM)

## Results
Logistic Regression: model attempted, but given labels beforehand so ML was incorrectly used.
Clustering: looked at the data on a day over day basis, thus not predicting a bear or bull market
Random Forest Classifer: Randomized the dates, rather than using them in order, thus creating an error based on datetime
SVM: Accuracy was always showing at 1 or 100%, which is not ideal.

## Looking ahead
Would recommend creating separate labels on the logistic regression, and focus more on that model.
Use the MA50 and MA200 as linear time slots.
Create features based on input of the MA50 and MA200 as a buy/sell affected by date.

## Citation
Shahiar Shochi https://github.com/shahriarshochi
For helping with the needed coding and installations to run Alpaca

