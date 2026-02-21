# 🎓 Grade Management System (Advanced Version)

## 📌 Project Overview

The Grade Management System is a Java-based console application developed to manage student academic records efficiently.
It allows users to add student marks, calculate averages, assign grades, generate performance reports, perform analytics, and store data permanently using file persistence.

This project is built using Object-Oriented Programming (OOP) concepts and follows a modular structure.

---

## 🚀 Features

* Add student records and marks for 5 subjects
* Automatic average calculation
* Grade assignment (A+ to F)
* View all students with performance summary
* Identify top performer
* Generate class report
* File persistence (Save & Load student data)
* Input validation (marks and menu choices)
* Performance analytics (highest, lowest, pass %)

---

## 🛠 Technologies Used

* Java (JDK 8+)
* Object-Oriented Programming (OOP)
* File Handling (FileWriter, BufferedReader)
* Exception Handling
* Arrays & Data Structures

---

## 📂 Project Structure

```
GradeManagementSystem/
│
├── src/
│   ├── GradeManage_main/
│   │     └── Main.java
│   │
│   ├── GradeManage_StudentGrade/
│   │     └── StudentGrade.java
│   │
│   ├── GradeManage_GradeCal/
│   │     └── GradeCalculator.java
│   │
│   └── GradeManage_ReportGenerator/
│         └── ReportGenerator.java
│
├── docs/
│   ├── Project_Documentation.pdf
│   ├── Installation_Guide.pdf
│   └── User_Manual.pdf
│
├── examples/
│   ├── students_sample.txt
│   └── output_example.txt
│
├── README.md
└── .gitignore
```

---

## ⚙️ Setup & Installation

### Step 1: Install Java

* Install Java JDK 8 or above
* Verify installation:

```
java -version
```

### Step 2: Clone Repository

```
git clone https://github.com/kraunak212/Grade_Management_System.git
```

### Step 3: Open in IDE

* Open project in IntelliJ IDEA / Eclipse

### Step 4: Run Project

* Run **Main.java**

---

## 📊 Grading System

| Average Marks | Grade |
| ------------- | ----- |
| 90–100        | A+    |
| 80–89         | A     |
| 70–79         | B     |
| 60–69         | C     |
| 50–59         | D     |
| Below 50      | F     |

Grades are assigned automatically based on calculated average.

---

## 💾 File Persistence

Student data is saved in:

```
students_runtime_example.txt
```

Format:

```
Name,Math,Science,English,History,Computer
```

* Auto-loads when program starts
* Auto-saves when program exits

---

## 📈 Analytics Provided

* Class average
* Top performer
* Highest & lowest performance
* Pass percentage

---

## 🧪 Example Data

Sample grade data available in:

```
examples/students_sample.txt
```

Example output:

```
=== CLASS REPORT ===
Total Students: 5
Class Average: 76.40

=== TOP PERFORMER ===
Aman with Average = 92.20, Grade = A+
```

---

## 🎯 Learning Outcomes

This project demonstrates:

* Java programming fundamentals
* OOP design and modular coding
* File handling and persistence
* Input validation techniques
* Algorithm design for grade computation
* Structured project architecture

---

## 🚧 Limitations

* Console-based interface
* Limited to 100 students
* No database integration

---

## 🔮 Future Enhancements

* GUI version using Swing/JavaFX
* MySQL database integration
* Web-based system
* Graphical performance analytics

---

## 👨‍💻 Author

**Name:** Raunak Kumae
**Course:** B.Tech 
**Project Type:** Internship Mini Project
**Version:** Advanced (Option 3)
