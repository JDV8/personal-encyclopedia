# Multiple comparisons

**Prerequisites:** [Hypothesis tests and p-values](08-hypothesis-tests-and-p-values.md) and [Sensitivity and specificity](15-sensitivity-and-specificity.md).

@@IMG@@

If you test one true null hypothesis at α = 0.05, you have a 5% chance of a false positive. If you test twenty, the chance that at least one comes up "significant" by luck is about 64%. This is the **multiple comparisons problem**, and it is behind a remarkable share of false findings.

## The arithmetic

For k independent tests of true null hypotheses, each at α = 0.05:

> P(at least one false positive) = 1 − 0.95ᵏ

- 1 test: 5%
- 5 tests: about 23%
- 20 tests: about 64%
- 100 tests: over 99%

```mermaid
flowchart LR
  A["1 test: 5%"] --> B["5 tests: 23%"]
  B --> C["20 tests: 64%"]
  C --> D["100 tests: over 99%"]
```

The cartoonist Randall Munroe captured this in his *xkcd* strip "Significant" (2011): scientists test whether jelly beans cause acne, find nothing, then test twenty colours separately, find that green jelly beans are "linked" to acne at p < 0.05, and the newspaper headline follows. It is a joke, but it describes a real pattern.

## Where multiple comparisons hide

The problem is obvious when a paper reports twenty tests. It is less obvious when the multiplicity is hidden:

- **Many outcomes:** a trial measures 15 outcomes and highlights the one that was significant.
- **Many subgroups:** the effect is tested in men, women, old, young, diabetic, non-diabetic... ([subgroups](../09-from-lab-to-headline/04-subgroups-and-secondary-analyses.md)).
- **Many time points:** results at 3, 6, 9 and 12 months.
- **Many exposures:** nutritional studies that examine dozens of foods against dozens of diseases.
- **Many analysis choices:** different covariates, outlier rules and model forms. Andrew Gelman and Eric Loken called this the **garden of forking paths**: even if researchers run only one analysis, the choice of which one can depend on the data. See [p-hacking](../06-research-integrity/04-p-hacking.md).

A famous demonstration: in 2009 Craig Bennett and colleagues presented a poster showing apparent "brain activity" in a dead Atlantic salmon shown photographs in an fMRI scanner, an artefact of testing tens of thousands of brain voxels without proper correction. The work later won an Ig Nobel Prize.

## Corrections

Statisticians have developed ways to control the overall error rate:

- **Bonferroni correction:** divide α by the number of tests. With 20 tests, each must reach p < 0.0025. Simple and conservative (it reduces power).
- **Holm's method:** a step-down refinement of Bonferroni that is less conservative.
- **False discovery rate (FDR)** methods, such as the Benjamini-Hochberg procedure (1995): instead of preventing any false positive, they control the expected *proportion* of false positives among significant results. Common in genomics.
- **Hierarchical (gatekeeping) testing:** test outcomes in a pre-specified order and stop at the first non-significant one.

Genome-wide association studies, which test hundreds of thousands to millions of genetic variants, use a conventional threshold of p < 5 × 10⁻⁸ for this reason.

## Pre-specification is the real cure

Statistical correction helps, but the deeper defence is **pre-specification**: naming the primary outcome, the main comparison and the analysis plan before seeing data. A pre-specified primary outcome means one test carries the main conclusion; everything else is explicitly secondary or exploratory. This is why [preregistration](../06-research-integrity/01-preregistration.md) and [trial registries](../06-research-integrity/02-trial-registries.md) matter so much, and why [outcome switching](../06-research-integrity/03-outcome-switching.md) is a serious problem.

## Exploratory research is legitimate

None of this means researchers should not explore data. Exploration generates hypotheses. The problem is presenting exploratory findings as if they were confirmatory tests. A good paper labels them clearly ("exploratory", "hypothesis-generating", "post hoc") and does not build its conclusion on them. A good reader treats them as leads to be tested in new data.

## Questions to ask

- How many outcomes, subgroups, time points and exposures were examined?
- Which was the pre-specified primary outcome, and what did it show?
- Was any correction for multiple testing applied?
- Are the highlighted findings ones that were planned, or ones that turned up?

## Key ideas

- Many tests at α = 0.05 almost guarantee some false positives.
- Multiplicity hides in outcomes, subgroups, time points, exposures and analysis choices.
- Corrections such as Bonferroni and false discovery rate control error rates at the cost of power.
- Pre-specification of one primary outcome is the main defence.
- Exploratory findings are leads, not conclusions.

## Where this leads

- Next: [Regression to the mean](17-regression-to-the-mean.md)
- Related: [P-hacking](../06-research-integrity/04-p-hacking.md), [Outcome switching](../06-research-integrity/03-outcome-switching.md)
