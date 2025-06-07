Calculator App

# 🧮 Calculator App

A responsive, fully functional calculator built using **HTML**, **CSS**, and **JavaScript**. This project showcases interactive event handling, dynamic DOM manipulation, and mobile-friendly design — all built from scratch without any frameworks.

---

## 🚀 Features

- Basic arithmetic operations: **Addition, Subtraction, Multiplication, Division**
- AC (All Clear) functionality to reset display
- Input display auto-clears before new values
- Fully responsive layout using `vh`, `vw`, and flexible design units
- Mimics the iPhone Calculator design with custom styling
- Dark theme with intuitive color differentiation

---

## 🧪 Technologies Used

- **HTML5** – For structure and layout
- **CSS3** – For responsive and aesthetic styling
- **JavaScript (Vanilla)** – For interactivity and logic

---

## 🗂️ Project Structure

calculator-app/
│
├── calculator.html # Main HTML file
├── style.css # Calculator styling
├── README.md # Project documentation


---

## 🧠 Core Concepts Practiced

- DOM Manipulation using `getElementById`
- Handling user inputs and click events
- Arithmetic computation logic using JavaScript
- Preventing input anomalies like leading zeros
- Clean separation of HTML, CSS, and JS logic

---

## 📋 How It Works

### ➕ Entering Digits
```js
digitBtnPressed(button)
Appends the clicked digit to the input box. Clears default zero when typing the first number.
Stores the current input (value1) and chosen operator (+, -, *, /) for later computation.
Uses a switch statement to compute the result based on the stored operator and second input (value2), then updates the display.
Resets everything to the default state (0 on screen, cleared variables).

🔧 Improvements for Future Versions
Add decimal support (. button)

Add keyboard support for digit and operator input

Allow chaining operations (e.g., 2 + 3 + 5 =)

Add percent (%) and sign toggle (+/-) functionality

Refactor JavaScript into modules

Add CSS transitions and animations for smoother UI feedback

Improve accessibility (aria-labels, keyboard nav)

📚 Lessons Learned
Building a calculator may seem simple on the surface, but it's an ideal way to learn:

Event-driven programming

JavaScript control structures (if, switch, etc.)

State management using variables

Mobile-first responsive layout design

✅ Status
✔️ Complete – V1.0
🛠️ Open to improvements in future iterations.

📄 License
This project is open source and available under the MIT License.

🤝 Contributing
Have suggestions or want to make improvements? Pull requests are welcome!

🙌 Acknowledgments
Inspired by the iPhone Calculator interface

Guided by the [App Academy] curriculum structure


