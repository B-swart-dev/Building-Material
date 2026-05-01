# 🏗️ Building Materials Cost Calculator

## Overview
A terminal-based application built with Java to calculate the total cost of building materials purchased at a hardware store.

The system allows users to select different materials (zinc sheets, window frames, and doors), input quantities, and calculate total costs dynamically.

---

## 🚀 Features
- Menu-driven terminal interface
- Supports multiple material categories:
  - Zinc (Corrugated & IBR)
  - Window Frames
  - Doors
- Displays pricing menus for each category
- Calculates total cost based on quantity × unit price
- Object-oriented design using inheritance and abstraction

---

## 🧠 OOP Concepts Demonstrated
- Abstract classes  
- Inheritance  
- Method overriding  
- Encapsulation  

### Structure:
- `BuildingMaterial` (abstract class)
- `Zinc`, `WindowFrame`, `Door` (subclasses)

Each subclass implements:
- `totalCostPrice()` → calculates total cost

Additional methods:
- Zinc:
  - `viewCorruZinc()`
  - `viewIBRZinc()`
- WindowFrame:
  - `viewWindowMenu()`
- Door:
  - `viewDoorMenu()`

---

## 🛠️ Tech Stack
- Java  
- Console / Terminal I/O  

---

## ▶️ How to Run
1. Open the project in your IDE (NetBeans / IntelliJ / Eclipse)  
2. Run:
```bash
UseBuildingMaterial.java
```

---

## 💡 Example Usage
<img width="1190" height="481" alt="image" src="https://github.com/user-attachments/assets/688cdf2e-9ef8-448a-94b2-87fac93df975" />

---

## 📌 Notes
This project demonstrates the use of object-oriented programming principles to solve a real-world problem involving pricing and inventory calculations.

---
