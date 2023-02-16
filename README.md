# Expense Tracker
> To track expenses and monitor spending habits, helping individuals to manage their budget


To store expense details we need to define columns
- Columns: 
  1. ID
  1. Category
  1. Date
  1. Amount
  1. Description
  1. PaymentMode
  
 
 ### Sample Data
 ```
 ID = 1
 Category = Food
 Date = 16-02-2023
 Amount = 168
 Description = 2 Lassies
 PaymentMode = UPI Payment
 ```
 
 ### Symbols
```
{ }   => Flower Brackets / Curly Brackets
[ ]   => Square Brackets
( )   => Rounded Brackets / Parenthese
/     => Forward Slash
\     => Backwared Slash
'     => Single Quotes
"     => Double Quotes
`     => Backtick
 ```

 
 
 ### Single expense (Entity) data define in JSON format
 ```json
 {
  "ID"  : 1,
  "Category": "Food",
  "Date" : "16-02-2023",
  "Amount": 168,
  "Description": "2 Lassies",
  "PaymentMode": "UPI Payment"
 }
 ```
 
 
 ### Multiple expenses (Entities) data defining in JSON format
 ```json
 [
    {
      "ID"  : 1,
      "Category": "Food",
      "Date" : "16-02-2023",
      "Amount": 168,
      "Description": "2 Lassies",
      "PaymentMode": "UPI Payment"
    },
     {
      "ID"  : 2,
      "Category": "Shooping",
      "Date" : "16-02-2023",
      "Amount": 500,
      "Description": "Buy TShirt",
      "PaymentMode": "CreditCard"
    },
     {
      "ID"  : 1,
      "Category": "Sports",
      "Date" : "16-02-2023",
      "Amount": 720,
      "Description": "Book Cricket Ground",
      "PaymentMode": "Cash"
    }
 ]
 ```

 
 
