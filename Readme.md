Food Ordering System
________________


The program facilitates food ordering by the users by taking in user info that includes - Username, Email, Address, City, Password, Mobile Number. Collection of above information and its storage culminates the registration process, Then the user is offered a number choices among restaurants, with each having its menu and its coordinates stored in a database. The user places the order using one of the payment methods. The order is tracked using a real time timer module, if order delivery exceeds a particular limit, then the user is offered with a choice to either deem the order as successful or cancel it. 


 Prerequisite
________________


1. Python
2. SqLite 


 Running the Test
________________


1. Download the 2017165_MT21217_MT21174_MT21218.zip folder. 


2. Database :
You can either directly use the ‘Food_Ordering.db’ file for the database or create the same by running ‘Food_Ordering_Database.py’ file. 
         
>> cd <File path>/2017165_MT21217_MT21174_MT21218
>> python Food_Ordering_Database.py


The above commands will generate the database file Food_Ordering.db. This file will be used to run the main programme. 


3. Food Ordering System (Python Programme) - 
Run the programme in local server using the following command 


>> python Food_Ordering_System.py


The sample test case is provided below for reference.


Sample Test Case 1


Welcome to the Portal!
Please select from the following options
1. Sign In
2. Sign Up
3. Exit
2
Enter Name to register
mansigupta@gmail.com
Enter Address
(3,8)
Enter City
Delhi
Enter Mobile Number
6489203412
Enter the Email ID for Sign Up
mansigupta@gmail.com
Email ID registered successfully.
Create Password
xyz@123
Sign Up Successful!
Please select from the following options
1. Sign In
2. Sign Up
3. Exit
1
Enter Email ID
mansigupta@gmail.com
Enter Password
xyz@123
Welcome mansigupta@gmail.com
Please select the restaurant you wish to order from
R.No     Restuarant      Address         Rating     Estimated Delivery (min)
----     ----------      -------         ------     -----------------------
1        Dominos Pizza   (3,5)           3.0        18.0
3        Diggin          (1,5)           4.0        20.0
4        Bakebook Bakery (8,2)           5.0        26.0
Enter the Restaurant Number (R.No.)
1
Menu of Dominos Pizza
Item No.   Item                           Price (Rs.)
--------   ----                           -----------
1          Pizza                          200.0
2          Garlic Bread                   110.0
Enter -
1 <Item No.> <Item Quantity> --> To Move the Item to Cart
2 <Item No.> <Item Quantity> --> To Move the Item to Wishlist
3 --> Go To Cart
4 --> Go To Wishlist
5 --> Exit from App
6 --> Go to Restaurants
1 1 1
2 2 1
3
---------------------- CART ITEMS --------------------------- 


Item No.   Item            Quantity        Price (Rs.)    
--------   ----            --------        -----------
1          Pizza           1               200.0
Enter-
 1 --> Return To Menu
'2 <Item No>' --> To delete the particular item from cart
 3 --> Discard entire order
 4 --> Proceed To CheckOut
1
Menu of Dominos Pizza
Item No.   Item                           Price (Rs.)
--------   ----                           -----------
1          Pizza                          200.0
2          Garlic Bread                   110.0
Enter -
1 <Item No.> <Item Quantity> --> To Move the Item to Cart
2 <Item No.> <Item Quantity> --> To Move the Item to Wishlist
3 --> Go To Cart
4 --> Go To Wishlist
5 --> Exit from App
6 --> Go to Restaurants
1 2 2
3
---------------------- CART ITEMS --------------------------- 


Item No.   Item            Quantity        Price (Rs.)
--------   ----            --------        -----------
1          Pizza           1               200.0
2          Garlic Bread    2               220.0
Enter-
 1 --> Return To Menu
'2 <Item No>' --> To delete the particular item from cart
 3 --> Discard entire order
 4 --> Proceed To CheckOut
2 1 
---------------------- CART ITEMS --------------------------- 


Item No.   Item            Quantity        Price (Rs.)    
--------   ----            --------        -----------    
2          Garlic Bread    2               220.0
Enter-
 1 --> Return To Menu
'2 <Item No>' --> To delete the particular item from cart
 3 --> Discard entire order
 4 --> Proceed To CheckOut
4
Bill Total: 220.0
Apply promocode
1. Apply SAVE20
2. Apply SAVE50
3. Continue without PromoCode
1
Promocode Applied
Bill Total:200.0
 Following are the payment options:Please select
