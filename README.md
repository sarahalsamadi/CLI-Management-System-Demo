# CLI Management System Demo

[cite_start]A robust and interactive Command Line Interface (CLI) application developed in **C++** to manage ticket bookings and reservations efficiently. This program features a secure user login system and handles complex financial calculations for various ticket classes.

## 🌟 Key Features
* **Secure Authentication:** Implements a username and password protection system with a limited number of login attempts (3) to ensure authorized access.
* **Tiered Ticket Categories:** Offers three distinct ticket classes:
    * **First Class:** $150.0
    * **Medium (Window Seat):** $80.0
    * **Regular:** $40.0
* **Dynamic Financial Logic:** * Calculates the total required amount based on the number of reserved seats.
    * Automatically calculates the remaining balance (rest) if the payment exceeds the requirement.
    * **Automatic Seat Adjustment:** Intelligently calculates how many seats can be booked based on the actual amount paid and informs the user of any cancellations.
* **Looping Session Management:** Allows users to perform multiple booking transactions in a single session.

## 🛠️ Built With
* [cite_start]**Language:** C++ 
* [cite_start]**Compiler:** GCC 
* [cite_start]**IDE:** Code::Blocks 
* **Key Concepts:** Procedural Programming, Switch-Case Logic, Financial Logic, and Error Handling.

## 📂 Project Structure
* [cite_start]`main.cpp`: The core source file containing the application logic, authentication, and booking functions.
* [cite_start]`project.cbp`: The Code::Blocks project file for seamless environment setup[cite: 14].

## 🚀 How to Run
1.  Ensure you have a C++ compiler installed (like GCC).
2.  [cite_start]Open the project using **Code::Blocks** by selecting `project.cbp`[cite: 14].
3.  Compile and run the program within the IDE.
4.  Enter the default login credentials and follow the on-screen instructions to reserve your tickets.

---
Developed as a demonstration of C++ programming fundamentals and logic implementation.
