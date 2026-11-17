# From individual to market demand

**Prerequisites:** [Optimal choice](06-optimal-choice.md), [Income and substitution effects](08-income-and-substitution-effects.md), [Demand](../02-supply-and-demand/01-demand.md).

![A busy crowd at St Albans market: market demand adds up the choices of many individual buyers](images/10-from-individual-to-market-demand.jpg)

*A busy crowd at St Albans market: market demand adds up the choices of many individual buyers. Credit: James Ó Nuanáin. License: [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0). Source: [File:Busy crowd on Market Place at St Albans Market.jpg](https://commons.wikimedia.org/wiki/File:Busy_crowd_on_Market_Place_at_St_Albans_Market.jpg).*

Consumer theory explains a single person's choices. Markets are made of many people. This lesson shows how to get from individual demand curves, derived from preferences and budgets, to the **market demand curve** used in supply-and-demand analysis.

## Deriving an individual demand curve

Hold income and the price of other goods fixed, and vary the price of one good. At each price, find the consumer's optimal bundle. Plotting the price against the optimal quantity traces the **individual demand curve**. The path of optimal bundles on the indifference-curve diagram as the price changes is called the **price-consumption curve**.

For Lena (U = x × y, income 60), coffee demand is x = 30 / Px:

| Price of coffee | Coffees demanded |
|---|---|
| 1 | 30 |
| 2 | 15 |
| 3 | 10 |
| 5 | 6 |
| 6 | 5 |

Her spending on coffee is always 30, so her demand is **unit elastic** at every price.

## Adding up: horizontal summation

The **market demand curve** is the **horizontal sum** of individual demand curves: at each price, add the quantities everyone demands.

Suppose the market has three buyers:

| Price | Lena | Omar | Priya | Market |
|---|---|---|---|---|
| 1 | 30 | 20 | 8 | 58 |
| 2 | 15 | 14 | 6 | 35 |
| 3 | 10 | 8 | 4 | 22 |
| 5 | 6 | 0 | 0 | 6 |

At 5 dollars, only Lena buys; Omar and Priya are priced out. That is a general reason market demand slopes down even more reliably than individual demand: as price falls, existing buyers buy more **and** new buyers enter the market. Even if each person bought just one unit or none (like a car or a fridge), market demand would slope down because people have different willingness to pay.

```mermaid
flowchart LR
  P["Preferences + income + prices"] --> O["Each person's optimal choice"]
  O --> I["Individual demand curves"]
  I --> H["Add quantities at each price (horizontal sum)"]
  H --> M["Market demand curve"]
```

## What shifts market demand

Market demand depends on everything that shapes individual demands, plus the number and composition of buyers:

- **Population** and its age structure (more retirees raise demand for health care and travel).
- **Income distribution.** If income shifts from people who spend it on one good to people who spend it on another, market demand changes even if total income is the same.
- **Tastes**, which can spread through a population.

## Network and interdependent demand

Horizontal summation assumes each person's demand is independent of others'. For goods with **network effects** (messaging apps, payment systems), or with bandwagon and snob effects, one person's demand depends on how many others buy. Then the market demand curve cannot simply be summed; it must account for feedback. Harvey Leibenstein's 1950 analysis showed that bandwagon effects make market demand more elastic than the simple sum suggests and snob effects make it less elastic.

## Aggregation: a caution

Can a whole market behave like a single rational consumer? Not necessarily. Results from the 1970s associated with Hugo Sonnenschein, Rolf Mantel and Gérard Debreu showed that, without strong restrictions, aggregate demand need not inherit all the tidy properties of individual demand, except a few basic ones. In practice, economists often use a "representative consumer" as a simplification, aware that it is one. For ordinary market analysis of a single good, the downward slope of market demand is well supported by evidence.

## From demand to welfare

Because each point on the market demand curve represents the marginal buyer's willingness to pay, the area under the market demand curve and above price is total [consumer surplus](../02-supply-and-demand/09-consumer-surplus.md). This links the preference-based theory of this section back to the welfare analysis of taxes, subsidies and price controls in the supply-and-demand section.

## Key ideas

- An individual demand curve comes from varying a good's price and finding the optimal bundle each time.
- Market demand is the horizontal sum of individual demands.
- Market demand slopes down because existing buyers buy more and new buyers enter as price falls.
- Network effects make demands interdependent, complicating aggregation.
- Aggregate demand need not behave like one rational consumer, but the downward slope is well supported.

## Where this leads

- Next: [choice under uncertainty](11-choice-under-uncertainty.md).
- Glossary: [[g:demand-curve|demand curve]], [[g:network-effect|network effect]], [[g:representative-agent|representative agent]].
