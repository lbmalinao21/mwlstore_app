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
![image](https://github.com/user-attachments/assets/4fbfdec2-7702-42fb-80d4-93c0b69423d0)




Product Detail Screen
![image](https://github.com/user-attachments/assets/f1759d71-9210-419e-a456-53763a434232)








Cart Screen
![image](https://github.com/user-attachments/assets/9494e2d5-e76e-4e0b-88ff-68141cbfe834)








Checkout Form
![image](https://github.com/user-attachments/assets/caf88e9e-bea7-4cff-aebd-60499c3b93e1)






Order Confirmation
![image](https://github.com/user-attachments/assets/36243821-0221-4936-b661-7c6a0ecd4e4a)








Challenges Faced & Solutions
1. State Management for Cart Functionality
Challenge: Managing cart items and ensuring real-time updates across screens.


Solution: Implemented a simple singleton-like CartManager class to hold and manage cart data. Used setState to trigger UI updates.


2. Passing Data Between Screens
Challenge: Efficiently passing product data to the Product Detail screen.


Solution: Used Flutter's Navigator.pushNamed with arguments to pass product objects cleanly to detail pages.



 Conclusion
The MWL Store UI Project successfully demonstrates a fully functional e-commerce front-end interface using Flutter, focusing on clean UI/UX design principles, modular components, and efficient navigation flow.


