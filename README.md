# Time-Series
Rossman Store Sales Analysis

This analysis is based on the Kaggle data challenge to forecast Rossman Store's sales using store, promotion, and competitor data. This projects consists of three parts:

Part A - Exploratory Data Analysis

Part B - Time Series Analysis & Predictive Modelling

Part C - Results & Conclusions


 ARMA Model Results                              
==============================================================================
Dep. Variable:                  Sales   No. Observations:                  942
Model:                     ARMA(6, 1)   Log Likelihood              -15284.825
Method:                       css-mle   S.D. of innovations        2692464.431
Date:                Tue, 01 Feb 2022   AIC                          30587.649
Time:                        18:46:39   BIC                          30631.281
Sample:                    01-01-2013   HQIC                         30604.280
                         - 07-31-2015                                         
===============================================================================
                  coef    std err          z      P>|z|      [0.025      0.975]
-------------------------------------------------------------------------------
const        6.235e+06   5.67e+04    109.973      0.000    6.12e+06    6.35e+06
ar.L1.Sales    -0.6391      0.034    -18.873      0.000      -0.705      -0.573
ar.L2.Sales    -0.1180      0.035     -3.414      0.001      -0.186      -0.050
ar.L3.Sales    -0.0375      0.035     -1.081      0.280      -0.106       0.031
ar.L4.Sales    -0.0943      0.035     -2.720      0.007      -0.162      -0.026
ar.L5.Sales    -0.2393      0.035     -6.910      0.000      -0.307      -0.171
ar.L6.Sales    -0.4800      0.029    -16.548      0.000      -0.537      -0.423
ma.L1.Sales     0.6826      0.025     26.962      0.000       0.633       0.732
                                    Roots                                    
=============================================================================
                  Real          Imaginary           Modulus         Frequency
-----------------------------------------------------------------------------
AR.1           -0.9750           -0.4477j            1.0729           -0.4315
AR.2           -0.9750           +0.4477j            1.0729            0.4315
AR.3           -0.2162           -1.1313j            1.1518           -0.2801
AR.4           -0.2162           +1.1313j            1.1518            0.2801
AR.5            0.9420           -0.6905j            1.1680           -0.1007
AR.6            0.9420           +0.6905j            1.1680            0.1007
MA.1           -1.4651           +0.0000j            1.4651            0.5000



![image](https://user-images.githubusercontent.com/82521644/151977981-f5dc3de5-a1e3-49a1-ae3d-4f9eaedd7920.png)
