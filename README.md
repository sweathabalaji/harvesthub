# 🥦 Bulk Vegetable/Fruit Order Web Application

A full-stack web application for bulk ordering vegetables and fruits. Buyers can browse products, place orders, and track them. Admins can manage products and orders.

## 🚀 Features

- Product catalog view
- Buyer order form
- Order status tracking
- Admin dashboard for product & order management

## 🧱 Tech Stack

- **Frontend:** Next.js (React.js), Tailwind CSS
- **Backend:** Next.js API routes or Express.js (optional)
- **Database:** PostgreSQL (Neon.tech or Docker)
- **ORM (Optional):** Prisma

## 📦 API Routes

| Route                  | Method | Description                     |
|------------------------|--------|---------------------------------|
| `/api/products`        | GET    | Get all products                |
| `/api/products`        | POST   | Add new product (Admin)         |
| `/api/products/:id`    | PUT    | Edit product (Admin)            |
| `/api/products/:id`    | DELETE | Delete product (Admin)          |
| `/api/orders`          | POST   | Place new order                 |
| `/api/orders/:id`      | GET    | View order details              |
| `/api/orders`          | GET    | View all orders (Admin)         |
| `/api/orders/:id`      | PUT    | Update order status (Admin)     |

## 🛠️ Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/bulk-order-app.git
   cd bulk-order-app
# harvesthub
