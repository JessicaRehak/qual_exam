# Qual presentation Outline

1. Background
    1. Transport equation
        1. fixed source
        2. discretization
        3. _k_-eigenvalue equation
    2. Issues with solving the TE
        1. Scattering ratio/dominance ratio
    3. The SN Equations
    4. Makeup of an "iteration"
        1. Inner iteration, outer iteration
        2. Convergence
2. Acceleration Methods
    1. Nonlinear diffusion acceleration
        1. LONDA
        2. Drift diffusion term
        3. Solve order (flow chart?)
    2. Transport-Two-grid method
    3. Combination of NDA + Two-grid
3. Analysis of Acceleration Methods
    1. Measurements of successful acceleration
        1. Use of iterations
        2. Difficulty in identifying success
        3. Use of Fourier analysis
4. BART
    1. Second order forms of Transport Equation
        1. SAAF Equation
        2. Mention Even/Odd Parity
    2. Polymorphism
        1. Minimum amount of code changed to give baseline
        2. Ease of implementation
    3. Instrumentation
        1. In-situ Fourier transform   
    4. Cross-sections using protobuf [may not need this part?]
5. Future prospects
    1. Adaptive acceleration schemes
