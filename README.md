# NEPv Interactive Explorer

An interactive mathematical visualization built to explore **Nonlinear Eigenvalue Problems with eigenvector dependency (NEPv)**.

## Live Demo
https://ttbyun1485.github.io/NEPv-interactive-explorer/

## Local Setup
To run this project on your machine, follow these steps:

1. **Clone the repository:**
```bash
   git clone https://ttbyun1485.github.io/NEPv-interactive-explorer/
cd NEPv-interactive-explorer
```
2. **Installation**
   No installation is required.

3. **Run Locally**
   Simply open the index.html file.

## Design Choices
- Interactive game: Users can choose any vectors using the sliders for x and y. The tool allows the user to actively look for the solution and observe the pattern.
- Real-time feedback: Once an eigenvector is found, a success state is shown where both vectors turn green and an eigenvalue approximation is presented.

## Limitations 
- Precision:  The tool uses a tolerance threshold (0.01 radians) for alignment detection.
- Oeprator: The operator is defined to be a  2x2 matrix, failed to provide gemoetric interpretation of higher-dimension matrix. Also, the users cannot explore other matrix-functions. 

## AI Disclosure
This project was developed with the assistance of AI for UI/UX brainstorming and front-end architecture. 

