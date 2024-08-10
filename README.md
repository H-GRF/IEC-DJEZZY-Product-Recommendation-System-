# IEC-DJEZZY-Product-Recommendation-System


**Overview:**
Welcome to the IEC Algeria Data Cup - "DJEZZY Product Recommendation System," an exciting machine learning competition organized by the student club "IEC" to showcase their data science and machine learning skills.

**Objective:**
The goal of this challenge is to develop an intelligent recommendation system that can predict which products a customer is likely to subscribe to, based on their subscription history, usage patterns, and other relevant characteristics. This involves exploring the data, identifying the most relevant features, developing effective modeling techniques, and evaluating the performance of the built models.

**Evaluation:**
Participants will be evaluated based on the accuracy of their predictions. They must submit models capable of providing accurate recommendations for products to subscribe to for different customers.

**Submission File:**
The first line of the submission file should contain the column names - "subscribers" and "Product_ID". Each subsequent line corresponds to a single prediction for a specific combination of subscriber and date. (Refer to the SampleSubmission.csv file in the data section for more details).

Example:
```
subscribers,Product_ID
9352,100
9926,101
9691,69
```

**Dataset Description:**
The provided dataset includes several files:
- **train.csv**: Contains information on subscriber subscriptions, including the products they are subscribed to, subscription dates, the number of subscriptions, and data on service usage by subscribers (dates, types of usage, data volumes, etc.).
- **test.csv**
- **simplesubmission.csv**
- **Dset_offers.csv**: Lists the various available offers, including details such as periodicity, price, and included data volume.

**Key Columns:**
- **Subscribers:** Unique identifier for the customer.
- **NB_SUBSCRIPTION:** Number of subscriptions during the specified date.
- **USAGE_DATE:** Date of customer usage (on a daily basis).
- **usage_Type:** Type of usage: DATA, VOICE, SMS.
- **Destination:** Consumption destination: onnet (Same network), offnet (Other Network), or DATA.
- **Amount_DZD:** Total price of consumption.
- **Amount_data_DZD:** Total price of DATA consumption.
- **Volume_Data_KB:** Data volume in kilobytes.
- **Volume_KB_SC_Nbr:** Kilobytes when the usage type is DATA / Seconds when the usage type is VOICE / Number of times of usage when the usage type is different from VOICE & DATA.
- **Nb_USAGE:** Number of the same type of consumption on the same day.



This competition challenges participants to create a recommendation system using historical subscription and usage data to predict future product subscriptions for DJEZZY customers. The main evaluation metric is accuracy.
