# Ecological studies

**Prerequisites:** [Case reports and case series](02-case-reports-and-case-series.md).

![John Snow's 1854 map of cholera deaths around the Broad Street pump in London](images/03-ecological-studies.jpg)

*John Snow's 1854 map of cholera deaths around the Broad Street pump in London. Credit: John Snow. License: Public domain. Source: [File:Snow-cholera-map-1.jpg](https://commons.wikimedia.org/wiki/File:Snow-cholera-map-1.jpg).*

An **ecological study** compares groups, usually countries, regions or time periods, rather than individuals. "Countries that eat more fat have more heart disease" and "towns with fluoridated water have fewer cavities" are ecological claims. These studies are quick and cheap and can reveal striking patterns, but they are prone to a special error that every reader should know.

## How they work

Ecological studies use aggregate data: national consumption figures, regional disease rates, average incomes. Common forms are:

- **Geographic comparisons:** plotting a rate against an exposure across countries or regions.
- **Time-trend studies:** comparing how an exposure and an outcome change over time in one population.
- **Mixed designs** that combine the two.

A famous example is Ancel Keys's Seven Countries Study, begun in the late 1950s, which compared diet and heart disease across cohorts in seven countries and became central to the idea that saturated fat causes heart disease. (The study combined cohort data within countries with between-country comparisons, and its interpretation remains debated.)

## The ecological fallacy

The central danger is the **ecological fallacy**: inferring that a relationship seen between groups holds for individuals. If countries with more chocolate consumption have more Nobel laureates, it does not follow that chocolate-eaters win Nobel prizes.

That example is real. In 2012 the cardiologist Franz Messerli published a tongue-in-cheek note in the *New England Journal of Medicine* reporting a correlation of r = 0.791 between per-capita chocolate consumption and Nobel laureates per 10 million population across 23 countries. Wealthy countries both consume more chocolate and fund more research; national wealth is a plausible confounder. The paper is now widely used to teach the ecological fallacy, and is the subject of a [worked example](../11-practice/06-worked-example-a-news-story.md) later in the course.

```mermaid
flowchart TB
  W["National wealth"] --> C["Chocolate consumption"]
  W --> N["Nobel laureates per capita"]
  C -.->|"r = 0.79 across countries"| N
  N --> F["Ecological fallacy: no evidence any individual benefits"]
```

The fallacy runs in both directions. A relationship can even reverse between levels. In some elections, richer regions have voted for one party while, within each region, richer individuals voted for the other; the political scientist Andrew Gelman explored this pattern in his book *Red State, Blue State, Rich State, Poor State* (2008).

## Confounding at the group level

Countries and regions differ in countless ways: wealth, healthcare, diet, climate, genetics, record-keeping, age structure. Ecological studies usually have few units (dozens of countries at most) and limited ability to adjust for these differences. Correlations between national averages are also often much stronger than correlations among individuals, because averaging removes individual noise.

## Time trends

Time-trend studies face their own problems. Many things change together over time: diagnostic criteria, awareness, testing, population age and other exposures. When autism diagnoses rose sharply in many countries from the 1990s, ecological comparisons were used to argue for many different causes. Researchers point to broadened diagnostic criteria, increased awareness and better services among the explanations for much of the rise. Similarly, a disease rate can rise because a new test finds more cases.

A useful variation is to check whether trends diverge where exposures diverged. When Japan withdrew the combined MMR vaccine in 1993, a 2005 study by Hideo Honda, Yasuo Shimizu and Michael Rutter of children born from 1988 to 1996 in Kohoku Ward, Yokohama, found that the cumulative incidence of autism spectrum disorders kept rising as MMR use fell to almost nothing, evidence against MMR as a major cause. Such "natural experiment" comparisons are stronger than simple correlations, but still ecological; see [natural experiments](12-natural-experiments-and-quasi-experiments.md).

## When ecological studies are the right tool

Ecological designs are appropriate when:

- the exposure really operates at the group level (laws, taxes, water fluoridation, air pollution, health system policies);
- individual data are unavailable and you need a quick first look;
- you want to generate hypotheses for individual-level studies.

They are weak when the question is about what happens to individuals who are exposed.

## Questions to ask

- Is the conclusion about groups or about individuals?
- What other differences between the groups could explain the pattern?
- How many units are compared, and how were they chosen?
- Could changes in diagnosis, testing or recording explain a time trend?

## Key ideas

- Ecological studies compare groups, not individuals.
- The ecological fallacy is inferring individual relationships from group correlations.
- Group-level confounding is hard to control with few units.
- Time trends are confounded by changes in diagnosis and testing.
- They suit group-level exposures and hypothesis generation.

## Where this leads

- Next: [Cross-sectional studies](04-cross-sectional-studies.md)
- Worked example: [A chocolate and Nobel prize news story](../11-practice/06-worked-example-a-news-story.md)
