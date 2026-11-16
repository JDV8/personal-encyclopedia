# Earnings and earnings per share

**Prerequisites:** [The income statement](../../02-firms-and-capital/05-the-income-statement.md), [What a share is](01-what-is-a-share.md).

![An option warrant for 1,000 Reichsmark of Vereinigte Stahlwerke AG, dated 1 July 1926, from the EDHAM historical share museum](images/05-earnings-and-eps.jpg)

*An option warrant for 1,000 Reichsmark of Vereinigte Stahlwerke AG, dated 1 July 1926, from the EDHAM historical share museum. Credit: Edhac-Edham. License: Public domain. Source: [File:Vereinigte Stahlwerke 1920.jpg](https://commons.wikimedia.org/wiki/File:Vereinigte_Stahlwerke_1920.jpg).*

The price of a share only means something when set against what the share earns. **Earnings per share** (EPS) is the profit attributable to each share, and it is the denominator of the most quoted valuation ratio in the world, the price-to-earnings ratio. This lesson shows how EPS is calculated, why there are several versions, and how to read it critically.

## The basic calculation

> EPS = (Net income − preferred dividends) ÷ weighted average common shares outstanding

Preferred dividends come out because preferred holders are paid first; only the rest belongs to common shareholders. The **weighted average** share count accounts for shares issued or repurchased during the year, because a share outstanding for three months contributes only a quarter of a share-year.

Example: a company reports net income of 120 million and pays 10 million in preferred dividends. Its weighted average number of common shares is 55 million. Basic EPS = (120 − 10) ÷ 55 = 2.00.

## Basic and diluted EPS

Companies often have commitments that could increase the number of shares: stock options, restricted stock units, convertible bonds or preferred shares, and warrants. If all in-the-money claims were exercised or converted, existing shareholders' slices would shrink. **Diluted EPS** includes the effect, using a conservative assumption. Suppose the company above has options and convertibles that would add 5 million shares. Diluted EPS = (120 − 10) ÷ (55 + 5) = 1.83, which is 8% lower than basic. Analysts generally prefer diluted EPS, and a large gap between basic and diluted is a flag about future dilution.

## Reported, adjusted and trailing

- **GAAP or IFRS EPS** follows the accounting standards.
- **Adjusted** (or "non-GAAP" or "normalised") EPS removes items the company calls one-time: restructuring charges, acquisition costs, stock compensation. Adjustments can reveal underlying performance but can also flatter it, particularly when "one-time" charges recur every year. Regulators require reconciliation to the standard figure.
- **Trailing EPS** (TTM) sums the last four quarters; **forward EPS** uses analysts' estimates of the next year or so, which are only forecasts.

Companies report quarterly, and the stock price often reacts to whether earnings beat or missed the consensus analyst estimate. A "beat" is relative to expectations, not to the previous quarter: a company can grow earnings 10% and see its stock fall because the market expected 15%.

## What drives EPS

EPS can rise for very different reasons:

1. **Higher net income** from growing revenue or margins, the healthy way.
2. **Fewer shares** from buybacks, discussed in [buybacks and stock splits](04-buybacks-and-stock-splits.md).
3. **Lower interest or tax costs.**
4. **Accounting choices** about depreciation, revenue recognition or reserves.
5. **Acquisitions**, which add earnings but also shares or debt.

A rising EPS from item 1 is the most valuable; item 4 is a warning. A useful check is to compare EPS growth with growth in operating cash flow ([cash flow statement](../../02-firms-and-capital/06-the-cash-flow-statement.md)): lasting differences should be explained.

## EPS growth and compounding

If a company's EPS grows at 8% a year, it doubles in roughly nine years (by the [rule of 72](../../01-foundations/03-simple-and-compound-interest.md)). A share bought at 20 times earnings that earns 2.00 today and grows 8% a year will earn about 4.32 per share after ten years (2.00 × 1.08^10). If the multiple stays at 20, the price will be 86 or so; if the multiple compresses to 14, the price will be 60. Share-price returns depend on both earnings growth and the change in valuation multiple, a point behind the P/E discussion in the next lesson.

## Limits of EPS

- It ignores the **amount of capital** needed to produce earnings. Two firms with the same EPS can differ greatly in how much equity they used.
- It is distorted by **leverage**: heavily indebted firms can show high EPS growth with more risk.
- It is **accounting profit**, not cash.
- It is sensitive to **share-count changes** and one-offs.
- Cyclical industries have earnings that swing between boom and bust, so a single year says little.

For these reasons EPS is a starting point, one input among several in [valuation](../../03-securities/01-stocks/07-other-valuation-ratios.md).

```mermaid
flowchart LR
  N["Net income"] --> M["minus preferred dividends"]
  M --> W["divide by weighted average shares"]
  W --> E["Basic EPS"]
  E --> D["Include dilutive securities: Diluted EPS"]
```

## Key ideas

- EPS = (net income − preferred dividends) ÷ weighted average common shares.
- Diluted EPS includes potential new shares from options and convertibles and is more conservative.
- Adjusted and forward EPS can be informative or misleading; the market reacts to results versus expectations.
- EPS growth can come from profit, buybacks or accounting; the first is the one that creates value.

## Where this leads

- Next: [the price-to-earnings ratio](06-the-price-to-earnings-ratio.md).
- Related: [other valuation ratios](07-other-valuation-ratios.md), [DCF valuation](09-discounted-cash-flow-valuation.md).
- Glossary: [[g:earnings-per-share|earnings per share]], [[g:diluted-eps|diluted EPS]], [[g:trailing-earnings|trailing earnings]], [[g:forward-earnings|forward earnings]], [[g:non-gaap|non-GAAP earnings]].
