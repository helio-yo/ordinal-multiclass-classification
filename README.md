# Ordinal and Multiclass Classification with GLMs

This project analyzes factors associated with students’ interest in applying
to graduate studies using generalized linear models.

The response variable is ordinal with three levels:
*unlikely*, *somewhat likely*, and *very likely*.

## Data

The dataset contains information from 400 university students, including:
- Type of university (public vs private)
- Parental education (postgraduate degree or not)
- Current GPA

## Exploratory Analysis

- Relative frequency plots show differences in application interest
  across parental education and university type.
- GPA distributions overlap across interest levels, with a mild shift
  toward higher values for students with stronger interest.

## Modeling Strategy

1. Multinomial logistic regression with and without interactions
2. Model comparison using likelihood ratio tests and AIC
3. Ordinal cumulative logit models
4. Assessment of the proportional odds assumption

## Interpretation

Higher GPA is associated with a higher probability of strong interest
in graduate studies. Parental postgraduate education and university type
also shift the probability distribution across interest levels.

## Visualization

Predicted probabilities are presented as functions of GPA, holding
parental education and university type fixed.

## Tools

R · VGAM · ggplot2 · dplyr
