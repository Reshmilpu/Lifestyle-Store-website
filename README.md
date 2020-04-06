# Lifestyle-Store-website

************** **************************Lifestyle Store*************************************************

An online shopping website for purchase of products.
NOTE: Scrennshots of web pages are inside website screenshot folder.

Features:

    User side- Add products to cart, Place an order, Request their desired products
    Admin side- Manage Inventory, Manage Users

Tech Stack: HTML, CSS, Bootstrap, in-built JavaScript, PHP, SQL, Apache Server (WAMP)


_____________________________________________Folder Structure__________________________________________________
	
	
	project_solution/
	├── css/ (contains all the css files)
	│    ├── bootstrap.css
	│    ├── bootstrap.min.css
	│    └── index.css
	├── fonts/ (contains glyphicons)
	│    ├── glyphicons-halflings-regular.eot
	│    ├── glyphicons-halflings-regular.svg
	│    ├── glyphicons-halflings-regular.ttf
	│    ├── glyphicons-halflings-regular.woff
	│    └── glyphicons-halflings-regular.woff2
	├── js/ (contains Bootstrap Js files.)
	│    ├── bootstrap.js
	│    └── bootstrap.min.js
	├──  img/
	│    └── (contains all images required for developing the website)
	├──  includes/	 
	│    ├── check-if-added.php
	│    ├── common.php
	│    ├── footer.php
	│    └── header.php
	├──  cart-add.php
	├──  cart-remove.php
	├──  cart.php 
	├──  index.php
	├──  lifestylestore.sql (Database of the project)
	├──  login.php
	├──  login_script.php
	├──  logout_script.php
	├──  products.php
	├──  settings.php
	├──  settings-script.php
	├──  signup.php
	├──  signup_script.php
	└──  success.php

____________________________________________SETUP_STEPS_________________________________________________________________________________________				
1.) Start the Apache and MySQL modules using the WAMP controller.
2.) Open the phpMyAdmin and create a database "lifestylestore". 
3.)Create three tables (items, users, user_items) and paste items in items table which you want to show, users to save record which are signing-in in website and user_items for which items they are adding in cart and which are placing order.
5.) Open the browser (chrome), type localhost/ and you should see the "index page" of the website.


*******************************************************************************************************************************************

