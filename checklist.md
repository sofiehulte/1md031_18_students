# Checklist

Before you submit the final version of your labs, make sure that your project fullfills all of the tasks mentioned above.

## 00 Introduction

- [X] Install an IDE on your system

## 01 Git

- [X] Fork and clone the 1md032_18_students repository


## 02 HTML

Create an index.html file which contains:
- [X] A headline
- [X] A section to select burgers that contains at least three items. Each item has:
	- [X] A name
	- [X] An image
	- [X] Information about allergies 
- [X] A section to collect customer information:
	- [X] First- and Last Name (in one field)
	- [X] E-Mail Address
	- [X] Street
	- [X] House Number (only allowing numbers in this field)
	- [X] Gender (male, female, do not wish to provide as radio buttons)
- [X] A button to place the order
- [X] Ensure the website loads when opening http://localhost:3000/

## 03 CSS

Create a style.css file which contains:
- [X] A rule to make the allergy information bold
- [X] Different text and background color for the two different sections (burger selection and customer information)
- [X] Change the cursor when hovering over the order button
- [X] Adds margins to the sections and the order button
- [X] Add a border to the two sections
- [X] Create a header that palces an image behind the headline
- [X] Use a grid layout instead of tables for the burger selection section


## 04 JavaScript

Create a menu.js file which contains:
- [X] At least five different burgers with respective attributes

Create a js_script.js file which contains:
- [X] A MenuItem constructor 
- [X] A function that defines at least five different burgers using the MenuItem constructor and adds them to an array
- [X] A function that loops through the array and inserts the information to the burger selection section of the index.html file
- [X] A function that loads the information from the menu.js json object and inserts the information to the burger selection section of the index.html file
- [X] Only displays allergy information if relevant (either only if it contains gluten or lactose, or only if it's gluten or lactose free)
- [X] Add a checkbox to each menu item
- [X] ] A functionality for the order button that writes the information from the text boxes, the gender and all items on the order (that have the checkbox checked) to the bottom of the html file when the button is clicked

Create a vue_script.js file which contains:
- [X] A function that loops through the array and inserts the information to the burger selection section of the index.html file
- [X] A function that loads the information from the menu.js json object and inserts the information to the burger selection section of the index.html file
- [X] Only displays allergy information if relevant (either only if it contains gluten or lactose, or only if it's gluten or lactose free)
- [X] Add a checkbox to each menu item
- [X] A functionality for the order button that writes the information from the text boxes, the gender and all items on the order (that have the checkbox checked) to the bottom of the html file when the button is clicked

## 05 Messaging

- [X] Exchange the field for the customer's address with the interactive map
- [X] Location information from the map should be send to the dispatcher view when pressing the "order" button
- [X] In the dispatcher view, you should see the following for every order:
    - [X] A location on the map
    - [X] The order information
    - [X] The customer information
    
## Optional
- [ ] Set the orderID on client side so one customer can make multiple orders
- [ ] Only allow the order to be sent if all necessary information are provided
- [ ] Display the order(s) on the customer page as well
- [ ] Allow the dispatcher to handle orders by providing buttons next to every order that can switch the order status to "in preparation" and "done"
- [ ] Display the order status to the customer and update it in the customer view if updated by the dispatcher
- [ ] Find a better visualization for what orders belong to which location on the map