# 📦 E-commerce MongoDB Dataset Setup

This repository contains dataset files for an e-commerce database.

Follow the steps below to import the data into your MongoDB database.

---

## 🚀 Setup Instructions

### 1. Create Database

Open your MongoDB shell or MongoDB Compass and run:

```
use ecommerce
```

---

## 📥 Import Datasets

### 👤 Customers Collection

Run the following:

```
db.Customers.insertMany(
  // Copy the entire JSON data from Customer-dataset.json and paste here
)
```

---

### 📦 Orders Collection

Run the following:

```
db.Orders.insertMany(
  // Copy the entire JSON data from OrdersCollection.json and paste here
)
```

---

### 🛍️ Products Collection

Run the following:

```
db.Products.insertMany(
  // Copy the entire JSON data from Products-dataset.json and paste here
)
```

---

### ⭐ Reviews Collection

Run the following:

```
db.Reviews.insertMany(
  // Copy the entire JSON data from Reviews-dataset.json and paste here
)
```

---

## ✅ Final Step

After inserting all datasets, verify:

```
show collections
```

You should see:

* Customers
* Orders
* Products
* Reviews

---

## 💡 Notes

* Make sure JSON data is in array format `[ {...}, {...} ]`
* Paste the full dataset inside `insertMany()`
* Run each query separately

---

## 🎯 You're Done!

Your **ecommerce database** is now ready to use 🚀
