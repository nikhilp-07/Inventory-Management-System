# Inventory-Management-System
Inventory Management System :-->By using this we can add,update,delete Items/Products from Inventory,-->user can purchase required products if products exist in Inventory,-->In the end we can keep track of all the sales 

-->In this IMS we can add,update,delete Items/Product using JSON ,
   Initially having some 18 products exist in Inventory or database.
   
-->From this we can update the data after product bieng sold

-->Enter True for = Addition and Updation ,
   Enter False for = Deletion
   
   1)adding a new Item/product in to database/Inventory or to update a data of an existing product(only quantity and price).
   
   i) if product exist we can update the existing data(only quantity and price)
   
   - enter quantity for update
   
   - enter change in price for update ( Enter True for = increase ,Enter False for = decrease )
  
   ii)else if dosen't exist we can add products in to Inventory.
   Earlier in database : Total products were = 18; for ex let's add 12 more new products in to database
   
   2) deletion of an item/product from the database/Inventory
   
   i)enter the prod_id to delete the existing product from Inventory
   
   ii) else If product doesn't exist then it displays a message saying - Entered item prod_id-1100 doesn't exist.

--> Purchase : user can purchase the product by entering the product_id and quantity

  i) if the (Availability)quantity of required product is 0 in Inventory/database then, message will be displayed saying - Product is out of stock,Apologize for the Invoncenience      and product will be back in stock soon
  
  ii)else if the quantity of products required by user is more than existing quantity of product in database,then message will be displayed saying - Product is out of            stock,Apologize for the Invoncenience and have the quantity of 35 left for prod_ID - 1008
  
  iii)generation of bill
  
  iv) creating a sales.json file for recording the total products sold and it's basic details like - product_id,quantity,total amount,date-and-time_details,and user phone number.
  
  v) in the end updating the Inventory/database products.¶
