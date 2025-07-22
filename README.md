# Interactive Linear Regression Calculator

An intuitive web-based tool designed to simplify linear regression analysis, especially for students and teaching assistants in a practicum or lab setting.

---

## Description

This project was developed to address a common challenge in academic lab work (practicum): the need for a tool that is both powerful enough to perform accurate linear regression calculations and clear enough to serve as an educational resource.

For students, it automates complex and error-prone manual calculations, allowing them to focus on understanding the results and the underlying concepts of their experiments. For practicum assistants, it provides a fast and reliable way to verify student work, as every step of the calculation is transparently displayed.

This tool bridges the gap between manual calculation and "black box" software by providing the speed of automation while showing the "how" and "why" behind every result.

---

## Features

-   **Dynamic Data Entry:** Users can specify the exact number of data points they need to analyze.
-   **Step-by-Step Calculation Table:** Automatically generates a process table showing all intermediate values (`xᵢ`, `yᵢ`, `xᵢ²`, `yᵢ²`, `xᵢyᵢ`) and their sums.
-   **Full Formula Display:** Shows the complete mathematical formulas for all major calculations, with the user's data plugged in for full transparency.
-   **Comprehensive Results:** Calculates and displays all key regression metrics, including:
    -   Slope (b) and Y-Intercept (a)
    -   Standard Error of Estimate (Δy)
    -   Uncertainty of the Slope (Δb)
    -   Coefficient of Determination (R²)
    -   Accuracy Level (Tingkat Ketelitian)
-   **Interactive Data Visualization:**
    -   A scatter plot of the user's data points.
    -   An overlaid **Data Path** (solid line) and **Regression Line** (dotted line) for easy comparison.
-   **Modern User Interface:**
    -   A clean, responsive design that works on all screen sizes.
    -   A **Light/Dark Mode** theme switcher with intuitive icons for user comfort.
    -   Professionally rendered mathematical equations using MathJax.

---

## Technologies Used

-   **HTML5:** For the core structure of the application.
-   **CSS3:** For all custom styling, responsive design, and theme implementation.
-   **Vanilla JavaScript (ES6+):** For all application logic, interactivity, and mathematical calculations.
-   **Chart.js:** Used to create the interactive and responsive regression graph.
-   **MathJax:** Used to render all mathematical formulas in a clean, professional format.

---

## Setup Instructions

This project is built with vanilla HTML, CSS, and JavaScript and has no build dependencies.

1.  Clone the repository to your local machine:
    ```bash
    git clone [https://github.com/Emraaaa/linear-regression-calculator](https://github.com/Emraaaa/linear-regression-calculator)
    ```
2.  Navigate into the project directory:
    ```bash
    cd linear-regression-calculator
    ```
3.  Open the `index.html` file directly in your web browser.

---

## AI Support Explanation

This project was developed with the assistance of an AI programming partner (IBM Granite). The AI's role was integral to the development process in several key areas:

-  The use of AI allowed for rapid prototyping and the implementation of advanced features that would have been more time consuming otherwise. This enabled a stronger focus on the core logic, user experience, purpose of this project, and the educational value of the tool.
-  Helped identify and fix bugs (like JavaScript reference errors and CSS layout issues) and refactor code for better performance and readability.
-  Assisted in adding complex features step-by-step, such as the professional equation rendering with MathJax and the interactive theme switcher.
