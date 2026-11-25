# The evidence hierarchy

**Prerequisites:** [Odds ratios and hazard ratios](../02-statistics/19-odds-ratios-and-hazard-ratios.md) and [Observation, measurement and experiment](../01-foundations/03-observation-measurement-and-experiment.md).

![A common pyramid of evidence, from expert opinion at the base to systematic reviews at the top](images/01-the-evidence-hierarchy.jpg)

*A common pyramid of evidence, from expert opinion at the base to systematic reviews at the top. Credit: Jmarchn. License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0). Source: [File:Hierarchy of Evidence-en.svg](https://commons.wikimedia.org/wiki/File:Hierarchy_of_Evidence-en.svg).*

Not all studies are equally good at answering every question. The **evidence hierarchy**, often drawn as a pyramid, ranks study designs by how well they protect against bias when the question is whether something *causes* something else. It is a useful first map, provided you remember what it leaves out.

## The classic pyramid

From weakest to strongest for questions about the effects of treatments:

1. **Expert opinion, mechanistic reasoning, laboratory and animal studies**
2. **Case reports and case series**: descriptions of individual patients ([lesson](02-case-reports-and-case-series.md))
3. **Ecological and cross-sectional studies**: comparisons of populations or snapshots ([ecological](03-ecological-studies.md), [cross-sectional](04-cross-sectional-studies.md))
4. **Case-control studies**: comparing people with and without an outcome ([lesson](05-case-control-studies.md))
5. **Cohort studies**: following exposed and unexposed people forward ([lesson](06-cohort-studies.md))
6. **Randomised controlled trials** ([lesson](07-randomised-controlled-trials.md))
7. **Systematic reviews and meta-analyses** of the above, especially of RCTs ([systematic reviews](14-systematic-reviews.md), [meta-analysis](15-meta-analysis.md))

```mermaid
flowchart TB
  SR["Systematic reviews and meta-analyses"] --> RCT["Randomised controlled trials"]
  RCT --> CO["Cohort studies"]
  CO --> CC["Case-control studies"]
  CC --> CS["Cross-sectional and ecological studies"]
  CS --> CR["Case reports and case series"]
  CR --> EO["Expert opinion, mechanisms, lab and animal work"]
```

The reasoning is that each step up adds protection against a source of error: a comparison group, then a time order, then randomisation, then pooling across many studies.

The modern hierarchy grew out of the **evidence-based medicine** movement. Archie Cochrane's 1972 book *Effectiveness and Efficiency* argued that health services should rely on randomised trials. In the early 1990s a group at McMaster University in Hamilton, Ontario, led by Gordon Guyatt and David Sackett, popularised the term "evidence-based medicine" in a 1992 *JAMA* article.

## What the pyramid gets right

For questions about whether an intervention works, randomisation really is a huge advantage, because it balances unknown as well as known confounders. Repeatedly, treatments that looked beneficial in observational studies failed in trials. The [hormone replacement therapy](../10-case-studies/04-hormone-replacement-therapy-and-the-whi.md) story and the beta-carotene and vitamin E trials of the 1990s are classic examples.

## What the pyramid gets wrong

Treat the hierarchy as a rule of thumb, not a ranking you can apply mechanically:

- **Design is not quality.** A badly run RCT, with poor concealment of allocation, heavy dropout or a switched outcome, can be worse than a careful cohort study. The [GRADE](16-cochrane-and-grade.md) system explicitly lets evidence be downgraded or upgraded from its starting level.
- **Different questions need different designs.** For rare or long-term harms, large observational studies and surveillance systems are often the *only* evidence, because trials are too small and short. For diagnostic accuracy, prognosis, or how common a disease is, the hierarchy looks different.
- **Some questions cannot ethically be randomised.** Nobody will randomise people to smoke. The case against tobacco was built on observational studies, mechanism and convergence ([tobacco case study](../10-case-studies/01-tobacco-industry-research.md)).
- **Very large effects need less.** The 2003 *BMJ* spoof by Gordon Smith and Jill Pell, "Parachute use to prevent death and major trauma related to gravitational challenge: systematic review of randomised controlled trials", found no RCTs of parachutes and wryly suggested that advocates of evidence-based medicine volunteer for one. The point: when effects are dramatic and mechanisms obvious, demanding an RCT is unreasonable.
- **Meta-analyses inherit the flaws of their inputs.** Pooling biased studies produces a precise biased answer.

Some writers therefore draw the pyramid with wavy lines between levels, or replace it with a framework that rates each body of evidence on its own merits, as GRADE does.

## Matching design to question

| Question | Best primary designs |
|---|---|
| Does treatment X work? | RCTs, systematic reviews of RCTs |
| Does exposure X cause disease Y? (can't randomise) | Cohort and case-control studies, natural experiments |
| Does X cause a rare harm? | Large cohort studies, case-control, self-controlled case series, surveillance |
| How common is Y? | Cross-sectional surveys of representative samples |
| How accurate is test T? | Diagnostic accuracy studies against a reference standard |
| What is it like to live with Y? | Qualitative research (interviews, focus groups) |
| Is this a new phenomenon? | Case reports and case series |

## Key ideas

- The evidence hierarchy ranks designs by protection against bias for causal questions.
- Randomisation and systematic pooling put RCTs and meta-analyses at the top.
- Quality within a design matters as much as the design itself.
- Rare harms, unethical exposures and dramatic effects need other kinds of evidence.
- Match the design to the question.

## Where this leads

- Next: [Case reports and case series](02-case-reports-and-case-series.md)
- Synthesis: [Cochrane and GRADE](16-cochrane-and-grade.md)
