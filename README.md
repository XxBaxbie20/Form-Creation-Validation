# Form-Creation-Validation

A simple **User Registration Form** built with **HTML, CSS, and JavaScript**, implementing basic client-side validation and asynchronous data fetching from a public API.
---

## 🧩 Project Overview

This repository demonstrates two core front-end development concepts:

1. **Form Validation** — ensuring users provide the correct input data before submission.
2. **API Data Fetching** — using asynchronous JavaScript to retrieve and display external data dynamically.

---

## 🧱 Features

- ✍️ User registration form with client-side validation  
- 🧠 Basic DOM manipulation and event handling  
- ⚙️ Asynchronous API fetching using `fetch()` and `async/await`  
- 🎨 Clean, modern CSS design  
- 💬 Dynamic success/error feedback messages  

---

## 🧮 1️⃣ User Registration Form Validation

### 🔍 Validation Rules

| Field | Validation Criteria | Error Message |
|-------|----------------------|----------------|
| **Username** | Must be at least 3 characters | “Username must be at least 3 characters long.” |
| **Email** | Must include “@” and “.” | “Please enter a valid email address.” |
| **Password** | Must be at least 8 characters | “Password must be at least 8 characters long.” |

The validation is handled entirely on the **client side** using plain JavaScript.  
Feedback messages are displayed dynamically within the form interface.

---

## 🌐 2️⃣ Fetching and Displaying API Data

### 🧠 Overview
The `fetch-data.html` file demonstrates asynchronous data fetching using the Fetch API from a public endpoint:  
> [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)

### ⚙️ How It Works
1. On page load, the JavaScript function `fetchUserData()` runs automatically.  
2. The function fetches user data asynchronously and parses it as JSON.  
3. Each user’s **name** is displayed in a styled list on the webpage.  
4. Errors (e.g., failed network request) are caught and handled gracefully.

### 🧾 Example Output

User List

- Leanne Graham

- Ervin Howell

- Clementine Bauch

- ...and so on

---

## 📂 Project Structure

Form-Creation-Validation/
│
├── index.html # User Registration Form
├── style.css # Styling for the form
├── script.js # Validation logic
│
├── fetch-data.html # Page for fetching and displaying API data
├── fetch-data.css # Styling for the fetched user list
├── fetch-data.js # Asynchronous JavaScript fetch logic
│
└── README.md # Project documentation

---

## 🚀 Setup and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/XxBaxbie20/Form-Creation-Validation.git

2. Navigate into the project folder:
   ```bash
   cd Form-Creation-Validation

3. Open index.html in your browser to view and test the form.

4. To test the API Fetch Feature, open:
   fetch-data.html

---

## 🧑‍💻 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

---

## 📸 Preview

---

## 🏁 Author

  Ernest Bright
 
- 💼 [GitHub](https://github.com/XxBaxbie20)

- 🐦 [Twitter](https://x.com/ernest_brightt)

- 🔗 [LinkedIn](www.linkedin.com/in/bright-ernest)







