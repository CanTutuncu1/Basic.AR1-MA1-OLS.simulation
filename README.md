# AR(1), MA(1), OLS simulation
Basic AR(1), MA(1) simulation and OLS estimation via MATLAB. This project was prepared for a group homework assignment by me and my groupmates for the class of '20532: Macroeconometrics'.

## Features
In ex1 we generate 500 observations from an AR(1) process with parameters phi = 0.4 and the variance of the white noise set as 0.2. In ex2 we generate data from an AR(1) with phi = 0.6 and the variance of the white noise set as 0.4. We set the starting condition as 20 even though the unconditional expected value is 3 and observe the sample path. In ex3 generate MA(1) process with theta = 0.3 and the variance of the white noise is set as 0.3. In ex4 we generate an ARMA(2,1) process. In ex5a we compute the empirical distributions of the OLS estimator in the case of an AR(1) with phi = 0.4. In ex5b we construct a t-test for the null hypothesis H0: phi = 0 against a two-sided alternative H0: phi =/= 0. In ex6 we compute the empirical distributions of the OLS estimator in the case of an AR(1) with phi = 0.9 with increasing sample sizes T = (50, 100, 200, 1000). In ex7 we compute the empirical distribution of the OLS estimator in the regression xt = axt 1 +vt in the case in which the data generating process for xt is MA(1) with theta = 0.6 and sample size 250.

## Technical Properties
Written in MATLAB R2024b.
