# The efficient market hypothesis

**Prerequisites:** [Market indices](../04-markets/06-market-indices.md), [Probability and expected value](../01-foundations/08-probability-and-expected-value.md).

![Eugene Fama at the 2013 Nobel Prize ceremonies; his 1970 review defined the efficient market hypothesis](images/04-the-efficient-market-hypothesis.jpg)

*Eugene Fama at the 2013 Nobel Prize ceremonies; his 1970 review defined the efficient market hypothesis. Credit: Bengt Nyman. License: [CC BY 2.0](https://creativecommons.org/licenses/by/2.0). Source: [File:Eugene Fama at Nobel Prize, 2013.jpg](https://commons.wikimedia.org/wiki/File:Eugene_Fama_at_Nobel_Prize,_2013.jpg).*

Do market prices already include everything known? The **efficient market hypothesis** (EMH) says largely yes: prices reflect available information so quickly that it is hard to consistently profit from it. It is one of the most influential, and most debated, ideas in finance.

## Origins: random walks

In 1900, the French mathematician Louis Bachelier, in his thesis *Théorie de la spéculation*, modelled price changes as a random process. Later statisticians, including Maurice Kendall in 1953, found that stock price changes appeared to follow no predictable pattern. This is the **random walk**: tomorrow's change is independent of today's. The conclusion is not that prices are arbitrary, but the opposite: if prices reflect all current information, then they change only when *new* information arrives, and news is by nature unpredictable. A market where price changes are predictable would offer easy profit, which competition would eliminate.

Eugene Fama organised the idea in 1970 in "Efficient Capital Markets: A Review of Theory and Empirical Work". Fama shared the 2013 Nobel Memorial Prize with Robert Shiller, who argued the opposite case (see below), and Lars Peter Hansen.

## Three forms

- **Weak form:** prices reflect all past price and volume data. Technical analysis (chart reading) cannot earn excess returns.
- **Semi-strong form:** prices reflect all *public* information (earnings, news, announcements). Fundamental analysis cannot earn excess returns.
- **Strong form:** prices reflect *all* information, including private. Even insiders cannot profit. This form is clearly false: insider trading is illegal because it can be profitable.

"Excess" means after adjusting for risk and costs. EMH does not say prices are always right, nor that investors earn nothing: it says expected returns compensate for risk, and **no free lunch** exists for most people.

## Evidence for

- **Active managers on average do not beat the market after fees,** as in the SPIVA reports; see [active versus passive investing](05-active-versus-passive-investing.md).
- **Event studies** show prices react almost instantly to news such as earnings announcements and mergers.
- **Little persistence** in manager outperformance.
- **Luck explains winners.** If 10,000 managers each have a 50% chance each year of beating the market by luck alone, the chance a given one does so 10 years in a row is 0.5^10 = 0.098%, so we expect about 10 of the 10,000 to have such a streak by chance alone. Hence a streak is weak evidence of skill.

## Evidence against (anomalies and behavioural critiques)

- **Momentum:** past winners continued to outperform past losers over the following months (Jegadeesh and Titman, 1993).
- **Value and size effects:** cheap stocks and small stocks have earned higher average returns; whether this is a premium for risk or a mispricing is debated; see [factor investing](07-factor-investing.md).
- **Excess volatility:** Robert Shiller (1981) argued stock prices fluctuate more than changes in subsequent dividends can justify.
- **Bubbles and crashes:** the dot-com boom and the 2008 financial crisis are cited as evidence that prices can depart from fundamentals for years; see [the dot-com bubble](../08-history/10-the-dot-com-bubble.md) and [behavioural finance](../07-behavioural-finance/README.md).
- **Limits to arbitrage:** Shleifer and Vishny argued that even if mispricings exist, trading against them is risky and costly ("markets can stay irrational longer than you can stay solvent", a saying often attributed to Keynes, though the attribution is doubtful).

## The Grossman–Stiglitz paradox

If prices fully reflected all information, nobody would pay to gather information, but then prices could not reflect it. Sanford Grossman and Joseph Stiglitz (1980) concluded that markets must be *inefficient enough* to reward the costs of research. The resulting view: markets are **mostly efficient**, with competition ensuring that the rewards from analysis are about equal to its costs, which is why average active management does not beat passive investing after costs.

## Joint hypothesis problem

Testing EMH requires a model of what returns *should* be for the risk taken (like [CAPM](03-capm-and-beta.md)). If a test finds excess returns, either the market is inefficient or the model of risk is wrong, and there is no way to know which. This **joint hypothesis problem**, stressed by Fama, makes decisive tests very difficult.

## Practical lessons

1. **Beating the market is hard.** Treat claims of easy superior returns with suspicion.
2. **Low-cost diversification** is a sensible default, especially since costs are the one thing you can control.
3. **Prices are informative, but not infallible.** Efficiency does not mean prices cannot crash: efficient markets can also fall sharply when bad news arrives.
4. **Do not confuse a good company with a good stock:** the price already reflects what is known about it.
5. **Hedge your own overconfidence:** see [overconfidence and other biases](../07-behavioural-finance/03-overconfidence-and-other-biases.md).

```mermaid
flowchart LR
  N["New information arrives"] --> P["Prices adjust quickly"]
  P --> U["Future changes unpredictable: random walk"]
  U --> E["Hard to beat the market consistently after costs"]
  E --> L["Rational response: low-cost diversified investing"]
```

## Key ideas

- EMH holds that prices reflect available information, so price changes follow news and are unpredictable.
- It comes in weak, semi-strong and strong forms; the strong form is clearly false.
- Evidence favours broad efficiency (managers' record), with anomalies such as momentum, value and bubbles still debated.
- Grossman–Stiglitz: markets must be inefficient enough to pay for research, so "mostly efficient" is a sensible summary.

## Where this leads

- Next: [active versus passive investing](05-active-versus-passive-investing.md).
- Related: [behavioural finance](../07-behavioural-finance/README.md), [index funds](../03-securities/03-funds/03-index-funds.md).
- Glossary: [efficient market hypothesis](../glossary/portfolio-theory/efficient-market-hypothesis.md), [random walk](../glossary/portfolio-theory/random-walk.md), [anomaly](../glossary/portfolio-theory/anomaly.md), [technical analysis](../glossary/portfolio-theory/technical-analysis.md), [fundamental analysis](../glossary/portfolio-theory/fundamental-analysis.md), [momentum](../glossary/portfolio-theory/momentum.md), [limits to arbitrage](../glossary/behavioural-finance/limits-to-arbitrage.md).
