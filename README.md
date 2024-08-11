# Airbnb-New-User-Bookings-Merging-Prediction
In this challenge, i have a list of users along with their demographics, web session records, and some summary statistics. I will predict which country a new user's first booking destination will be. All the users in this dataset are from the USA.

There are 12 possible outcomes of the destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. Please note that 'NDF' is different from 'other' because 'other' means there was a booking, but is to a country not included in the list, while 'NDF' means there wasn't a booking. However, i will just keep 5 most popular outcomes: 'NDF', 'US', 'other', 'FR', 'IT'.

The training and test sets are split by dates. In the test set, you will predict all the new users with first activities after 7/1/2014 (note: this is updated on 12/5/15 when the competition restarted). In the sessions dataset, the data only dates back to 1/1/2014, while the users dataset dates back to 2010. 

#Dataset: Airbnb New User Bookings

Link: https://www.kaggle.com/competitions/airbnb-recruiting-new-user-bookings/data

#File descriptions:

train_users.csv - the training set of users

test_users.csv - the test set of users
