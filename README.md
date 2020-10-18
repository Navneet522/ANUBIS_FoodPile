# ANUBIS_FoodPile
Softatblitz Project Aviskar

Whenever the project will run, first of all it will prompt a login form in front of the user(by the help of login.java)

After succussfull login the user will automatically reach to the pos form where he can select the foods by the help of product code (he only needed to enter the product code 
it will automatically fill the product price and its name) 
  now user only needs to fill the quantity in qty text field and click the add button and if this product exist in the 
database with proper quantity then it will added in the user's bucket and similiarly user can add more product in his bucket and 
after selecting all the products in subtotal text field it will show the money needed to pay and a button (Pay Invoice) through which user can pay the money.

After paying the money by the help of the print form it will show the bill and thank you message.

Product.java is used only by the admin of the shopkeeper he can add the products by the their name(category.java will help this), brand (by the help of brand.java), 
its cost price,  retail price and its quantity with barcode and its state (active or deactive).
  Admin can also edit the information of any product by the edit button and can delete and product by delete button.
All these add, edit and delete button is present in pos.java form.
  
Some issues which i think is needs some modifications is that :
    (1).  Product can only be searched by the help of product code it should be product name that will make it more user friendly
    (2).  It should be that only admin(shopkeeper) could modify the database but here any user which has his account in the system
          can change the database so database is not protected from user.
