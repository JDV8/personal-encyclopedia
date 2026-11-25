# 2. Statistics for readers

**Prerequisites:** [Foundations](../01-foundations/README.md). Basic arithmetic; no algebra beyond fractions is needed.

The statistical ideas you need to read results sections: distributions, averages and spread, sampling, confidence intervals, p-values and their misuse, power, effect sizes, relative and absolute risk, NNT, base rates and Bayes, diagnostic tests, multiple comparisons, regression to the mean, adjustment, and odds and hazard ratios.

## Contents

1. [Variables and data](01-variables-and-data.md): Variables can be categorical, binary, ordinal, continuous, counts or time-to-event, and each needs different methods.
2. [Probability](02-probability.md): Probability runs from 0 to 1 and can be read as long-run frequency or as degree of belief.
3. [Distributions](03-distributions.md): A distribution describes how values vary: centre, spread, shape and outliers.
4. [Mean, median and mode](04-mean-median-and-mode.md): The mean is the arithmetic average and is pulled by outliers; the median is the middle value and is robust.
5. [Variance and standard deviation](05-variance-and-standard-deviation.md): Spread matters as much as centre.
6. [Samples and populations](06-samples-and-populations.md): A sample is used to estimate parameters of a population.
7. [Standard error and confidence intervals](07-standard-error-and-confidence-intervals.md): The standard error measures how much an estimate would vary across repeated studies.
8. [Hypothesis tests and p-values](08-hypothesis-tests-and-p-values.md): A p-value is the probability of data at least this extreme, assuming the null hypothesis and the model are true.
9. [Misreading p-values](09-misreading-p-values.md): The p-value is not the probability that the result is due to chance or that the hypothesis is false.
10. [Statistical power](10-statistical-power.md): Power is the chance of detecting a real effect of a given size.
11. [Effect sizes](11-effect-sizes.md): Effect sizes measure how big an effect is; p-values do not.
12. [Relative and absolute risk](12-relative-and-absolute-risk.md): Relative risk compares risks as a ratio; absolute risk reduction is the difference.
13. [Number needed to treat and to harm](13-number-needed-to-treat.md): NNT = 1 ÷ absolute risk reduction; NNH = 1 ÷ absolute risk increase.
14. [Base rates and Bayes' theorem](14-base-rates-and-bayes-theorem.md): Bayes' theorem combines prior plausibility with the strength of new evidence.
15. [Sensitivity, specificity and screening](15-sensitivity-and-specificity.md): Sensitivity catches cases; specificity avoids false alarms.
16. [Multiple comparisons](16-multiple-comparisons.md): Many tests at α = 0.05 almost guarantee some false positives.
17. [Regression to the mean](17-regression-to-the-mean.md): Extreme measurements tend to be followed by less extreme ones, without any intervention.
18. [Regression models and adjustment](18-regression-and-adjustment.md): Regression models relate an outcome to predictors; "adjusted" means holding other measured variables constant.
19. [Odds ratios and hazard ratios](19-odds-ratios-and-hazard-ratios.md): Odds are events ÷ non-events; risks are events ÷ everyone.

## Suggested reading order

Lessons 01–08 form a core sequence. After that, 09–13 (interpreting results) and 14–19 (more advanced tools) can be read in any order.

Use the [glossary](../glossary/README.md) for any unfamiliar term.

Previous section: [Foundations](../01-foundations/README.md) · Course overview: [Reading research](../README.md) · Next section: [Study designs and the evidence hierarchy](../03-study-designs/README.md)

## References & further reading

- *The Art of Statistics: Learning from Data*, David Spiegelhalter (Pelican, 2019). **Beginner**
- *How to Lie with Statistics*, Darrell Huff (W. W. Norton, 1954). **Beginner**
- *How to Make the World Add Up* (US title *The Data Detective*), Tim Harford (Bridge Street Press, 2020). **Beginner**
- *Reckoning with Risk: Learning to Live with Uncertainty* (US title *Calculated Risks*), Gerd Gigerenzer (Allen Lane, 2002). **Beginner**
- *How Not to Be Wrong: The Power of Mathematical Thinking*, Jordan Ellenberg (Penguin, 2014). **Beginner**
- *Statistics Done Wrong: The Woefully Complete Guide*, Alex Reinhart (No Starch Press, 2015). **Intermediate**
- *Practical Statistics for Medical Research*, Douglas G. Altman (Chapman & Hall, 1991). **Intermediate**
- *The Theory That Would Not Die*, Sharon Bertsch McGrayne (Yale University Press, 2011). **Beginner**
- *Regression and Other Stories*, Andrew Gelman, Jennifer Hill and Aki Vehtari (Cambridge University Press, 2020). **Advanced**

## Key studies & sources

- Wasserstein RL, Lazar NA. The ASA statement on p-values: context, process, and purpose. *The American Statistician* 2016;70(2):129–133. [doi](https://doi.org/10.1080/00031305.2016.1154108). Six principles on what p-values do and do not mean.
- Greenland S, Senn SJ, Rothman KJ, et al. Statistical tests, P values, confidence intervals, and power: a guide to misinterpretations. *European Journal of Epidemiology* 2016;31:337–350. [doi](https://doi.org/10.1007/s10654-016-0149-3). Lists 25 common misinterpretations.
- Amrhein V, Greenland S, McShane B. Scientists rise up against statistical significance. *Nature* 2019;567:305–307. [doi](https://doi.org/10.1038/d41586-019-00857-9). Comment with more than 800 signatories calling to abandon dichotomous significance.
- Benjamin DJ, Berger JO, Johannesson M, et al. Redefine statistical significance. *Nature Human Behaviour* 2018;2:6–10. [doi](https://doi.org/10.1038/s41562-017-0189-z). 72 authors proposing p < 0.005 for new discoveries; contested by others.
- Button KS, Ioannidis JPA, Mokrysz C, et al. Power failure: why small sample size undermines the reliability of neuroscience. *Nature Reviews Neuroscience* 2013;14:365–376. [doi](https://doi.org/10.1038/nrn3475). Estimated median power of about 21%.
- Simmons JP, Nelson LD, Simonsohn U. False-positive psychology. *Psychological Science* 2011;22:1359–1366. [doi](https://doi.org/10.1177/0956797611417632). Showed how researcher degrees of freedom produce false positives.
