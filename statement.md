

# 🎯 Project Statement: Basic Subscription Manager

## 📝 Problem Statement

In today's digital economy, consumers often lose track of the various recurring charges (subscriptions) they incur monthly. These small, individual costs can quickly accumulate, leading to unexpected financial strain or budgetary oversight.

The problem is the lack of a **simple, immediate, and accessible tool** for users to quickly catalogue, view, and calculate their total monthly subscription expenditure without relying on complex external software or manually sifting through bank statements.

## 🔭 Scope of the Project

The scope of this initial project is narrow and focused on a single, essential function: **data aggregation and calculation**.

### **In-Scope Items:**

* **Data Entry:** Allow the user to input the subscription **name** and **cost** via the command line.
* **Data Storage:** Implement a fundamental Python data structure (a list of lists) to temporarily hold the entries during the program's execution.
* **Validation:** Implement input validation to ensure costs are positive numeric values.
* **Output:** Calculate and display the itemized list of subscriptions and the final, accurate **total monthly cost**.

### **Out-of-Scope Items (Future Enhancements):**

* **Persistence:** Saving data to a file (CSV, JSON) so it persists after the program closes.
* **CRUD Operations:** Functionality to edit, delete, or search existing entries.
* **User Interface:** Development of a graphical user interface (GUI) or web application.
* **Advanced Analytics:** Tracking annual costs, filtering by category, or predicting future expenses.

## 👤 Target Users

The project targets individuals who need a quick and easy way to monitor their recurring expenditures.

* **Students/Young Professionals:** Individuals managing their first independent budgets who are likely to have multiple streaming, gaming, or productivity subscriptions.
* **Budget-Conscious Users:** Any user who needs a fast calculation of their monthly overhead costs for financial planning.
* **Programmers Learning Python:** The simple list-based structure makes the project an excellent learning tool for understanding basic data structures, input handling, and calculation loops.

## ⭐ High-Level Features

1.  **Subscription Logging:** An iterative loop allowing users to input an unlimited number of subscription entries.
2.  **Robust Input Handling:** Built-in error checking to handle non-numeric or negative inputs for cost.
3.  **Total Monthly Summation:** Accurate calculation of the combined cost of all entered subscriptions.
4.  **Clear Report Generation:** Presentation of the final data in a neat, easy-to-read list format on the console.