1. GooglePay/BHIM
2. Net Banking
3. Debit/Credit Card
4. Exit
1
Do you wish to continue
1.YES
2.NO
1
enter your mobile number
6789904562
Processing......
Do not refresh the page
Payment Completed
Your order will be delivered within  18.0  sec(s)
Order will take longer than estimated
Do you wish to cancel the order?
1: Continue to Order
2. Cancel Order
Please enter your Choice
1
Order delivered in : 36.72 seconds
Enter
1: To give feedback
2: To exit
1
Rate Food on the scale of 1 to 5
3
Rate App on the scale of 1 to 5
4
Thank You for your valuable feedback !
Enter-
1: To order again
2: exit
2
	

        Sample Test Case 2


Welcome to the Portal!
Please select from the following options
1. Sign In
2. Sign Up
3. Exit
1
Enter Email ID
mansigupta@gmail.com
Enter Password
xyz
Incorrect Password. Select
1: Login Again
2: Forgot Password
2
Create new Password 
xyz
Password Updated
Please select from the following options
1. Sign In
2. Sign Up
3. Exit
1
Enter Email ID
mansigupta@gmail.com
Enter Password
xyz
Welcome mansigupta@gmail.com
Please select the restaurant you wish to order from
R.No     Restuarant      Address         Rating     Estimated Delivery (min)
----     ----------      -------         ------     -----------------------
1        Dominos Pizza   (3,5)           3.0        18.0
3        Diggin          (1,5)           4.0        20.0
4        Bakebook Bakery (8,2)           5.0        26.0
Enter the Restaurant Number (R.No.)
3
Menu of Diggin
Item No.   Item                           Price (Rs.)
--------   ----                           -----------
1          White sauce pasta              500.0
2          Veg Hakka Noodles              400.0
Enter -
1 <Item No.> <Item Quantity> --> To Move the Item to Cart
2 <Item No.> <Item Quantity> --> To Move the Item to Wishlist
3 --> Go To Cart
4 --> Go To Wishlist
5 --> Exit from App
6 --> Go to Restaurants
2 1 1
4
----------------- Wishlist ITEMS ------------------- 


Item No.   Item            Quantity        Price (Rs.)    
--------   ----            --------        -----------
1          White sauce pasta 1               500.0
Enter-
 1 --> Return To Menu
'2 <Item No>' --> To delete the particular item from wishlist
'3 <Item No>' --> To move item to cart
1
Item No.   Item                           Price (Rs.)     
--------   ----                           -----------
1          White sauce pasta              500.0
2          Veg Hakka Noodles              400.0
Enter -
1 <Item No.> <Item Quantity> --> To Move the Item to Cart
2 <Item No.> <Item Quantity> --> To Move the Item to Wishlist
3 --> Go To Cart
4 --> Go To Wishlist
5 --> Exit from App
6 --> Go to Restaurants
Enter -
1 <Item No.> <Item Quantity> --> Add the Item to Cart
2 <Item No.> <Item Quantity> --> Add the Item to Wishlist
3 --> Go To Cart
4 --> Go To Wishlist
5 --> Exit from App
1 1 1
3
---------------------- CART ITEMS --------------------------- 


Item No.   Item            Quantity        Price (Rs.)    
--------   ----            --------        -----------
1          White sauce pasta 1               500.0
Enter-
 1 --> Return To Menu
'2 <Item No>' --> To delete the particular item from cart
 3 --> Discard entire order
 4 --> Proceed To CheckOut
4
Bill Total: 500.0
Apply promocode
1. Apply SAVE20
2. Apply SAVE50
3. Continue without PromoCode
1
Promo Code Not Valid
Bill Total:500.0
 Following are the payment options:Please select
1. GooglePay/BHIM
2. Net Banking
3. Debit/Credit Card
4. Exit
1
Do you wish to continue
1.YES
2.NO
1
enter your mobile number
466878789
Not a Valid Mobile Number, try again!
6789054321
Processing......
Do not refresh the page
Payment Completed
Your order will be delivered within  20.0  sec(s)
Order will take longer than estimated
Do you wish to cancel the order?
1: Continue to Order
2. Cancel Order
Please enter your Choice
1
Order delivered in : 36.08 seconds
Enter
1: To give feedback
2: To exit
2


	



Viewing Doxygen Documentation
________________




To view the .html file for documentation, download the ‘2017165_MT21217_MT21174_MT21218\doxy’ folder and go to the ‘doxy\test\html\index.html’ to access the index.html which contains the documentation done on the code with help of Doxygen. 
Class diagrams help in understanding the overall class structure and flow better.


 
Authors
________________




Gyanvi Agarwal (gyanvi21217@iiitd.ac.in)
Harshit Somani (harshit21218@iiitd.ac.in)
Mansi (mansi17165@iiitd.ac.in)
Saksham Girotra (saksham21174@iiitd.ac.in)