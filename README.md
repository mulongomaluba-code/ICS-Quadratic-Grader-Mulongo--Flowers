# Quadratic Equation Solver & Grade Converter

A single-page **web application** built with **HTML, CSS, and JavaScript** that allows users to:
1. Solve quadratic equations of the form **ax² + bx + c = 0**
2. Convert numeric scores (0–100) into letter grades

All calculations are performed **client-side**, with no data sent to any server.

---

## 📘 Features

### 🧮 Quadratic Equation Solver
- Accepts coefficients **a**, **b**, and **c**
- Validates that **a ≠ 0**
- Computes:
  - **Discriminant (D)** = b² - 4ac  
  - **Roots** using the quadratic formula:  
    x = (-b ± √D) / (2a)
- Displays:
  - Equation in standard form
  - Value of the discriminant
  - Nature of the roots (real/complex)
  - Computed roots (up to 4 decimal places)
- Handles:
  - Two distinct real roots (D > 0)
  - One repeated real root (D = 0)
  - Two complex conjugate roots (D < 0)

---

### 🎓 Grade Converter
- Accepts a **score between 0 and 100**
- Converts the score into a **letter grade** based on the following scale:

| Score Range | Grade |
|--------------|--------|
| 85–100       | A+     |
| 75–84        | A      |
| 65–74        | B+     |
| 60–64        | B      |
| 55–59        | C+     |
| 50–54        | C      |
| 0–49         | D      |

- Displays the result in a color-coded box:
  - 🟢 Green for excellent results (A+)
  - 🟡 Yellow for average results
  - 🔴 Red for failing results (D)

---

## 💻 Technologies Used

- **HTML5** – Page structure and layout
- **CSS3** – Styling, responsive design, and visual effects
- **Vanilla JavaScript (ES6)** – Form validation and calculations

---

## 📱 Responsive Design

- Fully responsive on mobile, tablet, and desktop
- Uses flexible layouts and modern CSS media queries

---

## 🚀 How to Use

1. **Download or clone** this repository:
   ```bash
   git clone https://github.com/yourusername/quadratic-grade-app.git
