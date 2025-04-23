# 🧠 actix-todo-board

A lightweight in-memory to-do list API built using Rust and [Actix Web](https://actix.rs/).  
Perfect for learning how to build RESTful APIs, manage shared state, and implement CRUD operations with thread-safe concurrency in Rust.

---

## 🚀 Features

- [x] Health check route (`GET /`)
- [x] Get all to-do entries (`GET /todolist/entries`)
- [x] Create new entry (`POST /todolist/entries`)
- [x] Update entry by ID (`PUT /todolist/entries/{id}`)
- [x] Delete entry by ID (`DELETE /todolist/entries/{id}`)
- [x] In-memory shared state via `web::Data` and `Mutex`
- [ ] Add persistence (SQLite/PostgreSQL) 💡
- [ ] User authentication & validation 🔐

---

## 🧱 Tech Stack

- ⚙️ **Rust**
- 🚀 **Actix Web** – web framework
- 🧵 **Mutex + Arc** – for safe shared memory
- 🧩 **Serde** – for JSON serialization

---

## 📦 Getting Started

### 1️⃣ Install Rust

If you don’t have it yet:

```bash
curl https://sh.rustup.rs -sSf | sh
```
