# Fetch-Rewards-Take-Home-Test

**Folder Structure :** The 5 files in this folder as numerically indexed based on the submission order.

  

*   1\. **Data Model.png** : New structured relational data model
*   2\. **SQL Queries.pdf** : Queries that directly answer predetermined questions from a business stakeholder
*   3\. **Data Quality Report.ipynb** : Evaluation of Data Quality Issues in the Data Provided (notebook file)
    *   3.1 **Data Quality Report.pdf** (pdf submission for the same steps)
*   4\. **Email.pdf** (Communication email for Stakeholders)

  

2\. **Additional Directory:**

*   data/ : Consists of 3 unzipped data files, as provided, without any manipulation.

  

## Quick Overview of New Data Model:

  

In order to build a normalized datamodel, I have generated a new table from Receipts data called item\_recipt table which consists of receipt\_id, and all the normalized fields from rewardsReceiptitemList field. This can be used to join between receipt and brand table enabling us to maintain a relational structure in our data model.

  
![title](1.%20DataModel.png)
