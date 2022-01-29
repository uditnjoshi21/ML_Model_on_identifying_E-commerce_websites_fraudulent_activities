# ML_Model_on_identifying-E-commerce-websites-fraudulent-activities
To build a machine learning model, that predicts the probability that the first transaction of a new user in an E-commerce websites is fraudulent.

## High-level problem statement-
E-commerce websites often transact huge amounts of money. Whenever a huge amount of money is moved, there is a high risk of users performing fraudulent activities,
e.g. using stolen credit cards, laundering money, etc.

## Details-
XYZ is an e-commerce site that sells wholesale electronics. You have been contracted to build a model that predicts whether a given transaction is fraudulent or not.
You only have information about each user’s first transaction on Electronica’s website. If you fail to identify a fraudulent transaction, Electronica loses money 
equivalent to the price of the fraudulently purchased product. If you incorrectly flag a real transaction as fraudulent, it inconveniences the Electronica customers 
whose valid transactions are flagged—a cost your client values at $8.


## Fraud Data Description - information about the first transaction of each user.
**Columns:**

**• user_id** : Id of the user. Unique by user.

**• signup_time** : the time when the user created her account (GMT time).

**• purchase_time** : the time when the user bought the item (GMT time).

**• purchase_value** : the cost of the item purchased (USD).

**• device_id** : the device id. You can assume that it is unique by device. I.e., 2 transactions with the same device ID means that the same physical device was used to buy.

**• source** : user marketing channel: ads, SEO, Direct (i.e. came to the site by directly typing the site address on the browser).

**• browser** : the browser used by the user.

**• sex** : Male/Female. 

**• age** : user age.

**• ip_address** : user numeric ip address.

**• class** : this is what we are trying to predict: whether the activity was fraudulent (1) or not (0).

**• country** : country of IP address.
