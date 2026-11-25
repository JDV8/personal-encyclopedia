# What epidemiology is

**Prerequisites:** [Infection and transmission](../microbiology/06-infection-and-transmission.md)

![John Snow's 1854 map of cholera deaths around the Broad Street pump in Soho, London, a founding document of epidemiology](images/01-what-epidemiology-is.jpg)

*John Snow's 1854 map of cholera deaths around the Broad Street pump in Soho, London, a founding document of epidemiology. Credit: John Snow. License: Public domain. Source: [File:Snow-cholera-map-1.jpg](https://commons.wikimedia.org/wiki/File:Snow-cholera-map-1.jpg).*

## The study of disease in populations

Medicine usually looks at one patient at a time. **Epidemiology** looks at groups: how often a disease occurs, in whom, where and when, and what makes it more or less likely. It is the science behind nearly every claim in this course about whether a vaccine works or whether it causes a particular harm. Neither question can be answered by looking at one person. If a child develops autism a month after a vaccine, the individual story cannot tell us whether the vaccine caused it, because autism also appears in unvaccinated children at that age. Only comparisons between groups can.

## John Snow and the Broad Street pump

The founding story of the field comes from London in 1854. Cholera was widely blamed on "miasma", bad air. The physician John Snow suspected contaminated water. He mapped cholera deaths in Soho and found them clustered around a public water pump on Broad Street. He also compared households supplied by two water companies, one drawing water from the sewage-polluted Thames downstream, the other upstream; the death rate was far higher among the customers of the downstream company. The pump handle was removed (the outbreak was already declining by then). Snow's methods (counting cases, comparing groups that differ in exposure, thinking about alternative explanations) are still the core of epidemiology.

## The basic questions

```mermaid
flowchart LR
  D[Descriptive:<br/>who, where, when?] --> H[Hypothesis:<br/>what might cause it?]
  H --> A[Analytic:<br/>compare exposed vs unexposed]
  A --> C[Causal inference:<br/>is the link real and causal?]
  C --> I[Intervention:<br/>prevent, then measure again]
  I --> D
```

1. **Descriptive epidemiology** counts cases and describes them by person (age, sex, vaccination status), place and time.
2. **Analytic epidemiology** compares groups to test whether an exposure (a vaccine, a water source, a gene) is associated with an outcome.
3. **Causal inference** asks whether an association reflects cause and effect, or chance, bias or confounding. See [causation and association](06-causation-and-association.md).
4. **Intervention and evaluation**: introduce a measure, then measure again.

## Why vaccines need epidemiology twice

Vaccines raise two separate population questions:

- **Does it work?** Measured by [randomised trials](07-randomised-controlled-trials.md) before licensing and by [observational studies](08-cohort-and-case-control-studies.md) afterwards, giving [efficacy and effectiveness](13-efficacy-effectiveness-and-waning.md) estimates.
- **Is it safe?** Common side effects show up in trials. Rare ones (one in 100,000 or rarer) usually cannot, because trials are too small. They are found by [surveillance](12-surveillance-passive-and-active.md) and by large observational studies that compare the rate of an event after vaccination with its [background rate](11-base-rates-and-coincidence.md).

The same tools are used by everyone in vaccine debates, including critics. Disagreements are often about which study designs are trustworthy, what counts as an adequate control group, and how to handle bias. Learning the tools lets you judge the arguments for yourself rather than taking either side's word.

## Epidemiology's limits

Epidemiology is powerful but not infallible:

- Observational studies can be distorted by **confounding** and **bias**; see [bias and confounding](10-bias-and-confounding.md).
- Very rare effects need enormous populations to detect.
- Studies can show that a risk, if it exists, must be smaller than some amount; they can never prove a risk is exactly zero. This point is used by both sides. Critics note that "no evidence of harm" is not "evidence of no harm". Defenders reply that large studies can show any risk must be very small, and that the same standard applied to any medical product would make every product unprovable. Both are correct about the logic; the practical question is how small a remaining risk is acceptable given the benefits.

## Key ideas

- Epidemiology studies disease in populations; individual stories cannot establish cause.
- John Snow's cholera work set the pattern: count, compare, consider alternatives.
- Vaccines need epidemiology to show both that they work and how often they cause harms.
- Studies can bound a risk but never prove it is zero.

## Where this leads

- Next: [Measuring disease](02-measuring-disease.md).
- Related: the disease itself is covered in [[cholera|the cholera overview]].
