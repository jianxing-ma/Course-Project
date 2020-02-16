## High-level Requirements

Upon some stimulus [per some constraint, if any], and while X is in the Y State, the System shall display an output message within some time limit and for some duration, [per some constraint, if any].

### 1. MVP - minimum-viable product

####  Main Page
1.	Functional: Upon typing the address of the main page website, the main page should display right away. 
2.	Non-functional: The main page should include the title of the website, pictures of products and a login button on the top right-hand corner. 
####  Login
3.	Functional: Upon clicking the login button, a dialogue should pop up, which gives the option buttons of login or register. The default will be login dialogue.
4.	Non-functional: The login dialogue should be in the center of the page with length and width being 1/3 of the page’s.
5.	Non-functional: The login dialogue should display as two lines of username and password; the register dialogue should display as three lines of username, password and reenter password.
6.	Functional: Upon clicking on the login dialogue’s username and password line, user should be able to input characters, and finish by a single click somewhere else on the page.
7.	Functional: Upon clicking the “Enter” button or by hitting enter after finishing the password line, the system should recognize the combination and compare to the database.
8.	 Functional: If the input matches the database, the page should return to main page with username shown on the top right corner which replaces the login button. 
9.	Functional:  If the input does not match the database, it should clear the input and return a message “The username or password is invalid.” The dialogue should be able to accept input again.
10.	Functional: Once the login requirements are all met, the page should return to main page with username shown on the top right corner which replaces the login button.
####  Register
11.	Functional: The register dialogue should accept input by the user. For the username, it should compare to database once user finishes input, if the username already exists, user’s input should be cleared and a message” The username already exists” should be displayed.
12.	Functional: Once the register dialogue’s username is valid, user should be able to enter password by clicking on the line. 
13.	Functional: The input of password line and re-enter password line should be compared, if they do not match, the user input of passwords should be cleared and a message “The passwords do not match” should be displayed.
14.	Functional: Once the register requirements are all met, the page should return to main page with username shown on the top right corner which replaces the login button.
15.	Non-functional: On the top of the page, there should be search block which allows text input for search function.
16.	Functional: Upon clicking the “search” button, the page should redirect to the search product page.
####  Search Product Page
17.	Non-functional: the search block should still be on top of the page, with search keywords remaining in the block.
18.	Non-Functional: There should be a list of product titles and photos showing from top to bottom.
19.	Functional: Upon clicking on each photo, it should redirect to the product page.
####  Product Page
20.	Functional: Upon clicking on the product picture of the main page, it should direct to the product details page.
21.	Non-functional: The pictures of the product should be on the center top of the page, a main photo will be shown.
22.	Non-functional: The rest of the photos will be below main photo shown in a horizontal line in mini scale.
23.	 Functional: There should be left and right arrows besides the main photo. Upon clicking on it, the previous or next photo should be shown.
24.	Non-functional: Under the photos, there should be a title of the product, the condition of the product, the price of product and the word description of the product.
25.	Non-functional: Next to the title, there should be a “Contact seller” button.


### 2. Full - "should have"

####  Conversation Dialogue
26.	Functional: Upon clicking on “Contact seller” button, a conversation dialogue should pop up at the bottom right corner.
27.	Non-functional: The conversation dialogue should have seller’s name and the product title on top.
28.	Non-functional: The conversation dialogue should have a block that displays messages from buyer and seller.
29.	Non-functional: There should be a block that accepts text input from the buyer or seller. 
30.	Functional: Upon clicking in the block, input should be available.
31.	Functional: There should be an “enter” button in the text block; upon clicking on it, the text input block should clear and the text should appear in the dialogue block.
32.	Functional: On the top right corner, there should be an exit button, upon clicking it, the conversation dialogue should close.
33.	Functional: On the top right corner, there should be a minimize button. Upon clicking it, the conversation dialogue should minimize to showing just the title of the product.
####  Upload Product Page
34.	Non-functional: For the Seller, it should have a “sell an item” button.
35.	Functional: Upon clicking on the “Sell an item” button, a dialogue or new page should display with blocks for user to fill.
36.	Functional: Upon clicking the “Upload photos” button, a dialogue should pop up requesting local directory of target photos.
37.	Functional: Upon clicking the title block, the price block, the condition and the description block, user should be able to input characters.
38.	Functional: Upon clicking the “Submit” button, the system should post the product and user’s page will redirect to the product page.
39.	Non-functional: For the seller page, it should be divided into two categories – selling and sold. Both lists should have a title and a picture representing each product.
40.	Functional: Upon moving cursor to the product, a “edit” button should pop up.
41.	Functional: Upon clicking the “edit” button, it should take user to the adding product page. 
####  Profile Page
42.	Non-functional: It should display users' profile page independently as a buyer and a seller.
43.	Non-functional: For the buyer, it should display a list of product titles and photos the user has purchased.
44.	Non-functional: For the seller, it should display all the products titles and photos the user is selling.
45.	Functional: Upon clicking on the photo of the selling products, it should redirect the user to the product page.


### 3. Stretch - "nice to have"

46.	Non-functional: The product page can include similar or related products on the bottom of the page.
47.	Non-functional: Users rating independently as a buyer and seller. 
48.	Non-functional: Seller's preferred location displayed on map or as zip code on the market page. 
49.	Non-functional: Comment section for products and customers; 
50.	Functional: Products divided by categories and sorted in more specific details.


