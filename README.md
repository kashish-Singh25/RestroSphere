## Deployment

The application is deployed using:

- Frontend : Render
- Backend : Render
- Database : MongoDB Atlas

### Live Links

- Frontend : https://restrosphere-1.onrender.com
- Backend API : https://restrosphere.onrender.com/
  
# RestroSphere

RestroSphere is a full-stack, AI-powered restaurant management platform designed to help restaurants manage their digital presence, daily operations, staff, customers, orders, reservations, inventory, and business insights from a single platform.

It follows a SaaS-based model where restaurant owners can onboard their restaurant, manage their operations through role-based dashboards, and provide customers with a dedicated restaurant website.

---

## Overview

Traditional restaurants often rely on multiple systems for managing orders, tables, reservations, inventory, employees, customer interactions, analytics, and their online presence.

RestroSphere brings these operations together into one centralized platform.

The platform supports:

- Restaurant owners
- Managers
- Kitchen staff
- Waiters
- Customers

Each role receives a dedicated interface and permissions based on its responsibilities.

---

## Key Features

### Restaurant Management

Restaurant owners can manage their complete restaurant profile and operational settings, including:

- Restaurant name and branding
- Restaurant logo
- Restaurant type
- Contact information
- Address
- Opening and closing hours
- Order availability
- Reservation availability
- Notification preferences
- Restaurant activation status

---

### Restaurant Website

Each restaurant can have its own dedicated public website using a restaurant-specific URL.

The website supports:

- Restaurant branding
- Restaurant logo
- Home section
- Digital menu
- About section
- Contact section
- Customer authentication
- Restaurant-specific content
- Restaurant-specific customer experience

This allows every restaurant onboarded to RestroSphere to maintain its own digital presence.

---

### Digital Menu

Restaurants can manage their menu through the platform.

Features include:

- Menu item management
- Categories
- Item pricing
- Item descriptions
- Vegetarian/non-vegetarian classification
- Availability management
- Ratings
- Restaurant-specific menu data
- Customer-facing digital menu

---

### Order Management

RestroSphere provides end-to-end order management.

Customers can:

- Browse available menu items
- Add items to cart
- Update quantities
- Select a table
- Place orders
- View previous orders
- Track order status

Restaurant staff can manage orders through their respective dashboards.

Supported order statuses include:

- Pending
- Preparing
- Ready
- Completed
- Cancelled

---

### Table Management

Restaurants can manage their tables and availability.

Features include:

- Table management
- Table numbers
- Table capacity
- Available tables
- Occupied tables
- Table status tracking
- Customer table selection
- Reservation-linked tables

Customer table availability is synchronized with restaurant-side table management.

---

### Reservation Management

Customers can request table reservations by selecting:

- Table
- Date
- Time
- Number of guests
- Additional notes

Restaurant staff can manage reservation requests and update their status.

Supported reservation statuses include:

- Pending
- Confirmed
- Cancelled
- Completed

---

## Role-Based Dashboards

RestroSphere provides dedicated dashboards for different users.

### Restaurant Owner Dashboard

The owner has access to the complete restaurant management system.

Owner modules include:

- Overview
- Orders
- Menu
- Tables
- Reservations
- Customers
- Employees
- Inventory
- Analytics
- Reports
- Notifications
- Settings

Owners can monitor restaurant activity, manage operations, and access business insights.

---

### Manager Dashboard

The manager dashboard focuses on restaurant operations and performance.

Features include:

- Operational overview
- Order monitoring
- Order status management
- Reservation management
- Table monitoring
- Inventory alerts
- Customer information
- Menu-related operations
- Reports
- Revenue and performance insights
- Notifications
- Search and filtering

The dashboard also provides operational statistics such as pending, preparing, and ready orders, table availability, reservations, and inventory alerts.

---

### Kitchen Dashboard

The Kitchen Dashboard is designed for kitchen staff to manage incoming orders.

Features include:

- Pending orders
- Preparing orders
- Ready orders
- Completed orders
- Cancelled orders
- Order search
- Status filtering
- Customer information
- Table information
- Order item details
- Kitchen notes
- Order priority detection
- Delay alerts
- Real-time-style periodic data refresh
- Kitchen notifications

Kitchen staff can move orders through the preparation workflow:

`Pending → Preparing → Ready → Completed`

Orders can also be cancelled when required.

---

### Waiter Dashboard

The Waiter Dashboard helps front-of-house staff manage active restaurant orders and tables.

Features include:

- Restaurant-specific branding
- Active order management
- Table information
- Customer information
- Order status updates
- Payment status updates
- Order search
- Order statistics
- Automatic data refresh
- Notifications

---

### Customer Dashboard

The customer dashboard provides a complete restaurant ordering and engagement experience.

Customers can:

- Browse the live restaurant menu
- Search and filter dishes
- Add items to cart
- Manage cart quantities
- Place orders
- Select tables
- View order history
- Track order status
- Book reservations
- View available tables
- Manage favorite dishes
- Submit reviews and ratings
- Delete their reviews
- Receive order notifications
- Receive reservation notifications

---

## RestroSphere AI

