# Personal-Expense-Tracker
Personal Expense Tracker using demonstrating OOP concepts, collections, multithreading, exception handling and Java NIO.

# 💰 Personal Expense Tracker
### A Java Console Application

## 📌 Project Overview

Personal Expense Tracker is a menu-driven console application developed using Java. It helps users manage their daily expenses by recording, organizing, viewing, and deleting expense records.

The application supports one-time and recurring expenses, calculates total spending, generates category-wise summaries, and stores expense information in a text file so that records can be accessed in future sessions.

## 🎯 Objectives

- Record daily personal expenses.
- Organize expenses into different categories.
- Support one-time and recurring expenses.
- View all expenses sorted by date.
- Calculate total spending automatically.
- Delete expenses using their IDs.
- Generate category-wise expense reports.
- Save and load expense data using Java NIO.

## ✨ Features

1. **Add Expense:** Add expenses with title, amount, category and date.
2. **Recurring Expenses:** Record expenses with Weekly, Monthly or Yearly frequency.
3. **View Expenses:** Display all expenses in a structured table.
4. **Total Spending:** Calculate the total amount spent.
5. **Delete Expense:** Remove an expense using its ID.
6. **Expense Summary:** Display category-wise spending.
7. **File Handling:** Save and retrieve expense records.
8. **Multithreading:** Perform saving using a separate thread.
9. **Input Validation:** Handle invalid inputs and exceptions.

## 🛠️ Technologies Used

- Programming Language: Java
- JDK: JDK 8 or later
- IDE: Any Java-supported IDE (optional)
- Interface: Command Line / Console
- Storage: Text File
- Version Control: Git and GitHub

## 📚 Java Concepts Demonstrated

### Unit I
- Classes and Objects
- Constructors
- Static and Final Keywords
- Scanner
- Control Statements

### Unit II
- Inheritance
- Method Overriding
- Abstract Classes
- Interfaces
- Runtime Polymorphism

### Unit III
- Exception Handling
- Custom Exceptions
- Try-with-Resources
- Multithreading

### Unit IV
- ArrayList
- List and Map
- TreeMap
- Iterator
- Comparable
- Collections.sort()

### Unit V
- Java NIO
- Path and Paths
- Files Class
- File Reading and Writing

## 📂 Project Structure

```text
PersonalExpenseTracker_Console/
│
├── src/
│   ├── Main.java
│   ├── PersonalExpenseTracker.java
│   ├── Expense.java
│   ├── RegularExpense.java
│   ├── RecurringExpense.java
│   ├── ExpenseManager.java
│   ├── Reportable.java
│   ├── ExpenseReport.java
│   ├── ExpenseFileService.java
│   ├── ExpenseSaverThread.java
│   └── InvalidExpenseException.java
│
├── data/
│   └── expenses.txt
│
├── run.bat
├── run.sh
├── README.md
└── .gitignore
```

## ⚙️ Requirements

- Java Development Kit (JDK 8 or later)
- Command Prompt / Terminal
- Git (optional, for cloning the repository)

## ▶️ How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/grohithnandhan-09/Personal-Expense-Tracker.git
```

### Step 2: Open the project folder

```bash
cd Personal-Expense-Tracker
```

### Step 3: Compile the Java files

```bash
mkdir out
javac -d out src/*.java
```

### Step 4: Run the application

```bash
java -cp out Main
```

## 💾 Data Storage

Expense records are stored in:

```text
data/expenses.txt
```

The application automatically creates the required data folder and file when necessary.

## 🔮 Future Enhancements

- Graphical User Interface (GUI)
- Database integration
- User authentication
- Monthly expense charts
- Budget management and alerts
- Expense editing functionality

## 👨‍💻 Developer

**Name:** G. Rohith Nandhan

**Roll Number:** 1601-25-733-158

**College:** Chaitanya Bharathi Institute of Technology (CBIT), Hyderabad

**Department:** Computer Science and Engineering

**Course:** Java Programming

## 🔗 GitHub Repository

https://github.com/grohithnandhan-09/Personal-Expense-Tracker

---

⭐ If you find this project useful, consider giving the repository a star!

