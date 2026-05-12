# NEPv Interactive Explorer

An interactive mathematical visualization built to explore **Nonlinear Eigenvalue Problems with eigenvector dependency (NEPv)**.

## 🚀 Live Demo
[Insert your GitHub Pages link here]

## 🧠 Project Overview
This project visualizes how the matrix $A(v)$ evolves as the input vector $v$ changes. 
The specific operator used is:
$$A(v) = \begin{pmatrix} x^2 & 1 \\ 1 & y^2 \end{pmatrix}$$

The tool allows users to manually "hunt" for eigenvectors by identifying positions where the input and output vectors align.

## 🛠️ Built With
- **HTML5/CSS3** (Bootstrap 5)
- **Plotly.js** for real-time vector rendering
- **MathJax** for LaTeX typesetting

## 🤖 AI Disclosure & Hand-Verification
This project was developed with the assistance of AI for UI/UX brainstorming and front-end architecture. 
**Mathematical Integrity:** All core logic, specifically the NEPv operator and the alignment detection thresholds, were hand-verified. For example, the symmetric solution at $(-0.8, -0.8)$ and the inversion solution at $(-0.8, -1.25)$ were analytically confirmed to ensure visualization accuracy.
