# MWL Store – E-commerce UI Project

**Student Names & IDs**  
- Frederico Warde – `2021-2297740`  
- Lj Malinao – `2023-2110278`  
- Hannah Leocario – `2023-2110528`

---

## 📱 Project Description

**MWL Store** is a modern e-commerce mobile application UI built using **Flutter**. This project features a sleek, user-friendly interface for browsing and purchasing fashion and lifestyle items such as:

- Bags
- Shoes
- Clothes
- Pots
- Shorts
- Pants

The design emphasizes simplicity, modern aesthetics, and seamless navigation to ensure a smooth shopping experience.

---

## 🧩 Implemented Features

### 🔹 Screens Overview

| Screen Name             | Purpose                                                      | Key UI Elements                                              |
|-------------------------|--------------------------------------------------------------|---------------------------------------------------------------|
| **Splash Screen**       | Displays logo briefly before navigating to home screen       | Centered logo, violet background                              |
| **Home Screen**         | Displays product categories and items                        | Category filter chips, product grid, cart icon                |
| **Product Detail**      | Shows product info in detail                                 | Product image, name, price, 'Add to Cart' button              |
| **Cart Screen**         | Shows added items and total cost                             | List of products, total price, 'Proceed to Checkout' button   |
| **Checkout Screen**     | Gathers user info and payment method                         | Name, address, payment options, 'Place Order' button          |
| **Order Confirmation**  | Confirms successful order                                    | Success icon, message, 'Back to Home' button                  |

---

## 🛠️ Additional UI Features

- **Category Filtering:** Horizontally scrollable chips to filter products  
- **Snackbars for Cart Addition:** Quick confirmation when items are added  
- **Smooth Navigation Routes:** Animated transitions between screens  
- **Responsive Grid Layout:** Adapts to various screen sizes  
- **Custom Widgets:**
  - `CategoryFilter` – Scrollable chip selector
  - `ProductCard` – Interactive product tile

---

## 🎨 Design & Creativity

### 🎯 Niche & Concept
Aimed at **young adults** and **casual shoppers** looking for **affordable, stylish** fashion. Appeals to minimalists with a taste for clean design.

### 🎨 Color Palette
- **Primary Color:** Teal `#008080` (trust, calm, balance)  
- **Accent Colors:** White & Light Grey (clean and modern)

### 🔤 Typography & Icons
- **Fonts:** Default Flutter fonts with bold headers and readable body text  
- **Icons:** Material Icons for consistency and intuitive navigation

---

## 📸 Screenshots

### 🏠 Home Screen  
![Home Screen](https://github.com/user-attachments/assets/4fbfdec2-7702-42fb-80d4-93c0b69423d0)

### 📄 Product Detail Screen  
![Product Detail](https://github.com/user-attachments/assets/f1759d71-9210-419e-a456-53763a434232)

### 🛒 Cart Screen  
![Cart Screen](https://github.com/user-attachments/assets/9494e2d5-e76e-4e0b-88ff-68141cbfe834)

### 🧾 Checkout Form  
![Checkout Form](https://github.com/user-attachments/assets/caf88e9e-bea7-4cff-aebd-60499c3b93e1)

### ✅ Order Confirmation  
![Order Confirmation](https://github.com/user-attachments/assets/36243821-0221-4936-b661-7c6a0ecd4e4a)

---

## 🧠 Challenges Faced & Solutions

### 1. State Management for Cart
- **Challenge:** Keeping cart state updated across screens  
- **Solution:** Created a singleton-like `CartManager` class and used `setState()` to trigger UI refresh

### 2. Passing Data Between Screens
- **Challenge:** Efficiently sending product info to the detail screen  
- **Solution:** Utilized `Navigator.pushNamed` with arguments to pass product data cleanly

---

## ✅ Conclusion

The **MWL Store UI Project** showcases a fully functional e-commerce front-end interface using Flutter. With its clean design, reusable components, and intuitive navigation, it serves as a solid foundation for further development into a complete shopping app.

---
