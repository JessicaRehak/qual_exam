# Qual presentation Outline

1. Background
    1. Transport equation
        1. _k_-eigenvalue equation
    3. Issues with solving the TE
        1. Scattering ratio/dominance ratio
    3. The SN Equations
    3. Makeup of an "iteration"
        1. Inner iteration, outer iteration
        2. Convergence
2. Acceleration Methods
    1. Nonlinear diffusion acceleration
        1. LONDA
        2. Drift diffusion term
        3. Solve order (flow chart?)
    3. Transport-Two-grid method
    3. Combination of NDA + Two-grid
3. Analysis of Acceleration Methods
    1. Measurements of successful acceleration
        1. Use of iterations
        1. Difficulty in identifying sucess
        3. Use of fourier analysis
4. BART
    2. Second order forms of Transport Equation
        1. SAAF Equation
        2. Mention Even/Odd Parity
    1. Polymorphism
        1. Minimum amount of code changed to give baseline
        1. Ease of implementation
    1. Instrumentation
        1. In-situ fourier transform   
    1. Cross-sections using protobuf
5. Future prospects
    1. Adaptive acceleration schemes
