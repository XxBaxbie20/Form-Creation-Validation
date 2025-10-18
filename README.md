# Form-Creation-Validation

A simple **User Registration Form** built with **HTML, CSS, and JavaScript**, implementing basic client-side validation to ensure users provide correct input before submitting.

---

## 🧩 Project Overview

This project demonstrates form creation and validation using fundamental web technologies. The form collects a username, email, and password, then validates user inputs in real-time before displaying feedback.

---

## 🧱 Features

- 🧾 Clean and responsive user registration form  
- 🧠 Basic client-side validation (no external libraries)  
- 🎨 Styled with CSS for a modern look  
- 💬 Dynamic feedback messages for errors and success  

---

## ⚙️ Validation Rules

| Field | Validation Criteria | Error Message |
|-------|----------------------|----------------|
| **Username** | Must be at least 3 characters | “Username must be at least 3 characters long.” |
| **Email** | Must include “@” and “.” | “Please enter a valid email address.” |
| **Password** | Must be at least 8 characters | “Password must be at least 8 characters long.” |

---

## 🧠 How It Works

1. The JavaScript script waits for the **DOMContentLoaded** event before running.  
2. When the user submits the form:
   - The form submission is **prevented** from reloading the page.
   - Input values are **trimmed** of whitespace.
   - Each input field is validated based on set rules.
3. If all validations pass, a success message is shown.  
   Otherwise, descriptive error messages appear inside the feedback area.

---

## 📂 Project Structure

Form-Creation-Validation/
│
├── index.html # HTML structure of the form
├── style.css # Styling for the form and feedback
├── script.js # Validation logic using JavaScript
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

---

## 🧑‍💻 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

---

## 📸 Preview

---

## 🏁 Author

  Ernest Bright
 
- 💼 [GitHub](https://github.com/XxBaxbie20)

- 🐦 [Twitter](https://x.com/ernest_brightt)

- 🔗 [LinkedIn](www.linkedin.com/in/bright-ernest)







