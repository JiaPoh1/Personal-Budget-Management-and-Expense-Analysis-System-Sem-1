# 💰 Personal Budget Management System (C++)
📌 Description

This project is a console-based Personal Budget Management System developed in C++. It helps users track their income, manage expenses, and analyze spending habits across different categories.

The program allows users to input fixed and variable income, followed by multiple types of expenses. It then calculates total expenses, actual savings, and compares them against a user-defined savings goal.

Additionally, users can enter expenses by category such as transportation, food, utilities, medical & healthcare, personal spending, and entertainment. The system computes the percentage distribution of expenses and allocates the remaining budget proportionally based on spending priorities.

## ✨ Features
- 💵 Calculate total income (fixed + variable)
- 📉 Track fixed and variable expenses
- 🎯 Compare actual savings with savings goal
- 📊 Categorize expenses into 6 categories
- 📈 Calculate percentage of each expense category
- 💡 Automatically allocate remaining budget based on spending distribution

## 🛠️ Technologies Used
- C++
- Standard Libraries (iostream, iomanip, cmath)
- Functions & Modular Programming

## ▶️ How to Run

Clone the repository:
```
git clone https://github.com/JiaPoh1/Personal-Budget-Management-and-Expense-Analysis-System-Sem-1.git
Open in your C++ IDE (e.g., Visual Studio / Code::Blocks)

Compile and run:

g++ main.cpp -o program
./program
```
## 🖥️ Sample Output
Enter your fixed income: 2000
Enter your variable income: 500
Enter your savings goal: 1000

--- Results ---

Total Income: RM2500

Total Expenses: RM1800

Actual Savings: RM700

Savings goal not met. Deficit: RM300

## 📊 Categories Included
- 🚗 Transportation
- 🍔 Food
- 💡 Utilities
- 🏥 Medical & Healthcare
- 🛍️ Personal Spending
- 🎮 Entertainment
  
## ⚠️ Notes
- This is a console-based program (no GUI)
- Some parts use global variables (can be improved)
- Works best in environments that support standard C++ input/output

## 🚀 Future Improvements
- Replace global variables with structured data (struct/class)
- Add file storage for saving user data
- Improve UI/UX (menu system or GUI)
- Add charts/visualization of expenses
- Reduce repetitive functions using loops or arrays
