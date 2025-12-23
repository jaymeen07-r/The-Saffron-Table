# 🍽️ The Saffron Table – Restaurant QR Ordering System (Mobile Website)

A **mobile-first restaurant ordering system** for *The Saffron Table*, where customers scan a **QR code** placed on their table to view the menu, place orders, and check their bills.  
Hotel staff, kitchen staff, and admin manage operations through **role-based dashboards** — all accessible via any mobile browser (no app required).

---

### 📌 Project Overview
This project is designed specifically for operations at **The Saffron Table**, supporting real-time digital orders and smart billing.

- 17 tables with QR code stickers  
- 200+ food items and dynamic menu updates  
- Role-based dashboards for staff and admin  
- End-to-end digital ordering and billing workflow  
- Fully responsive mobile-first design  

Customers can place their orders digitally, while food service and payment occur in person.

---

### 👤 User Roles & Access

#### 1️⃣ Admin (Login Required)
**Responsibilities:**
- Manage hotel staff and kitchen staff users  
- Add, edit, or disable menu items and prices  
- View all live and historical orders  
- Access sales reports and manage table status  
- Close bills and toggle food availability  

#### 2️⃣ Hotel Staff (Login Required)
**Responsibilities:**
- Place manual orders for customers  
- Modify or cancel orders before preparation  
- Mark orders as *Served*  
- Generate and close bills  

#### 3️⃣ Kitchen Staff / Chef (Login Required)
**Capabilities:**
- View order queue and item details  
- Update order status:
  - `PLACED → PREPARING`  
  - `PREPARING → READY`  
- Restricted access (cannot change price or cancel orders)  

#### 4️⃣ Customer (No Login Required)
**Functions:**
- Scan QR code at table to view menu  
- Browse categories and place orders  
- Track live order progress  
- View running bill anytime  
- Call staff using an in-app button  
- Optionally verify via mobile number for order history  

---

### 📱 Website Navigation (Bottom Navbar)
- **Home (Menu)**  
- **Your Order**  
- **Bill**  
- **Account**

---

### 🏠 Home (Menu Page)
- Displays all categories with food items  
- Each item shows name, price, and quantity selector  
- Auto-detects table number via QR  
- Smooth mobile scrolling layout  

#### 🍛 Food Categories
**Thali:**
- Gujarati Fix Thali  
- Punjabi Fix Thali  
- Kathiyawadi Fix Thali  
- Gujarati Unlimited Thali  
- Punjabi Unlimited Thali  
- Kathiyawadi Unlimited Thali  

**Main Categories:**  
Sabji, Roti / Bread, Rice, Dal & Kadhi, Starters, Beverages, Combo Items  

**Extras:**  
Papad, Salad, Sweets, Chaas  

---

### 🧾 Your Order Page
- Displays selected items before confirming  
- Adjust quantity or remove items  
- Add customization notes (optional)  
- Track live status updates:
  - **Placed → Preparing → Ready → Served**  
- Edits disabled once order reaches the kitchen  

---

### 💵 Bill Page
- View **live billing details**:
  - Items, quantity, and prices  
  - Food subtotal, GST amount, and total  
- “Call Staff / Request Bill” button  
- Bill locked once finalized by staff  

---

### 📱 Account Page (Mobile Number Based)
- Login with **mobile number + OTP**  
- See order history and previous bills  
- Features:
  - View order history with dates  
  - Reorder previously ordered items  
  - Continue regular order patterns  

---

### 🔄 Order Flow
```
Customer places order
        ↓
Order Status: PLACED
        ↓
Kitchen: PREPARING
        ↓
Kitchen: READY
        ↓
Staff: SERVED
        ↓
Bill Generated
        ↓
Payment & Table Closed
```

---

### 🧠 Key Features Summary
- QR-based table identification  
- Mobile-first responsive design  
- Role-based access (Admin, Staff, Chef, Customer)  
- Real-time order updates  
- Kitchen-only order management view  
- Live GST billing  
- Customer history linked to mobile number  
- No login required for ordering  

---

### 🚀 Future Enhancements
- Online payment gateway integration  
- Multi-language menu support  
- Inventory management  
- Customer feedback & rating system  
- Discount and coupon support  
- Multi-branch management  

---


### 📄 License
This project is intended for real-world restaurant use and **may be modified or extended** as per business requirements.
```

Would you like me to append sections for **installation steps, tech stack, and database schema** at the end so developers can set it up easily?
