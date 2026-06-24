###Fast Food Restaurant MYSQL Database

This database is created by MySQL which was inspired by the receipts of a fast food restaurant.

Here is the diagram of the database:
<img width="333" height="349" alt="mcdonalds_diagram" src="https://github.com/user-attachments/assets/b76d715b-f692-4cea-b984-617aedc6d7a0" />

Meaning of tables:
*PURCHASE_INFO: Purchase record of the restaurant
  -Columns:
    -RecordID: A Unique ID representing every single purchase (Primary Key)
    -ProductID: The ProductID of the purchase (linked to PRODUCT_INFO)
    -UserID: The ID to identify the user (linked to USER_INFO)
    -PurchaseTime: The date and time when user made a purchase 
  
