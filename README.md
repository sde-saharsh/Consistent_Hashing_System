# 🔥 Consistent Hashing System

## 📌 Overview
**Consistent Hashing System** is a distributed-system simulation project that implements the **Consistent Hashing Algorithm**, widely used in **CDNs, load balancers, distributed caches (Redis/Memcached), and scalable databases**.  
It efficiently distributes keys across multiple servers while ensuring **minimal key remapping** when servers are added or removed.

---

## 🎯 Features
- ✅ Consistent Hashing based key distribution
- ✅ Hash Ring implementation
- ✅ Dynamic Server Add/Remove
- ✅ Minimal key re-distribution
- ✅ Virtual Nodes (VNodes) support for load balancing
- ✅ Key-to-server mapping simulation
- ✅ API support for testing

---

## 🧠 How It Works
- Servers are placed on a **circular hash ring** using a hash function.
- Keys are also hashed and placed on the same ring.
- Each key is assigned to the **nearest server in clockwise direction**.
- When a server is removed/added, only a small portion of keys shift, improving scalability.

---

## ⚙️ Tech Stack
- **Backend:** Node.js, Express.js  
- **Hashing:** SHA-256 / MD5  
- **Storage:** In-memory Map (optional Redis)  
- **Testing:** Postman  

---

## 📂 Project Structure
