# 🔐 Cryptography & Blockchain Fundamentals – Menu-Driven App

A Python-based console application demonstrating core cryptography concepts:

✔ SHA-256 Hashing
✔ Digital Signature (RSA)
✔ Vehicle Registration & Retrieval System

This project is part of the **Cryptography & Blockchain Fundamentals Assignment**.

## 🎯 Objective

The app allows users to:

### 🧩 1. SHA-256 Hashing

* Input any message
* Generate and display its **SHA-256 hash**

### ✍️ 2. Digital Signature (RSA)

* Generate a **public–private key pair**
* Enter a message
* Sign it using the **private key**
* Verify the signature using the **public key**

### 🚗 3. Vehicle Registration System

* Register a vehicle
* Retrieve vehicle info by number plate
* Prevent duplicate number plates
* Store: `number_plate`, `owner_name`, `model`

### 🧭 Bonus

The entire application is **menu-driven**, looping until the user chooses Exit.


## 📌 Menu Preview

```
========== CRYPTOGRAPHY & BLOCKCHAIN APP ==========
1️⃣  Generate SHA-256 Hash
2️⃣  Create & Verify Digital Signature
3️⃣  Register Vehicle
4️⃣  Retrieve Vehicle Details
5️⃣  Exit
===================================================
```

---

## 🛠 Features Explained

### 🔒 **1. SHA-256 Hash Generator**

* Takes user message
* Uses Python’s `hashlib`
* Generates a secure SHA-256 hash

### ✍️ **2. Digital Signature (RSA)**

Steps:

1. Generate 512-bit RSA public/private key pair
2. User enters a message
3. App signs the message using **private_key**
4. Verifies using **public_key**
5. Displays whether signature is **valid**

Uses the Python `rsa` library.

### 🚗 **3. Vehicle Registration System**

Stored in a Python dictionary:

```python
vehicles = {
    "NUMBER_PLATE": {"owner": "...", "model": "..."}
}
```

* Prevents duplicates
* Retrieves vehicle details in O(1) lookup
* Shows error if number plate doesn’t exist

---

## 🧪 Example Output

### SHA-256

```
Enter message to hash: hello
SHA-256 Hash:
2cf24dba5fb0a....
```

### Vehicle Registration

```
Enter vehicle number plate: MH12AB1234
Enter owner name: Rahul
Enter vehicle model: Honda City
Vehicle registered successfully!
```

### Vehicle Retrieval

```
Enter number plate: MH12AB1234
Owner: Rahul
Model: Honda City
```

---

## 📘 Learning Outcomes

✔ Understanding SHA-256 hashing
✔ Implementing RSA digital signatures
✔ Public key & private key authentication
✔ Python dictionaries for data storage
✔ Menu-driven program design
✔ Real-world use of cryptography concepts


## 👨‍💻 Author:-Sagar Singh
Cryptography & Blockchain Fundamentals – Python Assignment

