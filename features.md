# ShopperDapper - MVP Features (20 Days)

> A simple platform that helps Instagram sellers sell products without DM conversations.

---

## What this project does

ShopperDapper solves a very common problem:

People see products on Instagram → they DM → wait for reply → lose interest.

This app removes that friction by letting users:
 Click a link → View product → Buy instantly  

---

## What will be built (MVP Scope)

This is a **minimal but working version** of the idea, focused on core functionality.

---

## Pages


###  Home Page
- Simple landing page
- App introduction (“No DMs. Just Buy.”)
- Basic product categories
- List of stores 

### ️ Product Page
- Product image
- Price
- Description
- Product condition (New / First Copy / Thrift)
- Seller name
- **Buy Now button**

---

### Seller Store Page
`/store/:username`
- Shows all products from one seller
- Basic store identity (name / Instagram handle)

---

### Authentication
- Register (Buyer / Seller)
- Login


---

### Add Product (Seller)
- Product name
- Price
- Image upload (Cloudinary)
- Description
- Condition selection

---

### Orders Page

**Seller:**
- View incoming orders
- See buyer details

**Buyer:**
- View past orders

---

###  Checkout Page
- Enter:
  - Name
  - Phone
  - Address
- Razorpay payment (test mode)
- Place order

---

### Order Confirmation Page
- Order success message
- Basic order details

---

## Core Features

---

###  Authentication
- Email + password login
- JWT based session handling

---

### Simple cart aside not full page
Flow:
Instagram → Product Page →   Add to cart→ Order

---

###  Product Management
- Sellers can:
  - Add product
  - Edit product
  - Delete product

---

###  Payment Integration
- Razorpay (test mode)
- Basic payment success handling

---

###  Order Management
- Store order details
- Connect buyer and seller
- Simple status:
  - Placed
  - Confirmed


---

### Search (Basic)
- Search by:
  - Product name
  - Seller username/storename

---

## Not Included (to save time)

These are intentionally skipped to complete in 20 days:

- No cart system  
- No reviews & ratings  
- No advanced filters  
- No analytics dashboard  
- only simple admin panel  
- No notifications  

---

##  Focus of this MVP

This project focuses only on:

- Removing DM-based buying  
- Making Instagram selling faster  
- Showing a complete purchase flow  

---

##  Final Outcome

A working product where:

- Seller adds product  
- Buyer clicks link  
- Buyer pays  
- Seller receives order  

---

## Why this approach?

This MVP is designed to:
- Be completed within 20 days  
- Stay simple and practical  
- Demonstrate real-world problem solving  

---

**ShopperDapper — No DMs. Just Buy.**