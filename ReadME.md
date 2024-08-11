# Customer Interaction Analysis for Cafe Rewards Program

## 1. Introduction
### Project Overview: 
Analyze customer interactions with the Cafe Rewards program to derive actionable insights on customer behavior, offer effectiveness, and transaction patterns.
### Objectives:
 Understand customer behavior across different offers.
 Identify key drivers for offer completion and transaction volume.
 * Segment customers based on interaction patterns.
Provide actionable recommendations for optimizing the rewards program.
2. Problem Statement
Current Challenge:
The Cafe Rewards program collects vast amounts of data on customer interactions, including offers received, viewed, completed, and transactions made. However, this data is currently underutilized.
The goal is to transform this raw data into meaningful insights that can guide marketing strategies, improve customer engagement, and increase program effectiveness.
Key Questions:
How do different types of offers impact customer transaction behavior?
What are the characteristics of customers who frequently complete offers?
How can we segment customers based on their interaction patterns?
What time patterns exist in customer interactions?
3. Data Collection and Preparation
Data Sources:
Customer interaction data from Cafe Rewards program (CSV format).
Data Description:
customer_id: Unique identifier for each customer.
event: Type of interaction (offer received, offer viewed, offer completed, transaction).
value: Nested dictionary with details such as offer ID, amount, reward, etc.
time: Time of interaction in hours from the start of the program
