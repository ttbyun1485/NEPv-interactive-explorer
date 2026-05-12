# NEPv Interactive Explorer

An interactive mathematical visualization built to explore **Nonlinear Eigenvalue Problems with eigenvector dependency (NEPv)**.

## Live Demo
https://ttbyun1485.github.io/NEPv-interactive-explorer/

## Local Setup
To run this project on your machine, simply open the index.html file.

## Design Choices
- Interactive game: Users can choose any vectors using the sliders for x and y. The tool allows the user to actively look for the solution and observe the pattern.
- Real-time feedback: Once an eigenvector is found, a success state is shown where both vectors turn green and an eigenvalue approximation is presented.

## Limitations 
- Precision:  The tool uses a tolerance threshold (0.01 radians) for alignment detection.
- Operator: The operator is defined to be a  2x2 matrix, failed to provide gemoetric interpretation of higher-dimension matrix. Also, the users cannot explore other matrix-functions. 

## AI Disclosure
This project was developed with the assistance of AI for UI front-end architecture. All core logic, like the NEPv operator and the alignment detection thresholds, were hand-verified. For example, I have picked some x and checked that the alignment matched the actual calculation. 

