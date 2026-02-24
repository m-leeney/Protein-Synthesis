The system was solved using the ddeint
package in Python, which implements the VODE solver (Variable-coefficient ODE solver). VODE uses Adams-Moulton methods for non-stiff systems and Backward Differentiation Formulae (BDF) for stiff systems (See Brown, P.N., Byrne, G.D. and Hindmarsh**, A.C. (1989). ’VODE: A Variable-CoefficientODE Solver’, SIAM Journal on Scientific and Statistical Computing, 10(5), pp.
1038–1051. doi: 10.1137/0910062. Accessed: 2026-02-22.)

To verify numerical convergence, we tested the basic model under different temporal resolutions. Insufficient
sampling (150 points over 100 time units, equivalent to 1.5:1 ratio) produces severe aliasing artifacts.
