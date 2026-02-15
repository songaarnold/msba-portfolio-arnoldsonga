#Source Tables

Customer table- one row represents one customer;it contains variables like Customer ID, Signup date / tenure in months, Customer type (new, returning, long tenure). This is the identity anchor for the entire dataset.

Subscription/plan table- one row represents plan configuration for a customer; it contains variables like Add on services, Monthly fee, Contract type. It is important as add on services indicate engagement and stickiness

Usage/activity table- one row represents one customer’s usage for a given month; it contains variables like Average GB downloaded, Long distance minutes or fees. It's good for showing early signals for churn

#Connecting Keys

These are the join keys that would link the tables together.
•	customer_id
•	account_id
•	subscription_id
•	date or month

#Risks and Mitigation

Examples of risks are duplicates, missing IDs, using information that only exists after churn happens, and definitions changing over time.

Data leakage (using data after churn)- Fix by filtering data before churn date
Duplicate or inconsistent IDs- Fix by enforcing primary keys and deduplication
Missing usage data- Fix by flagging missingness and using imputation



