# Automatic Ticket Classification - NLP Case Study

Build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, identify the topics of the customer complaints. Since this data is not labelled, apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:
- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others 

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. Use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.
