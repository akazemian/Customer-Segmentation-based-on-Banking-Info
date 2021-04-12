
### Overview
In this project, I use old financial information belonging to US citizens to classify them into difefrent groups based on their spending behavior and demographic.


### Data
The data can be downloaded [here](https://drive.google.com/file/d/1zAjnf936aHkwVCq_BmA47p4lpRjyRzMf/view?usp=sharing). The and contains the following tables:

- twm_customer - information about customers
- twm_accounts - information about accounts
- twm_checking_accounts - information about checking accounts (subset of twm_accounts)
- twm_credit_accounts - information about checking accounts (subset of twm_accounts)
- twm_savings_accounts - information about checking accounts (subset of twm_accounts)
- twm_transactions - information about financial transactions
- twm_savings_tran - information about savings transactions (subset of twm_transactions)
- twm_checking_tran - information about savings transactions (subset of twm_transactions)
- twm_credit_tran - information about credit checking (subset of twm_transactions)


### Project Outline

I will:
1. Perform customer segmentation (using clustering) to split customer groups into 3-5 clusters based on demographics (twm_customer table)
2. visualize the created clusters and decide the best number of clusters based on features in the data
3. visualize segmentations in 2D (using PCA to reduce the dimansions of the data)
4. Visualize in 2D how the clusters are evolving in each iteration of KMeans by creating my own KMeans algorithm.
