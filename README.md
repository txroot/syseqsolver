##**syseqsolver**
Linear Equations System Solver (unique solution and equations = unknowns)

**Class linearEqSystem:**

*Method addEquation:*
To add a new equation

*Method buildSystem:*
Creates the needed matrices to use in the solve function

*Method remEquation:*
Remove just the indicated equation

*Method cleanEquations:*
Remove all equations

**Solver function:**

    @param {math.Matrix} coefMatrix   Coefficients Matrix (An)
    @param {math.Matrix} consMatrix    Constants Matrix (Bn)
    @param {math.Matrix} varMatrix    Variable Matrix (Xn)
    @param {int} decPlaces    Desired Decimal Places
    @returns {math.Matrix}    Code Error: 0 - Success; 1 - Error; 2 - Overflow.
    @returns {math.Matrix}    Solution Matrix



**Prettify function**

    @param {*} inpNumber   Input number to prettify
    @param {int} outRepres    Desired Output Representation: 0 - Cartesian; 1 - Polar; 2 - Exponential.
    @param {int} outFormat    Output format: 0 - Plain Text; 1 - TeX Format.
    @param {int} decPlaces    Desired Decimal Places
    @returns {string}    Return a Prettified Number
