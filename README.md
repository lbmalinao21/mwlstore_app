MWL Store - E-commerce UI Project
Student Name & ID: Frederico Warde [2021-2297740]
  Lj Malinao [2023-2110278]
                                  Hannah Leocario [2023-2110528]
PROJECT DESCRIPTION
MWL Store is a modern e-commerce mobile application UI built using Flutter. This project features a sleek and user-friendly interface for browsing and purchasing products. The store specializes in fashion and lifestyle items such as bags, shoes, clothes, pots, shorts, and pants. The overall theme focuses on simplicity, modern design aesthetics, and ease of navigation, providing a seamless shopping experience.

 Implemented Features
 Screens
Screen Name
Purpose
Key UI Elements
Splash Screen
Briefly displays the app logo before navigating to the home screen.
Large centered logo, violet background.
Home Screen
Displays product categories and a grid of product items.
Category filter chips, product grid cards, cart icon on AppBar.
Product Detail Screen
Shows detailed information about a selected product.
Product image, name, price, and 'Add to Cart' button.
Cart Screen
Lists all products added to the cart and displays the total price.
Product list with images, total amount, and 'Proceed to Checkout' button.
Checkout Screen
Collects user information and payment methods before placing an order.
Form fields for name, address, payment method radio buttons, 'Place Order' button.
Order Confirmation Screen
Confirms successful order placement with a thank you message.


Success icon, confirmation text, 'Back to Home' button.

Additional UI Features
Category Filtering: Filter products by selecting a category chip.


Snackbars for Cart Addition: Confirmation messages when adding products to the cart.


Navigation Routes: Smooth transitions between screens.


Responsive Grid Layout for product listing.


Custom Widgets: Reusable ProductCard and CategoryFilter components.


Unique Design Choices & Creativity
 Niche & Concept
The store targets young adults and casual shoppers looking for affordable yet stylish fashion and lifestyle products. The product mix is designed to appeal to modern minimalists.
Color Palette
Primary Color: Teal (#008080) – symbolizes trust, balance, and calmness.


Accent Colors: White and light grey for a clean and modern look.


 Typography & Iconography
Typography: Default Flutter fonts with emphasis on bold headings and readable body text.


Icons: Material icons for cart, checkmarks, and navigation, ensuring consistency and familiarity.



 Custom Widgets
CategoryFilter Widget: A horizontally scrollable chip selector for product categories.


ProductCard Widget: Interactive card displaying product image and details with tap navigation.


Screenshots 
Home Screen (Product Grid)
![image](https://github.com/user-attachments/assets/4978e6a7-7745-4af0-9c61-e6a27358f6d7)




Product Detail Screen








Cart Screen








Checkout Form






Order Confirmation








Challenges Faced & Solutions
1. State Management for Cart Functionality
Challenge: Managing cart items and ensuring real-time updates across screens.


Solution: Implemented a simple singleton-like CartManager class to hold and manage cart data. Used setState to trigger UI updates.


2. Passing Data Between Screens
Challenge: Efficiently passing product data to the Product Detail screen.


Solution: Used Flutter's Navigator.pushNamed with arguments to pass product objects cleanly to detail pages.



 Conclusion
The MWL Store UI Project successfully demonstrates a fully functional e-commerce front-end interface using Flutter, focusing on clean UI/UX design principles, modular components, and efficient navigation flow.

Project Overview

MWL Store is a mobile e-commerce application designed using Flutter and Dart. The focus of this project is to demonstrate a solid understanding of Flutter UI/UX design principles by creating a visually appealing and intuitive front-end for a niche-based shopping platform. This app does not rely on any backend and uses mock data for demonstration.

🌟 Objective and Purpose

To apply knowledge of Flutter widgets, layout, and navigation.

To design an attractive and user-friendly e-commerce UI.

To simulate basic e-commerce functionalities such as browsing, cart management, and checkout.

To demonstrate creativity and originality through design, layout, and app theme.

✅ Requirements Met

Feature

Description

✅ Splash Screen

Simple branded intro screen

✅ Home/Product Listing

Grid layout of products with images, price, and name

✅ Product Details

Detailed view of selected product with Add to Cart

✅ Cart Screen

Displays items in the cart, editable quantity, and total

✅ Checkout

Multi-step UI with address, payment selection, and order summary

✅ Order Confirmation

Confirmation page after placing an order

✅ Navigation

Implemented using Navigator and routes

🗂 App Screens and Functions

🔹 Splash Screen

A minimal splash screen displaying app branding.

🏠 Home Screen



Displays a grid of products.

Tapping a product opens the detail screen.

AppBar includes a Cart icon for quick access.

Products are grouped into the following categories:

Bags

Leather Handbag

Canvas Tote

Travel Duffel

Shoes

Running Sneakers

Leather Boots

Flip Flops

Clothes

Linen Shirt

Casual Dress

Denim Jacket

Pots

Handmade Mug

Clay Pot

Ceramic Vase

Shorts

Cotton Shorts

Athletic Shorts

Jean Shorts

Pants

Chinos

Joggers

Formal Trousers

📄 Product Detail Screen



Large product image, name, price, description.

Includes an "Add to Cart" button.

🛒 Cart Screen



Lists items added to the cart.

Allows quantity adjustments.

Displays subtotal and total.

Proceed to Checkout button.

💳 Checkout



Shipping form: Name, Address, Zip, City.

Payment Method UI: Card/PayPal (mock).

Order Summary before placing the order.

✅ Order Confirmation



Simple message confirming order placement.

🧠 Learning Highlights

Throughout this project, we learned how to:

Use Flutter widgets effectively to build responsive and reusable UI components.

Implement navigation between screens using named routes.

Manage mock data and pass it between widgets.

Apply UI/UX best practices including spacing, typography, and consistency.

Build a cohesive theme based on a unique niche (e.g., artisan crafts).

Structure a Flutter project with maintainable and modular code.

Incorporate visual storytelling through custom color palettes, icons, and animations.

Collaborate and manage source code using GitHub and version control best practices.
