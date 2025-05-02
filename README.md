# Bank Account Fraud Analysis
## Introduction
Detecting fraud in bank account transactions requires a keen eye for unusual patterns or activities. Monitoring specific aspects of transactions can help banks and customers identify potential fraudulent behavior. Here are key aspects to monitor in order to detect fraud effectively:
1. Transaction Amounts and Frequency  
    - Large or Unusual Transactions: Monitor for unusually large transactions, especially those that exceed normal spending patterns for the account holder. Fraudulent transactions often involve large sums of money that are quickly moved or withdrawn.  
    - Frequent Small Transactions: Fraudsters may break down large transactions into smaller amounts to avoid detection, especially if there are withdrawal limits or anti-fraud thresholds. Monitoring for multiple small transactions in a short period of time can help identify such patterns.  
    - Transactions Just Below Limits: Fraudsters may try to stay below transaction limits that trigger alerts, so it's important to monitor for activities where the amounts are consistently close to these thresholds.

2. Geographic Location and Device Use  
    - Location Inconsistencies: If a customer typically makes transactions in one geographic region but then suddenly initiates a large transaction from a different country or region, it could indicate a potential fraud. Cross-border transactions or rapid location shifts may signal fraud, especially if the account holder hasn’t traveled.  
    - Device/Channel Consistency: Fraudsters may use different devices (e.g., mobile, desktop) or unfamiliar networks to access accounts. Sudden shifts in device usage or IP addresses can trigger alerts. Monitoring the type of device and internet network (e.g., new IP address, public Wi-Fi) used for transactions can reveal suspicious activity.  

3. Time of Day and Frequency  
    - Unusual Hours: Fraudulent transactions often occur outside of regular banking hours or during odd hours (e.g., late night or weekends). If a customer typically performs transactions during business hours, any transactions outside these hours should be flagged for review.  
    - High Transaction Volume in Short Periods: A high number of transactions within a short time frame (e.g., several withdrawals in a few minutes) can indicate fraudulent behavior. This could be due to "carding" attacks or unauthorized access attempts.  

4. New Payees or Beneficiaries  
    - Changes in Beneficiaries or Payees: If the account holder suddenly starts transferring money to new or unfamiliar payees, especially if these payees are in different locations or countries, it may signal that the account has been compromised.  
    - Frequent Changes in Payment Details: Changes to payee details (e.g., bank account numbers, recipient names) without a clear reason should be monitored closely, as fraudsters may try to redirect funds to their own accounts.

5. Unusual Withdrawals or Transfers  
    - Out-of-Character Withdrawal Patterns: Sudden, significant withdrawals that are inconsistent with the account holder’s normal behavior (e.g., withdrawing a large sum all at once or multiple withdrawals over a short period) are key indicators of fraud.  
    - Transfers to Unknown Accounts: Monitor for large sums being transferred to external accounts or unverified accounts, especially if the transfers are out of the account holder’s usual pattern.  
    - ATM Withdrawals in Different Locations: If there are multiple ATM withdrawals across different locations (especially international), this can indicate that an account is being accessed fraudulently.  

6. Multiple Failed Login Attempts  
    - Suspicious Login Attempts: Multiple failed login attempts in a short period can be an indicator of an attempted account takeover. Fraudsters often try to guess passwords or use brute-force techniques to gain unauthorized access.  
    - Unsuccessful Authentication Attempts: If there are multiple unsuccessful attempts to authenticate a user’s identity (e.g., incorrect password or failed biometric verification), it could signal that fraudsters are trying to break into the account.  

7. Use of Different Payment Methods  
    - Unfamiliar Payment Methods: A sudden shift in the type of payment method being used (e.g., shifting from credit card payments to mobile wallets or cryptocurrency) could be a red flag.  
    - High-Risk Transactions: Certain payment types are more commonly associated with fraud, such as wire transfers to international accounts, or prepaid card transactions. Monitoring for an increase in these types of transactions could be useful.  

8. Multiple Accounts Linked to One Identity
    - Multiple Accounts Using the Same Information: Fraudsters may attempt to open several accounts using synthetic identities or stolen personal information. Banks should track accounts that are linked to the same identity (e.g., same phone number, email, or address).  
    - Coordinated Transactions Across Accounts: Fraudsters may create multiple accounts and transfer funds between them to disguise the origin of stolen money. Monitoring transactions across accounts that appear to have no legitimate business relationship can highlight fraudulent activity.  

9. Unusual Behavior Relative to Historical Patterns  
    - Deviation from Historical Spending Patterns: Fraud detection systems should be capable of analyzing historical transaction data to establish typical behavior patterns. Any deviation from these patterns, such as a significant increase in spending, can be a potential fraud indicator. 
   

## Objective




## Installation
```
```


## Dataset
> [Bank Account Fraud Dataset Suite (NeurIPS 2022)](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022)  

## Reference
> [5% of all digital transactions originating from Canada were suspected to be fraudulent.](https://newsroom.transunion.ca/suspected-digital-fraud-originating-from-canada-soars-in-2023-canada-with-third-highest-increase-in-fraud-rates-among-19-countries-analyzed-by-transunion/)  
> [An estimated $800 billion to $2 trillion, or 2 to 5% of the global GDP, is laundered through the financial system each year.](https://linkurious.com/anti-money-laundering/)  
> [Transaction monitoring in anti-money laundering (AML) stands as a frontline defense.](https://linkurious.com/transaction-monitoring-in-aml/)  