RestroSphere includes an AI-powered customer assistant.

The AI assistant can work with the restaurant's live menu and recent customer orders.

Customers can ask questions such as:

- What should I order?
- Suggest vegetarian dishes
- Recommend dishes within a specific budget
- Recommend drinks
- What should I order for two people?
- What is the status of my recent order?

The system also provides local recommendation fallback logic based on:

- Dietary preference
- Budget
- Category
- Dish availability
- Ratings

The backend AI assistant uses Google's Gemini API.

---

## Analytics

RestroSphere provides restaurant analytics to help owners and managers understand business performance.

Analytics can include:

- Revenue
- Orders
- Sales performance
- Best-selling dishes
- Peak periods
- Menu performance
- Operational statistics

The platform uses dashboard-based visualizations for business insights.

---

## Reports

The reporting system allows restaurant management to analyze operational performance over different time ranges.

Supported reporting ranges include:

- Today
- Last 7 days
- Last 30 days

Reports can provide information such as:

- Total orders
- Revenue
- Sales performance
- Menu performance
- Operational metrics

---

## Inventory Management

The inventory module helps restaurants monitor stock levels.

Features include:

- Inventory management
- Stock monitoring
- Low-stock detection
- Out-of-stock detection
- Inventory alerts
- Inventory statistics

Owners and managers can use inventory information to identify items that require attention.

---

## Employee Management

Restaurant owners can manage their restaurant staff through the employee management module.

The platform supports role-based restaurant staff including:

- Manager
- Kitchen Staff
- Waiter

Employee updates can also be included in restaurant notifications.

---

## Notifications

RestroSphere provides notifications for important restaurant events.

Owner notification preferences include:

- New Orders
- Reservations
- Inventory Alerts
- Employee Updates

Kitchen notifications can include:

- New orders
- Preparing orders
- Ready orders
- Completed orders
- Cancelled orders
- Delayed orders
- Urgent kitchen alerts

Customers can receive notifications related to:

- Order received
- Order preparing
- Order ready
- Reservation confirmation

---

## Authentication and Authorization

RestroSphere implements role-based authentication.

Supported roles include:

- Customer
- Restaurant Owner
- Manager
- Kitchen Staff
- Waiter

Authentication-protected routes ensure that users can access only the areas associated with their roles.

The application also includes:

- Login
- Signup
- Role selection
- Protected routes
- Forgot password flow
- Token-based authentication
- Google authentication support

---

## Multi-Restaurant Architecture

RestroSphere is designed as a multi-restaurant SaaS platform.

Each restaurant can have its own:

- Restaurant profile
- Restaurant URL
- Branding
- Logo
- Menu
- Tables
- Reservations
- Orders
- Customers
- Employees
- Inventory
- Analytics
- Settings

Restaurant-specific URLs allow customers and staff to interact with the correct restaurant context.

---

## Subscription-Based SaaS Model

RestroSphere is designed around a subscription-based business model.

Restaurant owners can subscribe to the platform and use RestroSphere to manage their restaurant operations.

The subscription system supports:

- Subscription plans
- Subscription status
- Start date
- End date
- Payment tracking
- Razorpay integration

The platform can therefore be extended with multiple subscription tiers for different restaurant requirements.

---

## Payment Integration

Razorpay is integrated for subscription payments.

The system supports tracking of:

- Razorpay order ID
- Payment ID
- Payment signature
- Subscription status
- Subscription plan
- Subscription duration

Payment credentials and secret keys are kept outside the public repository using environment variables.

---

## Local Development Setup

Follow these steps to run RestroSphere locally.

### Prerequisites

Make sure you have the following installed:

- Node.js and npm
- MongoDB (local installation or MongoDB Atlas)
- Git
- A Google Gemini API key for AI assistant features

### 1. Clone the Repository

```bash
git clone https://github.com/kashish-Singh25/RestroSphere.git
cd RestroSphere
```

### 2. Configure the Backend

```bash
cd server
npm install
```

Create a `.env` file inside the `server` directory and configure the environment variables required by the application, including database connection, authentication, and API credentials.

Use the exact variable names expected by the backend configuration.

Start the backend:

```bash
npm run dev
```

### 3. Configure the Frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

Vite will provide a local development URL in the terminal.

### 4. Access the Application

Open the local frontend URL provided by Vite in your browser.

Make sure the backend server and MongoDB connection are running correctly.

### Important Notes

- Never upload `.env` files or expose API keys.
- Configure MongoDB credentials before starting the backend.
- Gemini and Razorpay credentials are required for their respective integrations.
- Use separate terminals for frontend and backend development.

## Auhtor
Niharika ( IGDTUW - B.Tech IT )

## Project Architecture

```text
RestroSphere/
│
├── client/
│   ├── public/
│   └── src/
│       ├── api/
│       ├── assets/
│       ├── components/
│       ├── context/
│       ├── data/
│       ├── pages/
│       ├── routes/
│       ├── services/
│       └── App.tsx
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── seed/
│   ├── utils/
│   ├── app.js
│   └── server.js
│
├── package.json
├── package-lock.json
└── .gitignore
