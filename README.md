# Fake-Instagram-Profile-Detection
Prediction model for fake Instagram profiles

As of December 2021, there are 1.386 billion users registered on Instagram. Out of all registered account, how many are legitimate, created by actual users?
In the recent years, Instagram has been found to be using third party apps, called bots which can definitely impersonate a user and tarnish their reputation leading to ‘identity theft’. There has also been greater instances of malicious ways of promoting the brand image of a company known as “influencer marketing”. These days a number of businesses are using social media to heed to their customers, and a number of social media influencers are using fake accounts to increase their number of followers.

Hence, this model has been built to distinguish between fake and actual accounts based on attributes like existence of profile picture, number of followers, number of posts, length of name/username and so on.

The training dataset consists of 576 records and the testing set consists of 120 data points.

There are 12 attributes for each data point :

![image](https://user-images.githubusercontent.com/64343047/153698891-56d56832-239b-4f69-8075-eeade20042df.png)

These attributes are used to determine which profiles are fake and which are legitimate.

The entire process has been divided into the following steps :
1. Importing Libraries
2. Loading Dataset
3. Exploratory Data Analysis - is used to find correlations between different attributes and determine which attributes contribute most significantly in finding which profiles are fake and which are by actual users.
4. Preparing Data
5. Building ANN Model
6. Display Results

The performance of model is displayed through heatmaps and a confusion matrix.
