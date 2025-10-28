# Delia's Donuts Website (Foundations of Front End Dev Project: Building an Online Food Ordering Application)

## Project Description
This is a beginner web application that simulates a donut ordering website. It includes a login page, a payment page, and a donut menu page that includes donut menu items, an "Add to Cart" button for each item, and a "Shopping Cart" that keeps track of purchases. This page includes HTML, Tailwind CSS for styling, and simple JavaScript for dynamic interactivity. Includes a simulated AJAX call to a JSON database file. 

## How it Works
1. Donuts are loaded dynamically from donuts.json when donutMenu.html is opened.
2. Users can add donuts to their shopping cart, which stores items in an array.
3. The "Shopping Cart" button displays all selected items and the total cost.
4. Login and payment pages validate user input against predefined credentials.
5. Reset buttons allow clearing form inputs for testing and convenience.

## Features
- Menu loaded dynamically from JSON file via simulated AJAX call
- Responsive grid layout to display donuts
- Interactive and functional navigation header complete with functional shopping cart
- Functional "Add to Cart" buttons that push information to an array
- "Shopping Cart" calculates total cost
- User-friendly alerts display when adding items to cart or viewing total
- User input displays on login and payment pages when credentials are accurate or not
- Beginner Tailwind styling with interactivity

## Installation/How to Run
1. Download or clone repository
2. Make sure that "donuts.json" exists in the project file and includes donut data.
3. Open "donutMenu.html" in browser to view menu. You can access login and payment pages via navigation header. 
4. Click the "Add to Cart" button on donuts, and click the "Shopping Cart" button to view your purchases and total. 
5. Open "login.html" in browser (or navigate from donuts.html via navigation header).
6. Enter login credentials in the form boxes. Login: test@test.com Password: password will trigger "Login successful". Any other input will trigger "Please try again". 
7. Utilize reset button below login form to clear the data within. 
8. Click the "Donut Menu" button to navigate to the donutMenu.html file.
9. Open "payment.html" in browser or utilize navigation header in donutMenu.html>Payment. 
10. Enter payment details in the form boxes. Card Number: 123456789 Zip Code: 90210 will trigger "Payment successful!". Any other input will trigger "Please try again". 
11. Utilize reset button below payment form to clear the data within. 
12. Navigate to login.html or donutMenu.html via the navigation header.  

## Usage
- Browse the menu and add donuts to your cart
- Navigate between pages using the navigation headers on payment.html and donutMenu.html or the "Donut Menu" button in login.html
- Access your shopping cart items and total by clicking the shopping cart button on donutMenu.html
- Enter your login information and payment information (one correct combination for each) to ensure secure user login. 

## Technologies Used
- HTML
- Tailwind CSS (via CDN)
- Inline CSS
- JavaScript (ES6+)
- JSON files and AJAX call to JSON database

## Project Structure
- login.html (login page)
- donutMenu.html (donut menu page)
- payment.html (payment page)
- donuts.json (array of donut objects)
- local jpg files within project folder that populate within json file

## Credits/Acknowledgements
- Project inspired by module one practice exercises
- Guidance and inspiration provided by Alex Demichieli
- Tailwind CSS for styling
- Oversight and edits inspired by ChatGPT5/Gen AI






