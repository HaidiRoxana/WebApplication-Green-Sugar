# WebApplication-Green Sugar
The purpose of this manual testing project is to ensure the quality and reliability of the Green Sugar web application. The project aims to systematically test the application's functionality, usability, and performance to deliver a seamless user experience.


1.1.Functional Testing
1.1.1.Smoke Testing
1.1.1.1.Menu Tabs
NATQA62-171: Verify if the tabs are clickable
NATQA62-859: Validate that the Home tab button is working properly
1.1.1.2.Main Page
NATQA62-161: Validate that the Green Sugar web application is functional
NATQA62-217: Check the functionality of the arrows from top page slideshow
NATQA62-218: Validate that the photos in the slideshow can be accessed with a click
NATQA62-324: Check if the form at the bottom of the page is functional
NATQA62-330: Check if the Messenger button is functional
1.1.1.3.Search Bar
NATQA62-191: Check if the search button is functional
NATQA62-192: Validate that the search function works correctly
1.1.1.4.Shopping Cart
NATQA62-194: Verify if the shopping cart button is clickable
NATQA62-195: Check if the functionality of the shopping cart works correctly
NATQA62-196: Check if the items can be removed from shopping cart
NATQA62-197: Check the functionality of placing an order.
1.1.1.5.My Account
NATQA62-199: Verify if the tab "Contul Meu" are clickable
NATQA62-200: Validate that registration form is working properly
NATQA62-201: Validate that Login form is working properly
NATQA62-202: Check if the Logout button is working properly
1.1.2.Exploratory Testing
1.1.2.1.My Account
1.1.2.1.1.Registration
NATQA62-341: Validate a new customer account can be created
NATQA62-344: Check if a new account can be created with invalid data
NATQA62-346: Validate that an error is displayed when an existing email is already in use
1.1.2.1.2.Authentication
NATQA62-349: Check if an user can be authenticated with invalid password
NATQA62-628: Validate that the password field is mandatory
NATQA62-629: Validate that the login form with password show/hide toggle eye button is functional
1.1.2.1.3.Account Details
NATQA62-633: Check if the First Name field allows only letters
NATQA62-636: Check if the Last Name field allows only letters
NATQA62-651: Validate that First Name field requires at least two characters
NATQA62-652: Check if the Change Password functionality works by entering valid old pass and matching new ones
1.1.2.1.4.Addresses
NATQA62-653: Validate that an shipping address is generated automatically after complete all the mandatory fields
NATQA62-654: Validate that an existing adress can be deleted
NATQA62-655: Check if the Postal Code consists of a maximum of 6 digits
1.1.2.1.5.Wishlist
NATQA62-656: Validate that wishlist must be associated with a customer account
NATQA62-657: Check if products can be added to the wishlist
NATQA62-658: Check if the products can be removed from Wishlist
NATQA62-659: Validate that a product can be added to shopping cart from wishlist
NATQA62-660: Validate that all the product from the shop are available for the Wishlist
1.1.2.2.Search Bar
NATQA62-661: Verify that the search results are relevant to the search query.
NATQA62-663: Check if the search bar returns the article by product code
NATQA62-664: Test that the search results are displayed correctly when no results are found.
1.1.2.3.Shopping Cart
NATQA62-673: Check if the shopping cart accepts products from different categories
NATQA62-676: Check if the quantity of the products can be modified from the shopping cart
NATQA62-691: Test if the total price in the cart is updated correctly after adding the item
NATQA62-697: Check if the quantity field allows to insert more than 100 units
NATQA62-699: Validates that the delivery is free if the amount of the products is greater than 300 lei
NATQA62-700: Check if the valid discount code works properly
1.1.3.API Testing
NATQA62-976: Verify the HTTP response and its code status
NATQA62-977: Verify that the API receives input and returns the expected output
1.2.Non-Functional Testing
1.2.1.Usability Testing
NATQA62-198: Check if the tab "Contul Meu" open on mouseover
NATQA62-193: Check if the shopping cart button is functional
NATQA62-164: Check if the tabs open on mouseover or not.
NATQA62-335: Check if the "Back to top" button is functional
NATQA62-708: Check if the "Store" button is displayed on the main page
NATQA62-714: Validate that the grid and list buttons from the products are functional
NATQA62-716: Check the functionality of the sorting function
1.2.2.User Interface Testing
NATQA62-168: Verify if the sub-menu colors are changing by mouse-over it
NATQA62-707: Test if the wishlist button appears on the main page after a customer is logged in
NATQA62-709: Check if the text of a product in the website is fully displayed
NATQA62-711: Validate that an image of a product mentain the saim clarity
NATQA62-719: Test if the body image of the page remains the same, if the quantity of the cart is changed
NATQA62-748: Verify that the reCAPTCHA checkbox is properly load in the contact form or not
1.2.3.Security Testing
NATQA62-632: Check the strength of registration mechanisms, including the checking for weak passwords
NATQA62-749: Check if the confidentiality of personal data is protected on the page
NATQA62-857: Validate that the payment security system is activated when an invalid card is used
1.2.4.Compatibility Testing
NATQA62-752: Testing the compatibility of the web application with an O.S Windows 11, Firefox 124
NATQA62-763: Testing the compatibility of the web application with an O.S Windows 11, Opera 108
NATQA62-765: Testing the compatibility of the web application with an O.S Android, Samsung Galaxy 23, Edge
NATQA62-766: Testing the compatibility of the web application with an O.S iOS, iphone 15, Safari
NATQA62-767: Testing the compatibility of the web application with an O.S Mac, Sonoma, Safari 17.3
1.2.5.Code Testing
NATQA62-791: Validate that checking a website's code to determine if it follows the formatting standards
NATQA62-978: Check the existence of major errors in the HTML code
1.2.6.Performance Testing
NATQA62-858: Test the performance of the website on Speedlab
1.2.7.System Integration Testing
NATQA62-860: Validate that the web application is integrated with the Messenger chat plugin
