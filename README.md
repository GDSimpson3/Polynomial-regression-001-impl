<h1 align='center'>Polynomial Regression 001 IMPL</h1>
<h5 align='right'>2025 December</h5>


NOTE: REFER **README.PDF**, THATS THE UPTODATE DOCUMENTATION FOR THIS PROJECT

<h1>Versions</h1>

<h2>NTerms</h2>

<h3>STAGE 3</h3>
Added L1 Regularisation and Dynamic Pruning to eliminate non-essential Terms

<h3>STAGE 2</h3>
Added Normalisation and Exponent Clamping

<h3>STAGE 1</h3>
Simple NSLOTS NPARAM Dynamic Polynomial Regression with Learnable Exponents (NTERMS Is a static constant)


<h3>Full File Dictionary for NTerms</h3>

- STAGE-1-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM.ipynb
- HALF-STAGE2-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM.ipynb
- STAGE-2-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM-Normalisation-Clamping.ipynb
- STAGE-2.1-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM-SinX-150000.ipynb
- STAGE-3-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM-L1-Regularisation.ipynb
- STAGE-3.1-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM-L1-Regularisation-Optimised.ipynb
- STAGE-3.2-ATTP001_Polynomial_regression_impl_001_Dynamic_Exponents_NSLOTS_NPARAM-Params-tweaked.ipynb



<h2>StaticTerms</h2>
These are simply regression line equasions that have Parameterised Coefficients and **Learnable Exponents**. Though there are a fixed number of terms. (Refer documentation)

The regression line consists of a fixed number of `Cn X ^ En` terms

<h3>Polynomial_regression_impl_001_Dynamic_Exponents_3SLOTS_6PARAM-DSCubic</h3>
3 `Cn X ^ En` terms (6 Parameters) on a Cubic Dataset

<h3>Polynomial_regression_impl_001_Dynamic_Exponents_3SLOTS_6PARAM-DSQuadratic</h3>
3 `Cn X ^ En` terms (6 Parameters) on a Quadratic Dataset

<h3>Polynomial_regression_impl_001_Dynamic_Exponents_3SLOTS_6PARAM-DSSINX</h3>
3 `Cn X ^ En` terms (6 Parameters) on a SinX Dataset

<h3>REV001-Polynomial_regression_impl_001_Dynamic</h3>
3 `Cn X ^ En` terms (6 Parameters)


<h2>Static-Exponents</h2>
These are simply regression line equasions that have Parameterised Coefficients and Fixed Exponents. EG: Quadratic Regression, Cubic Regression

<h3>2 Degrees</h3>

- REV-001-Polynomial_regression_impl_001
- REV-002-Polynomial_regression_impl_001

<h3>3 Degrees</h3>

- Polynomial_regression_impl_001_3DEG_ipynb
