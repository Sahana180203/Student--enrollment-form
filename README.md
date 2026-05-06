# 🎓 Student Enrollment Form - SCHOOL-DB

A simple and responsive Student Enrollment Form web application built using HTML, CSS, JavaScript, and JSONPowerDB (JPDB).  
This project allows users to add, search, update, and view student records efficiently.

---

## 🚀 Features

- 🔍 Search student records using Roll Number
- ➕ Add new student records
- ✏️ Update existing student details
- 📋 Display all student records in table format
- ✅ Form validation
- 🔄 Reset form functionality
- 🎨 Responsive and clean UI
- ⚡ Fast database operations using JSONPowerDB

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- JSONPowerDB (JPDB)
- Fetch API

---

## 📂 Project Structure

project-folder/
│
├── index.html
└── README.md

---

## 🗄️ Database Details

| Property | Value |
|----------|-------|
| Database Name | SCHOOL-DB |
| Relation/Table | STUDENT-TABLE |
| Primary Key | Roll-No |

---

## 📸 Workflow

1. Enter Roll Number
2. Click "Look Up"
3. If record exists:
   - Details are loaded
   - User can update the record
4. If record does not exist:
   - User can enter new details
   - Save the record
5. Stored records are displayed in the table section

---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository

git clone https://github.com/your-username/student-enrollment-form.git

### 2️⃣ Open Project

Open the project folder in VS Code or any code editor.

### 3️⃣ Run Application

Open `index.html` in your browser.

---

## 🔑 JSONPowerDB Setup

1. Create account in JSONPowerDB
2. Create Database: `SCHOOL-DB`
3. Create Relation/Table: `STUDENT-TABLE`
4. Replace your token in code:

var TOKEN = "YOUR_TOKEN_HERE";

---

## 📋 Form Fields

- Roll Number
- Full Name
- Class
- Birth Date
- Enrollment Date
- Address

---

## ✅ Validation Features

- Prevents empty field submission
- Checks existing records before insert/update
- Highlights invalid fields

---

## 🌟 Future Enhancements

- Delete Record Feature
- Login Authentication
- Export Data to Excel/PDF
- Search Filters
- Improved Mobile UI

---

## 👨‍💻 Author

Developed by SAHANA SIDRAM HIREMATH

---

## 📄 License

This project is developed for educational and learning purposes.
