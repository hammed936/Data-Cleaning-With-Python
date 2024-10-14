# Data Cleaning With Python

We sold a video editing course to our customers. After they bought it, we wanted to inform them about another product, Product B. To do this, we retargeted them with an in-stream ad, where we explained how Product B could really help them with their projects and encouraged them to fill out a form to show their interest. After collecting their responses, we noticed that some of the information wasn’t clear or correct. We need to fix that information, so our call center team can reach out to these customers and try to help them buy Product B.

### Goals And Objective
- Check for missing values and populate if necessary.
- Remove Duplicates: Identify and eliminate duplicate records to ensure each entry is unique.
- Standardize Formats.

### Data Source

The primary dataset for this project, titled "Customer Call List.xlsx," contains detailed information about each customer, including the following fields: CustomerID, First_Name, Last_Name, Phone_Number, Paying Customer, Do_Not_Contact, Street_Name, City_Name, and State.


### Tools

- python - Data Cleaning

## Analysis

### Data Cleaning
in the initial data preparation phase we performed the following tasks:
1. data loading and inspection

![Screenshot (001)](https://github.com/user-attachments/assets/da0cefcc-59b2-4a5c-a8ae-4e360f746bca)

2. Checking duplicates and missing values.
   
![Screenshot (002)](https://github.com/user-attachments/assets/61dee2ec-d003-4d52-affb-02f334624c12)

4.
![Screenshot (003)](https://github.com/user-attachments/assets/32b26f44-cbf1-4cac-ae40-e880760a61db)

5.
![Screenshot (004)](https://github.com/user-attachments/assets/3c75c4dc-13ba-4a2d-8148-0a06af3833c2)

6.
![Screenshot (005)](https://github.com/user-attachments/assets/8e510ae7-bbf3-4fd4-b8af-677aa74978f4)

7.
![Screenshot (006)](https://github.com/user-attachments/assets/a2b978e9-f831-4ce0-ba95-c6034a011ab2)

8.
![Screenshot (008)](https://github.com/user-attachments/assets/4ec5e59d-3e65-4380-8fa0-0862d4edb02a)
   
9. handling missing values

### Result/Key Findings/Insight
the analysis results are summarized as folows:
1. The phone number entries varied in format, showing no standard way of input.
2. Some customers submitted the form multiple times with the same contact information.
3. The last name field had different punctuation marks, causing inconsistencies in the data.

## Reccomendation:
based on the analysis, we recommend the following actions:
- Update the questionnaire to disallow any punctuation marks in the last and first name field, ensuring cleaner and more consistent data collection.
- Introduce a validation check to prevent customers from submitting the form again if their contact information matches an existing entry.
- Implement a clear format for phone numbers in the questionnaire, such as "(XXX) XXX-XXXX," and provide examples to ensure uniformity.
