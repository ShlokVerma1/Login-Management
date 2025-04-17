# 👤 User Management System – C++

This is a simple **User Management Console Application** written in **C++**, which allows users to register, log in, display all users, search for a specific user, and delete users.

---

## 📌 Features

- 🔐 **User Registration**
- ✅ **User Login**
- 📋 **View Registered Users**
- 🔍 **Search User by Username**
- ❌ **Delete a User**
- 🧼 Simple Menu-Driven CLI

---

## 🧰 Technologies Used

- C++
- Standard Template Library (`<vector>`, `<string>`)
- Object-Oriented Programming (OOP)

---

## 🧠 How It Works

1. The application runs in a loop until the user exits.
2. A class `User` stores each user's username and password.
3. A class `UserManager` handles:
   - Registration
   - Login
   - Displaying users
   - Searching
   - Deleting users
4. All user data is stored in memory using a vector (no file/database).

---

## 📂 Folder Structure

```
/UserManagementSystem
│
├── user_management.cpp    # Main C++ source code
└── README.md              # Project documentation
```

---

## ⚙️ How to Run

### 🧱 Prerequisites

- C++ compiler (e.g., `g++`, `clang++`)

### 🚀 Steps

```bash
# Step 1: Compile
g++ user_management.cpp -o user_mgmt

# Step 2: Run
./user_mgmt
```

---

## 🧪 Example Menu

```
1. Register User
2. Login
3. Show User List
4. Search User
5. Delete User
6. Exit
Enter Your Selection: 
```
---

## 📌 Limitations

- Data is not persistent (resets after every run).
- Passwords are stored in plain text.
- No advanced input validation.

---

## 🔧 Future Improvements

- Add file or database support for persistent storage.
- Encrypt or hash passwords.
- Add email or mobile validation.

---

## 📜 License

This project is open-source and available under the MIT License.
