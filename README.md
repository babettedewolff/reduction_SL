# reduction_SL
Mathematica code that performs a second order phase reduction for two-coupled Stuart-Landau oscillators. 

Input: the function "coupling" defines the coupling between the two oscillators, here chosen as a delayed mean field. 
Output: 
- The function f1[phi1, phi2] gives the first order phase reduction and the functions f2[phi1, phi2] the second order correction to the phase reduction.
- In phase difference coordinates psi = phi1 - phi2, the second order reduction will be of the form psi' = epsilon a1 sin(psi) + epsilon^2 b1 sin(psi) + epsilon^2 b2 sin(2*psi). The coefficients are computed in the following functions:
    - The function ord1four1 computes the coefficient a1
    - The function ord2four1 computes the coefficient b1
    - The function ord2four2 computes the coefficient b2
