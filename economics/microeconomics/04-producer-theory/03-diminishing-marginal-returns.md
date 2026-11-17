# Diminishing marginal returns

**Prerequisites:** [Production functions](02-production-functions.md).

![Anne-Robert-Jacques Turgot, portrait by Joseph Ducreux; Turgot described diminishing returns in agriculture in the 1760s](images/03-diminishing-marginal-returns.jpg)

*Anne-Robert-Jacques Turgot, portrait by Joseph Ducreux; Turgot described diminishing returns in agriculture in the 1760s. Credit: Joseph Ducreux. License: Public domain. Source: [File:Joseph Ducreux - Portrait of Anne Robert Jacques Turgot, Controller-General of France.jpg](https://commons.wikimedia.org/wiki/File:Joseph_Ducreux_-_Portrait_of_Anne_Robert_Jacques_Turgot,_Controller-General_of_France.jpg).*

If you keep adding workers to a single kitchen, at some point each extra worker adds less output than the one before. This is the **law of diminishing marginal returns**: when one input is increased while others are held fixed, the marginal product of the variable input eventually declines. It is one of the oldest ideas in economics and the reason short-run cost curves slope upward.

## Statement

Holding all other inputs and technology constant, as more of a variable input is added, a point is eventually reached beyond which the marginal product of that input falls.

Three things are essential to the statement:

1. **At least one input is fixed.** Diminishing returns is a short-run phenomenon. If all inputs increase together, the question is about **returns to scale**, a different idea.
2. **Technology is constant.** A new oven design could raise the output of every worker.
3. **"Eventually"**: marginal product can rise at first, as the bakery example showed, before it falls.

It does not say that adding workers reduces total output. Total output can keep rising, just by smaller amounts. Only when marginal product turns negative (workers literally get in each other's way enough to reduce output) does total output fall.

## History: land and food

The law was first formulated for agriculture. In the 1760s the French economist and administrator Anne-Robert-Jacques Turgot described how successive applications of labour and capital to the same piece of land yield first increasing and then decreasing increments of produce. In 1815 several British economists, including Thomas Malthus, David Ricardo, Edward West and Robert Torrens, independently used diminishing returns on land to explain rent and the effects of the Corn Laws, which restricted grain imports.

Malthus had earlier argued, in *An Essay on the Principle of Population* (1798), that population tends to grow faster than food supply. Diminishing returns in agriculture was part of the reasoning: adding more labourers to a fixed amount of land would raise output by less and less, pushing wages toward subsistence. History has not followed Malthus's prediction for most of the world since the 19th century, mainly because technology (new crops, fertilisers, machinery, the Green Revolution) kept shifting the agricultural production function upward. Diminishing returns holds **with technology fixed**; technology has not stayed fixed.

## Worked example: fertiliser

A farmer applies fertiliser to one hectare of wheat:

| Bags of fertiliser | Yield (tonnes) | Marginal product (tonnes per bag) |
|---|---|---|
| 0 | 3.0 | – |
| 1 | 4.0 | 1.0 |
| 2 | 4.7 | 0.7 |
| 3 | 5.1 | 0.4 |
| 4 | 5.3 | 0.2 |
| 5 | 5.35 | 0.05 |

If wheat sells for 300 dollars a tonne and a bag costs 90 dollars, how much fertiliser should she use? Apply [marginal thinking](../01-foundations/05-marginal-thinking.md):

- Bag 1: extra revenue 1.0 × 300 = 300 > 90. Use it.
- Bag 2: 0.7 × 300 = 210 > 90. Use it.
- Bag 3: 0.4 × 300 = 120 > 90. Use it.
- Bag 4: 0.2 × 300 = 60 < 90. Stop.

She should apply **3 bags**. The marginal revenue product of fertiliser (marginal product times price) falls because of diminishing returns, and she stops when it drops below the price of a bag. The same logic determines how many workers a firm hires, as shown in [labour demand](../06-factor-markets/02-labour-demand.md).

```mermaid
flowchart LR
  F["Fixed input: land, oven, factory"] --> V["Add more variable input"]
  V --> E["Early: specialisation, rising marginal product"]
  E --> D["Later: crowding, falling marginal product"]
  D --> C["Rising marginal cost of output"]
```

## From diminishing returns to rising costs

Diminishing marginal returns has a direct consequence for costs. If each extra worker adds less output, then each extra unit of output requires more workers, and so costs more. In the bakery example, when the fifth baker adds only 20 loaves and costs 160 dollars a day, the marginal cost of a loaf is 160/20 = 8 dollars. When the third baker added 60 loaves for the same wage, the marginal cost was only 160/60 ≈ 2.67. Falling marginal product means rising marginal cost:

**Marginal cost = wage / marginal product of labour**

This is why short-run supply curves slope upward, the link drawn in [short-run costs](05-short-run-costs.md).

## Diminishing returns everywhere

The principle applies far beyond farms and factories:

- **Studying**: the fifth hour of revision in a day usually adds less than the first.
- **Advertising**: the first ads reach new customers; later ones mostly reach people who have already seen them.
- **Software teams**: Fred Brooks observed in *The Mythical Man-Month* (1975) that adding programmers to a late software project tends to make it later, because new people must be trained and communication overhead grows. That is diminishing, even negative, marginal returns to labour with a fixed project structure.

## Key ideas

- With some inputs fixed, adding more of a variable input eventually yields smaller increments of output.
- It is a short-run law; increasing all inputs is a question of returns to scale.
- Turgot, Malthus, Ricardo and others developed it for agriculture.
- Technological progress shifts production up and has outrun diminishing returns historically.
- Diminishing marginal returns implies rising marginal cost: MC = w / MPL.

## Where this leads

- Next: [isoquants and input choice](04-isoquants-and-input-choice.md).
- Then: [short-run costs](05-short-run-costs.md).
- Glossary: [diminishing marginal returns](../glossary/diminishing-marginal-returns.md), [marginal product](../glossary/marginal-product.md), [returns to scale](../glossary/returns-to-scale.md).
