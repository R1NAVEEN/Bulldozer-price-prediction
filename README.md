# Bulldozer-price-prediction

## Predicting the Sale Price of Bulldozers using Machine Learning

***Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers.***

**1. Problem Definition**

> `The Target`: **predicting** the sale price of bulldozers sold at auctions.

**2. Data**

* Meaning of data files:
    * **`Train.csv`** is the training set, which contains data through the `end of 2011`.
    
    * **`Valid.csv`** is the validation set, which contains data from `January 1, 2012 - April 30, 2012` You make `predictions` on this set throughout the `majority of the competition`. Your score on this set is used to create the `public leaderboard`.
    
    * **`Test.csv`** is the test set, which won't be released until the `last week of the competition`. It contains data from `May 1, 2012 - November 2012`. Your score on the test set determines your `final rank` for the competition.
    
    
* The key fields are in train.csv are:
    * **`SalesID`**: the uniue identifier of the sale
    * **`MachineID`**: the unique identifier of a machine.  A machine can be sold multiple times
    * **`saleprice`**: what the machine sold for at auction (only provided in train.csv)
    * **`saledate`**: the date of the sale

* Dataset:https://www.kaggle.com/datasets/farhanreynaldo/blue-book-for-bulldozer

**3. Evaluation**

> **`RMSLE`(root mean squared log error)**: get this value as low as possible

* Submission files should be formatted as follows:

    * Have a header: "SalesID,SalePrice"
    * Contain two columns
        * `SalesID`: SalesID for the validation set in sorted order
        * `SalePrice`: Your predicted price of the sale

**4. Features**

   ***data dictionary for first look at values:***

* `53 unique columns`

* Dictionary can be found:
https://docs.google.com/spreadsheets/d/1hIMNJzXu1U5u4-DSFAU_uFAGvrWSciF5/edit?usp=sharing&ouid=104502734380757905998&rtpof=true&sd=true
