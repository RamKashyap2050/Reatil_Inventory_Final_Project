Retail Inventory

Project Structure :-

Client Folder:- 
This is where all the Frontend of the project is located in React App
Testing of Cypress and Postman have been made

Server Folder:-
This is where we have our Index.js where all the connections to SQL have been made using NodeJS and ExpressJS 


2130359 - Chaturvedula Rama Narasimha Kasyap
2130295 - Praneel Reddy Dharpally
2120011 - Deepak Kalagara

The main purpose of this project is to help the retail owners to maintain an E-inventory for their products

Software Stack :- React, Bootstrap, MySQL, NodeJS, expressJS, 

Frontend :- 

Let's Look at Components

-Add Product to a Inventory :- 
  This is our Form Page which basically does read values given and send it to the backend

-Home :- 
    This is our Home page just with some random Background image and some text written in the center

- Footer :- 
    We have our Footer for our page with some random content

-Navbar:-
    We have our Navbar Component which has all routes defined for neccesary components

-Inventory :- 
    We have our Inventory which basically displays all the products retrived from the backend using GET Request,
    In this component we can update the price of a product, or Delete the product if it doesn't exist in the stock using DELETE, POST and PUT
    Our Inventory also has a search bar where you can search for product we want
-ThemeSwitcher :-
    We also designed a Theme Swithcer where using uselocalstorage we make PC remember the themes that've been previously visited
 Backend :- 
 We've used MySQL as Backend, and expressJS is used to Handle HTTP Requests 



 Tesing Documentation:-
 We've Used Cypress to do E2E testing, and Postman with Newman for API testing 
 As you can see Cypress/E2E has the example spec file to do the three test as per project requirement,
 and We've used Postman with Newman(CLI) to do API testing you can see "New Collection postman_collection.json"
 which we've used to run Newman(CLI) test



