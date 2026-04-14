# Regex → Automaton Visualizer

A powerful web-based tool to convert Regular Expressions into Finite Automata. This project visualizes the step-by-step pipeline of formal language theory.

## 🚀 Features
* **Thompson Construction:** Generates an ε-NFA from a regular expression.
* **Subset Construction:** Converts NFA to a Deterministic Finite Automaton (DFA).
* **DFA Minimization:** Uses Hopcroft's Algorithm to find the smallest possible DFA.
* **Interactive GTG:** Step-by-step Generalized Transition Graph reduction.
* **Build by Hand:** Draw your own states and transitions and convert them back to Regex.
* **Live Simulation:** Test strings against your generated DFA.

## 🛠️ Technology Stack
* **Frontend:** HTML5, CSS3 (Glassmorphism UI), Vanilla JavaScript.
* **Canvas API:** Custom-built engine for rendering and animating state nodes and transitions.

## 📖 How to Run
1. Clone this repository: `git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git`
2. Open `index.html` in any modern web browser.
3. (Optional) This project is compatible with **Netlify** or **GitHub Pages** for instant hosting.

## 🎓 Academic Context
This tool was developed as part of a **Theory of Computation (TOC)** project to help students visualize abstract automata concepts.