# Social Network Simulator (Java Desktop) 🌐

A Java-based desktop application that simulates a social network environment. This project was designed to explore advanced **Object-Oriented Programming (OOP)** principles and the **Facade Design Pattern** to manage user interactions and administrative roles.

### 🚀 Key Features

- **Authentication System:** Secure registration and login for standard Users and Administrators.
- **Friendship Management:** Logic to add, list, and remove friends with real-time updates to the user's profile.
- **Role-Based Access:** Distinction between `USER` and `ADMIN` accounts using Enums and Polymorphism.
- **GUI Interface:** Built with Java Swing and AWT, featuring custom button designs and dynamic window transitions.

### 🏗️ Architectural Highlights

- **Facade Pattern:** Implemented via `ContasFacade` to decouple the business logic from the UI, simplifying interactions between the front-end and the account management system.
- **Polymorphism & Inheritance:** Use of an abstract `Conta` class as a blueprint for `Usuario` and `Administrador` subclasses.
- **Encapsulation:** Robust data protection using private attributes and controlled access through Getters/Setters.
- **Advanced Enums:** Specialized `TipoConta` enum to manage constant metadata (weights and descriptions) for different account types.

### 🛠 Tech Stack
- **Language:** Java (JDK Eclipse Temurin 17.0.8)
- **Library:** Java Swing & AWT (GUI)
- **Design Patterns:** Facade, Singleton (logic), and Builder-style interaction.

---
*Note: This simulator served as a deep dive into Java OOP structures. I am currently applying these architectural patterns to high-concurrency Back-end systems using Go, PostgreSQL, and Docker.*
