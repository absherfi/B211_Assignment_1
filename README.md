# B211_Assignment_1
The purpose of this project is to build a Car class to serve as a piece of the virtual inventory for a small union of used car shops.

First I started by creating the Car class. In this class, the attributes include manufacturer, model, year, mileage, engine, transmission, drivetrain, mpg, exterior color, interior color, accident or damage, and price. Then I created the methods Paint, Repair, Reupholster, Drive, and Modify_Price. The 'Paint' method takes a color name as input and changes the exterior color of the car. The 'Repair' method takes 2 arguements, the part being replaced and the new part. The 'Reupholster' method takes a color name as input and changes the interior color of the car. The 'Drive' method takes a number as input and increase the mileage of the car by that number. The final method is the 'Modify_Price'. This method takes a number as an input and changes the price of the car to that new number.If the number inputted is less than 1, it discounts the car by that amount, prints the new amount, and then has the user confirm the correct price change.

Next, I was tasked with creating a Seller class. The attributes in this class are name, rating, and the inventory. The 2 methods in this class are 'Buy' and 'Sell'. The 'Buy' method takes a car that is not currently in the inventory as the input and adds that car to the Seller's inventory. The 'Sell' method takes a car in the Seller's inventory as the input and removes it from the inventory.

After the 2 classes were created, I imported the csv file to create a virtual database of Sellers and their Cars.

I included default values to the '__init__' method of the 'Car' class for the attributes 'accident_or_damage' and 'price'. The addition of default values allows for better error handling if there is no data in either the accident_or_damage or price attribute.
