# Rubric for the _generalized linear models_ exercises

## 1. Logistic regression with one predictor

 - [ ] The binned proportions are calculated and visualized with the raw data appropriately, and the pattern is described reasonably, including which bins are too small to be reliable
 - [ ] The logistic model is fit correctly, with the binomial family and logit link
 - [ ] The slope is interpreted correctly on the log odds scale, with units
 - [ ] The hypotheses and p-value are interpreted correctly
 - [ ] The predicted probabilities are calculated with a prediction grid and overlaid on the raw data appropriately
 - [ ] The predicted probability for a 100-year-old home is reported correctly
 - [ ] The changes in probability are calculated correctly, and the difference between them is explained using the shape of the S-curve

## 2. Logistic regression with multiple predictors

 - [ ] The model is fit correctly
 - [ ] The `home_age` and `dist_exide_km` coefficients are interpreted correctly, with units, holding the other predictors constant
 - [ ] The significance of each coefficient is interpreted correctly
 - [ ] The `home_age` coefficients from the two models are compared appropriately
 - [ ] The predictions are calculated with a prediction grid that includes every predictor, and visualized appropriately with one curve per area
 - [ ] The advice to the resident is reasonable and based on the predictions
 - [ ] The non-significant distance effect is interpreted appropriately (absence of evidence is not evidence of absence), with reference to the range of distances in the data

## 3. Simulate data for a Poisson regression

 - [ ] The parameter table is completed correctly, with reasonable signs and magnitudes
 - [ ] The predictor and response are simulated correctly, with the expected count exponentiated from the log scale
 - [ ] The Poisson model is fit correctly to the simulated data
 - [ ] The true and estimated parameters are compared on both the log and multiplicative scales
 - [ ] The distance effect is interpreted correctly as a multiplicative effect on the expected count, and parameter recovery is assessed using the standard errors
 - [ ] The simulation is visualized appropriately, with the simulated data, a curve for the simulation parameters, and a curve for the fitted model
