# 🛒 SauceDemo E-Commerce Automation - 

## 📌 Project Overview

This project is an automation testing assignment developed using
**Selenium WebDriver, Java, and TestNG**.

The project automates the basic e-commerce workflow on the
**SauceDemo (Swag Labs)** website.

## 🛠️ Technologies Used

- Java
- Selenium WebDriver
- TestNG
- ChromeDriver
- Maven
- Eclipse IDE

## 🧪 Test Scenarios

The following test scenarios are automated:

### 1. Login Test
- Open SauceDemo website
- Enter username and password
- Click Login
- Verify successful login

### 2. Product Filter Test
- Apply the product sorting filter
- Select **Price (low to high)**
- Verify that the filter is applied

### 3. Add Product to Cart
- Select the Sauce Labs Backpack
- Add the product to the shopping cart
- Open the cart

### 4. Checkout Test
- Click Checkout
- Enter first name
- Enter last name
- Enter postal code
- Continue with checkout
- Complete the order

### 5. Order Confirmation
- Verify the successful order confirmation message:
  
  **"Thank you for your order!"**

## 🔄 Automation Flow

```text
Login
  ↓
Product Filter
  ↓
Add Product to Cart
  ↓
Open Cart
  ↓
Checkout
  ↓
Enter Customer Information
  ↓
Complete Order
  ↓
Verify Order Confirmation
