# CryptoClustering
Leveraging Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes





---
# Module 19 Challenge Instructions (provided by edX Boot Camps LLC)

## Due Thursday by 23:59 Points 100 Submitting a text entry box or a website url

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Before You Begin

1. Create a new repository for this project called `CryptoClustering`. Do not add this homework to an existing repository.
2. Clone the new repository to your computer.
3. Push your changes to GitHub.

## Files

Download the following files to help you get started:

[Module 19 Challenge files](Links to an external site.)

## Instructions

1. Rename the `Crypto_Clustering_starter_code.ipynb` file as `Crypto_Clustering.ipynb`.
2. Load the `crypto_market_data.csv` into a DataFrame.
3. Get the summary statistics and plot the data to see what the data looks like before proceeding.

### Prepare the Data

1. Use the `StandardScaler()` module from scikit-learn to normalize the data from the CSV file.
2. Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
3. The first five rows of the scaled DataFrame should appear as follows:
![Image](https://static.bc-edx.com/data/dla-1-2/m19/lms/img/PCA_DataFrame.png)

