# 🧮 Interactive Vanilla JavaScript Calculator

A sleek, modern, and high-performance Web Calculator built with pure HTML5, CSS3, and modern Vanilla JavaScript (ES6+). Designed with a realistic 3D aesthetic, dynamic keyboard support, and robust operator input handling.

---

## ✨ Features

* **Realistic 3D UI:** Built with custom dynamic box-shadows, balanced padding, and dark-mode color palettes for a tactile physical desktop calculator feel.
* **Dual Control Options:** Fully functional with both **Mouse Clicks** and **Physical Keyboard** inputs.
* **Clean Code & Validation:** Prevents invalid input sequences (e.g., consecutive operators like `++` or `**`) dynamically using modern JavaScript methods like `Array.includes()`.
* **Centralized Logic Engine:** Reusable `handleInput()` function driving both keyboard and click events (DRY - Don't Repeat Yourself principle).
* **Safe Expression Evaluation:** Integrated `try...catch` error handling to gracefully capture evaluation errors without breaking the application UI.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic layout structuring.
* **CSS3:** Custom styles, Flexbox layout, CSS variables, and modern shadow effects.
* **JavaScript (ES6+):** Event listeners (`keydown` and `click`), string manipulation, DOM methods, and modular code logic.

---

## ⌨️ Keyboard Shortcuts Supported

| Keyboard Key | Function / Action |
| :--- | :--- |
| `0` - `9` | Digits Input |
| `+`, `-`, `*`, `/`, `%` | Mathematical Operators |
| `.` | Decimal Point |
| `Enter` / `=` | Evaluate Expression |
| `Backspace` | Delete Single Last Character (`DEL`) |
| `Escape` | Clear All Inputs (`C`) |

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone (https://dev-nasrullah-pk.github.io/js-calculator-app/)