# 🗂️ Group 334 - E-commerce Database Assignment

## 📘 Project Overview

This repository contains a peer group assignment for the design of an **E-commerce Database Schema**. The schema was built to handle product catalog data efficiently, supporting variations such as size and color, attributes, and brand details, while remaining scalable and normalized.

## 🔧 Technologies Used

- **MySQL / PostgreSQL (SQL standard)**
- **dbdiagram.io** for ERD generation
- SQL DDL & DML concepts

---

## 📊 Entity Relationship Diagram (ERD)

The ERD below outlines the structure of our e-commerce database:

![Untitled](https://github.com/user-attachments/assets/1eb0b979-879e-4e06-a800-88f8e5684241)

### 📦 Product

- `id`, `name`, `base_price`, `brand_id`, `category_id`

### 🏷️ Brand & Category

- Each product belongs to a **brand** and **category**.

### 🎨 Variants

- **Color** and **Size Option** are stored in separate tables and linked via `product_variation`.

### 📷 Product Images

- Multiple images can be stored for a single product using the `product_image` table.

### 📚 Attributes

- Flexible structure to add features like material, gender, etc.

---

## ▶️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/MuganziJames/group-334-database-assignment.git
   ```

## 🤝 Contributors

- **James Muganzi**
- **Tebogo Ranuga**
- **Joram Kombo**
- **Derrick Olewe**
- **Esther Wanjiku**
- **Samuel Oluoch**
- **Isaac Kabelo**
- **Victor Ayanwale**
- **Velmar Atieno**
