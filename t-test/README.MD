### P-value

- a **low p-value** can give statistical evidence to **support rejecting the null hypothesis** (however, does not prove the alt hyp is true)
- if alpha is 0.05, then 5% change of incorrectly rejecting the null hypothesis
- Shapiro-Wilk (normality test) - null hypothesis is that the population is normally distributed
  - If data is not normal (p < 0.05) these are non-parametric equivalents of Student test:
    - Mann-Whitney test (independent groups)
    - Wilcoxon signed rank test (related groups)
- Effect size benchmarks **none (d < 0)**, **small (d = 0.2)**, **medium (d = 0.5)**, and **large (d = 0.8)**

### Paired Samples T-Test Example

In the analysis below:

 - the null hypothesis (moon vs other behavoir is the same) - **p < 0.001** so we reject the null hypothesis
 - the Shapiro-Wilk null hypothesis is that the data is normally distributed - **p = 0.148** so we do not reject the null hypothesis

![paired-t-test](./paired-t-test.png)

- See [also](https://stats.stackexchange.com/questions/502637/p-value-for-shapiro-wilk-is-high-but-data-doesnt-appear-normal)


