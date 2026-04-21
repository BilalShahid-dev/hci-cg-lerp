 Lab Week 09: Linear Interpolation (LERP) Explorer

**Course:** Human Computer Interaction and Computer Graphics CS 555 (2+1)
**Student Name:** Muhammad Bilal Shahid
**Seat Number:** B23110006091

## 🎯 Project Overview
This project provides an interactive web-based interface to understand and visualize **Linear Interpolation (LERP)**. LERP is a fundamental mathematical function used extensively in computer graphics, animation, and game development (like Three.js) to transition smoothly between two states, positions, or values over time.

## 🧠 Core Concepts

* **Start Value (A):** The initial state or origin point.
* **End Value (B):** The target state or destination point.
* **Weight / Time (t):** A floating-point number strictly between `0.0` and `1.0` that determines the current percentage of the transition.
    * When `t = 0`, the result is exactly the Start Value.
    * When `t = 1`, the result is exactly the End Value.
    * When `t = 0.5`, the result is exactly halfway between the two.
