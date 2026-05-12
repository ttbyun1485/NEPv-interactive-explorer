## Report

## Problem Statement 
The primary objective of this project is to explore and visualize the Nonlinear Eigenvalue Problem with eigenvector dependency(NEPv). In standard eigenvalue problem, the matrix is defined by a fixed matrix. However, in the NEPv, the matrix is a function of a vector. This dependency transforms the problem from a direct linear computation into a more complex question. By designing an interactive tool , this project aims to provide intuitive visualization.

## Methodology 
A 2x2 matrix is used as an exmaple in this visualizer. The chosen operator is A(v), where 
        A(v) = [[ x²  1 ],
               [ 1   y² ]].

This matrix is then multiplied with the vector v. After that, an alignment detection algorithm is designed to identify eigenvector in the visualizer. Sepecially, the algorithm calculate the phase angle of both vectors using Math.atan2(y,x). Also, an tolerance of 0.01 radians is set. Once an eigenvector is detected, the corresponding eigenvalue will be computed by taking ratio of the vector magnitudes. 

## Evaluation 
The explorer was evaluated by fixing coordinates and verifying the presented result. It is observed that all symmertric solutions are detected and some non-trivial solutions are also successfully identified. The success state reliably signled these alignments by turning the visual output to green. 
