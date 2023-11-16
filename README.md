# ETL- Challenge
This repository contains an ETL pipeline of Crowdfunding data created using Python, Pandas, and Python Dictionary to extract and transform the data into four different CSV files. An ERD and a table schema were created with the CSV file data. The CSV files were uploaded to a Progres Database. 

This Crowdfunding ETL pipeline was created in multiple stages:

1.	Creating the category and subcategory dataframe of all the different crowdfunding projects. 
    a.	The categories and subcategories were assigned an ID (e.g., Cat1 or subcat1)
    b.	This was exported as subcategory.csv and category.csv.

2.	Creating a campaign dataframe of all the different crowdfunding projects. 
    a.	This was exported as campaign.csv.

3.	Creating the Contacts Dataframe containing names, emails, and contact_id unique to each individual.
    a.	This was exported as contacts.csv.

4.	Creating the Crowdfunding Database.
    a.	Using QuickDBD, a sketch of the crowdfunding database was created to identify the relationships between each CSV file. 
    b.	Based on the QuickDBD, a table schema was created, and a Postgres Database was developed. 

!(https://github.com/ns96/Crowdfunding_ETL/blob/main/images/ETL_QuickDBD.png)
!(https://github.com/ns96/Crowdfunding_ETL/blob/main/images/campaign.png)
!(https://github.com/ns96/Crowdfunding_ETL/blob/main/images/campaign_join.png)
!(https://github.com/ns96/Crowdfunding_ETL/blob/main/images/category.png)
!(https://github.com/ns96/Crowdfunding_ETL/blob/main/images/contacts.png)
!(https://github.com/ns96/Crowdfunding_ETL/blob/main/images/subcategory.png)
