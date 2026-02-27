# 🏦 Java Financial Control System

![Java](https://img.shields.io/badge/Language-Java-orange.svg?logo=java&logoColor=white)
![CLI](https://img.shields.io/badge/Interface-CLI-yellow)
![Core Logic](https://img.shields.io/badge/Focus-Control_Flow-green)
![OOP](https://img.shields.io/badge/Concept-OOP_Basics-purple)

A streamlined Java terminal application simulating a foundational banking environment, designed to securely manage account states and handle real-time financial transactions.

**The Problem:** Understanding the strict typing, object orientation, and control flow of Java can be challenging when coming from more flexible languages. Building scalable enterprise software (the primary use case for Java in industry) requires a solid grasp of state management and input validation.

**The Solution:** A practical, interactive terminal banking application. This project serves as a foundational sandbox to master Java's core logic, specifically `Scanner` input handling, `while`/`switch` control loops, and variable state mutation—by simulating real-world banking operations.

---

## 📸 Capabilities
* **Account Initialization:** Allows users to establish their identity, set their account type (e.g., Checking or Savings), and define an initial balance.
* **Transaction Engine:** Supports real-time financial operations:
    * **Check Balance:** Securely retrieve the current account state.
    * **Receive Funds (Deposit):** Increment the account balance safely.
    * **Transfer Funds (Withdrawal):** Verify sufficient funds and decrement the balance, preventing overdrafts.
* **Interactive CLI:** Utilizes a persistent menu loop that waits for user commands, ensuring a continuous user experience until a manual exit is triggered.

## 🛠 Tech Stack
| Component | Technology | Description |
| :--- | :--- | :--- |
| **Core** | Java | Main application logic and state management |
| **Input Handling** | `java.util.Scanner` | Capturing and parsing standard input (stdin) |
| **Execution** | JVM | Runs on the Java Virtual Machine |

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone [https://github.com/cunhanina/Bank.git](https://github.com/cunhanina/Bank.git)
cd Bank

# 2. Compile the Java file
javac main.java

# 3. Run the application
java main
```

## 🧠 System Architecture
This application utilizes a straightforward procedural architecture to establish a solid grasp of Java fundamentals:
1.  **I/O Stream (Input/Output):** Relies on the `Scanner` class to read user inputs from the console. This requires careful handling of line breaks and data types (e.g., ensuring a `double` is provided for currency).
2.  **The Event Loop:** The core of the program is wrapped in a `while` loop that acts as the main thread. It continuously renders the operation menu and listens for state changes.
3.  **Command Routing:** A control flow structure evaluates the user's numeric input and routes the execution context to the appropriate transaction block (Deposit, Transfer, or Exit), updating the isolated `balance` variable accordingly.

---

<div align="center">

### Built with ❤️ by [Nina Cunha](https://github.com/maxykoin)

**Data Science · Industrial Automation · Software Engineering**

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/nscunha/)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/maxykoin)

</div>

---
