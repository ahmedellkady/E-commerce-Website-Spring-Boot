# E-Commerce Web Application

Welcome to the **E-Commerce Web Application**! This is a full-stack web application built using **Spring Boot** for the backend and **HTML/CSS/JavaScript** for the frontend. The application provides features like user authentication, product management, order processing, and more.

---

## **Features**

### **1. User Authentication**
- **Registration**: Users can register with a name, email, password, and phone number. Validation is performed for email, name, phone, and password.
- **Login**: Users can log in using their credentials. JWT tokens are used for authentication.
- **Logout**: Users can log out, which invalidates their session.
- **Role-Based Access**: Users have roles (`USER` or `ADMIN`). Admins have access to additional features like managing users, products, and orders.

### **2. Product Management**
- **Browse Products**: Users can view a list of products with details like brand, description, price, and rating.
- **Product Details**: Users can view detailed information about a specific product, including images.
- **Add to Cart**: Users can add products to their shopping cart with selected size and quantity.
- **Wishlist**: Users can add products to their wishlist for future purchase.

### **3. Shopping Cart**
- **View Cart**: Users can view the items in their cart, including product details, quantity, and subtotal.
- **Remove Items**: Users can remove items from the cart.
- **Apply Coupons**: Users can apply discount coupons (e.g., `Abdelaziz20` for 20% off).
- **Proceed to Checkout**: Users can proceed to the checkout page to place an order.

### **4. Order Management**
- **Place Order**: Users can place orders by providing their address, payment method, and additional information.
- **Order History**: Users can view their past orders.
- **Order Status**: Admins can update the status of orders (e.g., "Out for Delivery").
- **Email Notifications**: Users receive an email confirmation after placing an order.

### **5. Admin Dashboard**
- **Manage Users**: Admins can view, update, and delete user accounts.
- **Manage Products**: Admins can view and manage products (add, update, delete).
- **Manage Orders**: Admins can view and update orders, including changing the order status.
- **View Statistics**: Admins can view statistics like total users, total products, total orders, and total earnings.

### **6. Wishlist**
- **Add to Wishlist**: Users can add products to their wishlist.
- **Remove from Wishlist**: Users can remove products from their wishlist.
- **View Wishlist**: Users can view their saved products.

### **7. Frontend Features**
- **Responsive Design**: The frontend is designed to work on different screen sizes.
- **Dynamic Content**: JavaScript is used to dynamically fetch and display data from the backend (e.g., products, orders, users).
- **Interactive UI**: Features like modals for editing, deleting, and updating data are implemented.
---

## **Technologies Used**
- **Frontend**: HTML, CSS, JavaScript (Vanilla JS).
- **Backend**: Spring Boot, Spring Security, JWT Authentication, Hibernate, MySQL.
- **Database**: MySQL.
- **Other Tools**: Maven, Git, Postman (for API testing).

---

## **Project Structure**
```
project-root/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/website/ecommerce/  # All Java packages (model, service, dto, repo, controller, etc.)
│   │   ├── resources/
│   │   │   ├── static/                 # Static assets (HTML, CSS, JS, images)
│   │   │   │   ├── assets/             # Contains img, js, css folders
│   │   │   │   │   ├── img/            # Images
│   │   │   │   │   ├── js/             # JavaScript files
│   │   │   │   │   └── css/            # CSS files
│   │   │   │   └── index.html          # HTML files
│   │   │   └── application.properties  # Spring Boot configuration
│   └── test/                           # Test files
└── pom.xml                             # Maven build file 
```

---

## **Screenshots**

### Register & Login
| Register | Invalid Register | Login |
|----------|------------------|-------|
| ![Register](./e-commerce/registerPage.png) | ![Invalid Register](./e-commerce/InvalidRegister.png) | ![Login](./e-commerce/loginPage.png) |

---

### Homepage
| Homepage |
|----------|
| ![Homepage](./e-commerce/HomePage.png) |

---

### Products Pages
| Products Page | Product Page | Sale Page |
|---------------|--------------|----------|
| ![Products Page](./e-commerce/ShopPage.png) | ![Product Page](./e-commerce/SingleProduct.png) | ![Sale Page](./e-commerce/SalePage.png) |

---

### Wishlist
| Empty Wishlist | Full Wishlist |
|----------------|---------------|
| ![Wishlist](./e-commerce/EmptyWishlist.png) | ![Wishlist](./e-commerce/FullWishlist.png) |

---

### Shopping Cart
| Empty Cart | Full Cart |
|------------|-----------|
| ![Shopping Cart](./e-commerce/EmptyCart.png) | ![Shopping Cart](./e-commerce/FullCart.png) |

---

### Checkout Page
| Checkout Page |
|---------------|
| ![Checkout Page](./e-commerce/checkout.png) |

---

### Order Confirmation Email
| Email Sent After Order |
|------------------------|
| ![Order Confirmation Email](./e-commerce/OrderConfirmationEmail.png) |

### Account Details
| Account Details | Edit Account Details |
|-----------------|----------------------|
| ![Account Details](./e-commerce/AccountDetails.png) | ![Edit Account Details](./e-commerce/AccountDetails2.png) |

---

### Admin

| Admin Dashboard |
|-----------------|
| ![Admin Dashboard](./e-commerce/AdminDashboard.png) |

| All Orders Table |
|------------------|
| ![All Orders](./e-commerce/AllOrders.png) | 
| ![Edit Status](./e-commerce/AllOrders1.png) | 
| ![Status Updated](./e-commerce/AllOrders2.png) |

| All Users Table |
|-----------------|
| ![All Users](./e-commerce/AllUsers.png) | 

---

### Responsive Design
| Responsive Handling | Responsive Homepage | Responsive Wishlist |
|---------------------|---------------------|---------------------|
| ![Responsive](./e-commerce/ResponsiveHandling.png) | ![Responsive](./e-commerce/ResponsiveHomePage.png) | ![Responsive](./e-commerce/ResponsiveWishlist.png) |

| Responsive Account Details | Cart & Wishlist |
|----------------------------|-----------------|
| ![Responsive](./e-commerce/ResponsiveAccountDetails.png) | ![Responsive](./e-commerce/CartWishlist.png) |

---
