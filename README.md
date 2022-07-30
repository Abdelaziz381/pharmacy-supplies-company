# pharmacy-supplies-company
Analysis for pharmacy supplies company
 
### **Products** 
- DATE_ : The date "year , month and day".
- ClintName : Customer name. 
- AccountId : Customer ID and it's a foreign key to a Primary key in "account" tabel.
- ProductName : Full product name. 
- ProductId : Product ID.
- CompanyId : Manufacturer ID and it's a foreign key to a Primary key in "company" tabel.
- CATEGORY1 : Main category ID and it's a foreign key to a Primary key in "proprties" tabel.
- CATEGORY3 : Subcategory ID and it's a foreign key to a Primary key in "proprties" tabel .
- InvoicesId : Bill ID can be repeated.
- UnitSellPrice : Sell price for the product.
- ConsumerPrice : A price suggested by the wholesaler to retailers to sell to the consumer, but it is not compulsory.
- CostPrice : ِThe net cost price.
- QTY : Quantities of the item sold. 


### **Proprties**
- PROPRTIES_ID : Primary key represents classifications of products in general, a category and a sub-category.
- PROPRTIES_NAME : Classification name for both category and sub-category.
- PROPRTIES_TYPE : This code is what determines whether the name belongs to a main ( **1** ) or sub-category (**2 , -1**).

### **Company**
- **A very important note : that Manufacturer is not the vendor**
- COP_ID : Primary key represents Manufacturer ID.
- COP_NAME : Manufacturer name.

### **Account**
- CLIENT_NAME : Customer name.
- CLIENT_ID :  Primary key represents customer ID.
- LOCATION_ID : Area Id represents the ID of customer's state can be repeated.
- LOCATION_NAME : Area name represents the name of customer's state.
_________________________________________________________________________
### Introducing the company
 A B2B company working in the trade of pharmacy supplies and cosmetics stores, its products are cosmetics, paper and medical supplies. It operates in a local environment and seeks to expand the circle of its customers within this environment.
    
## Analysis plan
-------------------------------------------------------------------------------------------------------------------------------
  The first step is to call the libraries see the head for each data ,the form of each the data 
  The next step is to describe the data , display data information, key factor of data 
  then we merge all the four sheets in one dataframe, 
  after cleaning the data then we will move to
  
  
### Questions for analysis.
- **These are the questions we're going to answer**
- **------------------------------------------------------------------------------------------------------------------------------** 1" What is the highest, most and best selling group Manufacture ? 
 2" What is the highest, most and best selling group Category ? 
 3" What is the highest, most and best selling group Subcategory ? 
 4" What is the highest, most and best selling group Area ? 
 5" What is the highest, most and best selling group Product ? 
 6" What is the highest, most and best selling group Client ? 
 7" What is the highest, most and best selling Month ? 
- **The question about the year will appear to have some bias because the years 2020 and 2022 are not complete.**

