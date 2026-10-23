# -econ3916-lab09-ab-testing
# A/B Testing — Designing the Data-Generating Process

## Objective
In this lab, I explored how A/B testing can measure the effects of an intervention, how selection bias can affect results, and how to determine the sample size needed for an experiment.

## Methodology
- Loaded the LaLonde NSW job training dataset with 445 people, including 185 trainees and 260 controls.
- Calculated the average treatment effect (ATE) to measure how job training affected earnings.
- Simulated an observational comparison group to see how selection bias can change the results.
- Used a permutation test with 9,999 shuffles to test whether the earnings difference was statistically significant.
- Calculated a 95% bootstrap BCa confidence interval to estimate the range of possible effects.
- Performed a power analysis to evaluate the experiment and estimate the sample sizes needed to detect different effects.
- Analyzed the Cookie Cats A/B test with 90,189 players to compare Day-1 retention between gates
