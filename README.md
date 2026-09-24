# Statistical Analysis of Chicken Weight Using Factorial Design

This project investigates how different feeding conditions affect chicken
weight using a **2 × 3 × 2 factorial experimental design**.

The analysis was conducted in **R** and examines both main effects and
interaction effects among feeding factors.

## Objective

The study addresses two main questions:

1. How do protein source, protein level, and fish-solubles level affect
   chicken weight?
2. Do these factors act independently, or do they interact?

## Experimental Design

Three factors were investigated:

- **Protein source:** Groundnut vs. Soybean
- **Protein level:** Low, Medium, High
- **Fish-solubles level:** Two levels
- **Response variable:** Chicken weight (grams)

A 2 × 3 × 2 factorial design with two replicates was used.

## Statistical Methods

The analysis includes:

- Exploratory data analysis
- Factorial design
- Interaction plots
- Multiple linear regression
- ANOVA
- Model comparison and selection
- Residual diagnostics
- Tukey multiple comparisons
- Bonferroni-adjusted comparisons

## Key Findings

The selected model was:

`Weight ~ Protein + LP + LS + Protein:LP`

The model explained approximately **65.3% of the variation in chicken
weight (R² = 0.653)** and was statistically significant overall
(**p < 0.001**).

Key results included:

- **Protein level (LP):** statistically significant
- **Fish-solubles level (LS):** statistically significant
- **Protein × Protein Level interaction:** statistically significant
- **Protein source:** marginal evidence of a main effect (p ≈ 0.054)

The Protein × Protein Level interaction suggests that the effect of
protein level on weight depends on the protein source.

Post-hoc analysis found the clearest pairwise difference between the two
fish-solubles levels.

## Tools

- R
- Regression Modeling
- ANOVA
- Factorial Experimental Design
- Tukey HSD
- Bonferroni Adjustment
- Statistical Diagnostics

## Full Report

https://github.com/Therancearizi/chicken-weight-factorial-design/blob/main/Statistical%20Analysis%20of%20Chicken%20Weight%20Using%20Factorial%20Design.pdf

The report contains the experimental design, statistical models,
diagnostic plots, model comparisons, post-hoc analysis, conclusions,
and recommendations.
