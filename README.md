subscription_manager
vityarthi project



# 📑 README.md: Basic Subscription Manager (List Version)

## 💰 Project Title

**Basic Subscription Manager (List Version)**

-----

## 💡 Overview of the Project

This project is a simple, command-line utility written in Python designed to help users track their recurring monthly subscription costs. It prompts the user to enter the name and cost for each subscription and utilizes a **list of lists** as the primary data structure for storage.

The utility automatically calculates and displays the **total monthly expenditure**, making it a useful tool for basic budgeting and financial awareness.

-----

## ✨ Features

  * **Interactive Input:** Guides the user through entering subscription names and costs.
  * **Data Validation:** Ensures that the entered cost is a valid, positive numerical value (uses `try-except` for error handling).
  * **List Storage:** Stores subscription data (name and cost) using Python lists.
  * **Total Calculation:** Automatically sums all individual subscription costs.
  * **Formatted Output:** Displays a clear, itemized list of all entered subscriptions and the final total cost, formatted to two decimal places (e.g., `$15.99`).

-----

## 🛠️ Technologies/Tools Used

  * **Programming Language:** Python 3 (Tested with Python 3.9+)
  * **Primary Data Structure:** Python `list` (specifically, a list of lists)
  * **Input/Output:** Standard built-in Python functions (`input()`, `print()`)

-----

## 🚀 Steps to Install & Run the Project

Since this project consists of a single Python file with no external dependencies, running it is straightforward.

### Prerequisites

You must have **Python 3** installed on your system.

### Installation & Execution

1.  **Save the Code:** Save the provided code into a file named `subscription_manager.py`.

2.  **Open Terminal/Command Prompt:** Navigate to the directory where you saved the file.

3.  **Run the Script:** Execute the file using the Python interpreter:

    ```bash
    python subscription_manager.py
    ```

4.  **Follow Prompts:** The program will start and ask you to enter the subscription names and their costs. Enter `'done'` when you finish adding all subscriptions.

-----

## ✅ Instructions for Testing

To test the core functionality, follow these steps when the script is running:

| Test Case | Input | Expected Outcome |
| :--- | :--- | :--- |
| **Normal Input** | Netflix, 15.49; Spotify, 10.99; done | Both entries displayed. Total: `$26.48` |
| **Non-Numeric Cost** | Cost input: `hello` | Prints **"Invalid input. Please enter a valid number..."** and asks for cost again. |
| **Negative Cost** | Cost input: `-5.00` | Prints **"Cost cannot be negative. Please enter a positive value."** and asks for cost again. |
| **Zero Subscriptions** | Subscription name input: `done` immediately. | Prints **"No subscriptions were entered."** and exits gracefully. |

-----

## 🖼️ Screenshots (Example Run)

> **Note:** Screenshots are optional, but here is a simulation of the output you would see in the terminal.

### **Example Session**

```
 Welcome to your Basic Subscription Manager (List Version)! 
Enter 'done' for the subscription name when finished adding.
---------------------------------------------
Enter subscription name (or 'done'): Netflix
Enter cost for 'Netflix' (e.g., 9.99): $15.49
Added: Netflix ($15.49)

Enter subscription name (or 'done'): Spotify
Enter cost for 'Spotify' (e.g., 9.99): $10.99
Added: Spotify ($10.99)

Enter subscription name (or 'done'): done

=============================================
 Your Subscriptions:
- Netflix: $15.49
- Spotify: $10.99
---------------------------------------------
 Total Monthly Cost: $26.48
=============================================
