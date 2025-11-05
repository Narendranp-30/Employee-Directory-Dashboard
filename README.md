# 🧑‍💼 Employee Directory Dashboard

## 📘 Overview
The **Employee Directory Dashboard** is a simple, interactive web application built using **HTML, CSS, Bootstrap, and JavaScript**.  
It allows users to **add, edit, delete, and view employee records** in a responsive dashboard layout.

---

## 🧭 Project Structure

| File Name | Description |
|------------|-------------|
| `dashboard.html` | Displays all employee details and summary statistics like total count and department-wise count. |
| `addemp.html` | Used to add a new employee with form validation for email and phone number. |
| `editemp.html` | Used to edit an existing employee’s details retrieved from localStorage. |

---

## 🎯 Objective
To design a simple **Employee Management System** that allows managing employee records dynamically in the browser using **Bootstrap UI and JavaScript logic**.

---

## ⚙️ Functional Requirements

### 1️⃣ Dashboard Page (`dashboard.html`)
- Displays total number of employees and department-wise statistics:
  - HR Department  
  - IT Department  
  - Finance Department  
  - Admin Department  
- Shows employee details in **Bootstrap cards** with:
  - Name  
  - Department  
  - Email  
  - Phone  
  - Designation  
  - Joining Date  
- Includes:
  - 🔍 **Search bar** to filter by employee name  
  - 🧩 **Dropdown filter** to view employees by department  
  - ✏️ **Edit** and 🗑️ **Delete** buttons for each record  
- “➕ Add Employee” button redirects to `addemp.html`.

---

### 2️⃣ Add Employee Page (`addemp.html`)
- Contains a form to add new employees.  
- Input fields include:
  - Name  
  - Email (validated for correct format and lowercase letters)  
  - Phone (validated for 10 digits only)  
  - Department (select dropdown)  
  - Designation  
  - Joining Date  
- On submitting:
  - Employee data is saved in **localStorage**.  
  - Redirects automatically to `dashboard.html` showing the updated record.

---

### 3️⃣ Edit Employee Page (`editemp.html`)
- Loads existing employee data using a stored index from **localStorage**.  
- Pre-fills the input fields with the selected employee’s data.  
- On saving:
  - Updates the record in **localStorage**.  
  - Redirects back to `dashboard.html`.

---

## 🧩 Technologies Used
- **HTML5** – Page structure  
- **CSS3 / Bootstrap 5** – Responsive styling and grid layout  
- **JavaScript (ES6)** – Logic for add, edit, delete, and filter features  
- **LocalStorage** – To store and persist employee data  

---

## 🧠 Key Features
✅ Add, Edit, and Delete Employee Records  
✅ Filter by Department and Search by Name  
✅ Live Department Summary Cards  
✅ Form Validation for Email and Phone  
✅ Fully Responsive Layout with Bootstrap  
✅ Data Persistence using LocalStorage  


---

## 🧾 Example Workflow
1. Start from `dashboard.html`.  
2. Click on **➕ Add Employee**.  
3. Fill out the form and submit.  
4. Employee appears as a card on the dashboard.  
5. Click **✏️ Edit** → Modify details → Save → Redirected to dashboard again.  
6. Click **🗑️ Delete** to remove an employee record.

---

## Screenshots
Employee Directory dashboard page

<img width="1895" height="879" alt="image" src="https://github.com/user-attachments/assets/56f58a06-7758-4c44-973b-dd28c3fb0a2c" />


Filter by Department

<img width="1915" height="858" alt="image" src="https://github.com/user-attachments/assets/b5cfa697-5841-4529-853f-eed954846d56" />


Filter by name

<img width="1910" height="883" alt="image" src="https://github.com/user-attachments/assets/a205cb49-49a5-4f52-94c7-9eefd92688e2" />

Add Employee Details page

<img width="1905" height="870" alt="image" src="https://github.com/user-attachments/assets/6cecd87c-df13-4d49-b705-c7242f7b588e" />


Edit Employee Details page

<img width="1905" height="880" alt="image" src="https://github.com/user-attachments/assets/b6bae631-717a-4093-a3e8-2447757ab7c8" />

