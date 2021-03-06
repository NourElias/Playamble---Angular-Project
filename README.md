# Playamble---Angular-Project
Playamble is a web app which facilitates casino-style gaming for users. Payment support is included. The games include:

* Hi-Lo
* Blackjack
* Poker
* Roulette

### Requirements:

* Nebular Library
* PgAdmin
* Node JS

### Project Setup:

* Launch the database.
* Open the backend file "NodeJS-postgres-integration-master" in VSC and run the following code in the terminal:

![](Playamble%20Images/backend.png)

Finally open the main file in VSC and run the following codes in the terminal:

![](Playamble%20Images/npmi.png)

![](Playamble%20Images/serve.png)


### Login Page:

![](Playamble%20Images/Login.png)

A user that has registered before can login successfully into Playamble.
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/forms/login/login-component) 

### Register Page: 

![](Playamble%20Images/Register.png)

ِAny user can register filling up the required information.
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/forms/login/login-component) 


### Users DB:

Once a user registers, all information is recorded and saved to the database. 

![](Playamble%20Images/UsersDB.png)

Passwords that the users create for their login are encrypted using JWT. 

### Credit Cards DB:

![](Playamble%20Images/CreditCardsDB.png)

All credit cards are displayed with their corresponding information.

### Users Dashboard:

![](Playamble%20Images/Dashboard.png)

Dashboard consists of 2 graphs that display profit from the games played. The Dashbaord color can be changed from Light, Dark, Cosmic, and Corporate. 
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/dashboard) 

### Admin Dashboard:

![](Playamble%20Images/AdminDashboard.png)

Admin Dashboard has "check users" in addition to what the users have.
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/dashboard) 

### Check Users:

![](Playamble%20Images/Users.png)

Admins can see a list of all available users.
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/tables/users-table) 


### Make Admin or Delete User:

![](Playamble%20Images/MakeAdmin.png)

Admins can make users also admins or delete users.
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/tables/users-table) 

### Shop:

![](Playamble%20Images/Shop.png)

In the shop page users can buy packages to gain balance for them to play with.
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/shop/shop-page) 

### Purchasing A Package:

![](Playamble%20Images/PurchasingAPackage.png)

Users can choose with credit card to pay from while purchasing a package. 
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/shop/purchase) 

### Credit Card Balance:

![](Playamble%20Images/CreditCardInfoWithBalance.png)

Credit card infomration will be updated when balance is purchased. 
[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/tables/smart-table) 

### Hi-Lo Game:

![](Playamble%20Images/HiLoGame.png)

Hi-Lo game interface.

### Hi-Lo Game choose which credit card to play with:

![](Playamble%20Images/HiLoGameCreditCard.png)

### Hi-Lo Game winning and losing:

![](Playamble%20Images/HiLoGameWin.png)

Winning will grant the user +1 balance.

![](Playamble%20Images/HiLoGameLose.png)

Losing will result in -2 balance.

[(View the code!)](https://github.com/NourElias/Playamble---Angular-Project/tree/master/Playamble-main/src/app/pages/games/hi-lo) 



