# servicenow-training-management-system


# Smart Training & Access Management System

##  Project Overview
Built a ServiceNow application to manage employee training, access control, and bulk data import.

## Features
- Custom table: Training Management
- Reference fields (User table)
- Role-based ACL (training_user, training_admin)
- Field-level security (Marks restricted)
- Import Sets & Transform Maps
- Filters and UI customization

##  Concepts Used
- Tables & Fields
- Dictionary
- Reference fields
- Users, Groups, Roles
- ACL
- Import Sets

## Testing
- Verified access using impersonation
- Tested duplicate handling in import
- Validated field-level restrictions

## Screenshots
1)Training Management Table create-
<img width="1906" height="857" alt="Screenshot 2026-04-26 184506" src="https://github.com/user-attachments/assets/6143bcc0-8378-4ff8-ba04-98a0dcaad2a4" />

2)Training courses and status dropdown list -
<img width="1909" height="859" alt="image" src="https://github.com/user-attachments/assets/23a1176b-156c-4cf9-b12c-bd7a0eae9393" />

<img width="1916" height="851" alt="image" src="https://github.com/user-attachments/assets/013b306d-d17e-413b-b0d7-b355c32d5b81" />

3) Create Role-

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2c6c1d51-9051-491c-ab6d-b3ba4c4adf88" />

4) Create User 
User no -1-
<img width="1919" height="888" alt="Screenshot 2026-05-10 161006" src="https://github.com/user-attachments/assets/e45fa468-88d1-4b84-83f3-97c1fae1ebed" />

Role assign to user - as training User

<img width="1889" height="842" alt="image" src="https://github.com/user-attachments/assets/20ea213f-aa16-4fc6-9cc1-efe575086e83" />

User no-2
create user no 2 assigned role - as training admin

<img width="1904" height="836" alt="image" src="https://github.com/user-attachments/assets/34fda72a-7875-4570-b028-0148ec8c15f7" />

5) Create group of training Team-
<img width="1908" height="843" alt="image" src="https://github.com/user-attachments/assets/093ddef2-f9eb-410b-99a1-ac1f0284a94b" />

--->  Assign Role of Training admin to This Group-
<img width="1896" height="841" alt="image" src="https://github.com/user-attachments/assets/ebefbc67-5c51-4be6-a93d-ead94407d9cd" />

  
6) Create Records for Training Managament and upload it .
( By using Import set ---> load data of excel file , transfor mapping  with mapping assist with target table, with Coalesce and then transform)
<img width="1919" height="774" alt="image" src="https://github.com/user-attachments/assets/f49a5746-acb1-4c61-8c3e-572ce570594d" />

7) Apply ACL--->
   A) Read authority to training user .
  <img width="1898" height="823" alt="image" src="https://github.com/user-attachments/assets/a74539ff-78fd-4f86-9f05-737d24642c7e" />

  <img width="1904" height="872" alt="image" src="https://github.com/user-attachments/assets/e913f048-a83f-4aca-a01c-233651336e4b" />

  B) Update Authority to Trainer -  edit 
    <img width="1898" height="839" alt="image" src="https://github.com/user-attachments/assets/7e6cf50d-0b6d-4750-8b65-70b2ed931fa2" />
     <img width="1902" height="807" alt="image" src="https://github.com/user-attachments/assets/3f0ea120-a931-4611-a6f6-56d74c333d54" />


  C)Mark Read authority to trainer
    <img width="1891" height="867" alt="image" src="https://github.com/user-attachments/assets/b59f289d-6aab-4ed0-ba6a-55f5ed10511c" />

8)Impersonation-
  A)As training_user:
open records, but can't edit and see marks -

<img width="1915" height="885" alt="image" src="https://github.com/user-attachments/assets/787590d3-140a-49d5-8878-8f1e1defe66f" />

B) AS trainer :- open records , can see and  edit marks -
<img width="1906" height="725" alt="image" src="https://github.com/user-attachments/assets/9f0311ce-28d7-4999-b0cf-a3eeec990c6e" />

9)UI + Filter Customization -
<img width="1918" height="776" alt="image" src="https://github.com/user-attachments/assets/31631fd1-06ef-48ba-9ca9-6bbd31678702" />

<img width="1577" height="746" alt="image" src="https://github.com/user-attachments/assets/f79b60b7-b8dc-4fd6-8331-d808e71b9a9e" />



