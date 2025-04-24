# College-Management-System-Console-Based-
# 🏫 College Management System (Console-Based)

A simple Python-based console application to manage multiple colleges, their students, and teachers. Built using object-oriented programming (OOP) concepts like inheritance and encapsulation.

## 🚀 Features

- Add and manage multiple colleges
- Add students and teachers to specific colleges
- Display student and teacher details by college
- Basic validation to avoid duplicate college IDs
- Fully interactive command-line interface

## 🧠 Concepts Used

- Classes and Inheritance
- Constructor Overriding (`super()`)
- Lists and Objects
- Conditional and Loop Structures
- Encapsulation

## 🏗️ Class Structure

- `person`: Base class for all people (contains `rollno`, `name`)
- `student`: Inherits from `person`, adds `branch`
- `teacher`: Inherits from `person`, adds `subject`
- `college`: Contains college details and lists of students and teachers

## 📋 Menu Options

1. Add College  
2. Add Student  
3. Add Teacher  
4. Display Student Details  
5. Display Teacher Details  
6. Exit

## 📸 Sample Output

```plaintext
Welcome !

1. Add college
2. Add Student
3. Add Teacher
4. Display Student Details
5. Display Teachers Details
6. Exit
Enter Your Choice: 1
Enter College Id: 101
Enter College Name: Alpha Institute
🏁 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/college-management.git
cd college-management
Run the script

bash
Copy
Edit
python college_management.py
💡 Make sure you have Python 3 installed.

📂 File Structure
bash
Copy
Edit
college-management/
│
├── college_management.py   # Main Python script
└── README.md               # Project documentation
📌 To-Do / Future Features
File-based data saving/loading

Search functionality

GUI using Tkinter or PyQt

Validation for duplicate roll numbers

🧑‍💻 Author
Made with ❤️ by [Your Name]

Feel free to fork, contribute or suggest new features!
