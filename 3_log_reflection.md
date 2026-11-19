# 3_log_reflection.md — Working draft

**Student:** Muhammad Saad Noor  
**ERP ID:** 37179

## AI use log

| AI suggestion / assistance | Check performed | Status |
|---|---|---|
| Proposed rewriting “staple food items are becoming pricier” as a question about item prices across dates. | Confirmed the practice dataset has item, date and price columns. | Accepted for practice only. |
| Proposed comparing prices between Karachi and Islamabad. | Confirmed both cities appear in the synthetic data and every item has matching dates. | Accepted for practice only. |
| Proposed summarising each item with its average price. | Recomputed the group means with pandas `groupby`. | Accepted as a descriptive method. |
| Proposed percentage change from the first to the last observation. | Checked the first and last dates and confirmed the formula. | Accepted for practice only. |
| Proposed using the observed pattern to claim that real prices are going up. | The data is synthetic, so it cannot support claims about real markets. | Rejected. |

## Other questions considered

1. **Did each item's average recorded price change over the observation period?**  
   Kept: the synthetic file has date, item and price.

2. **Did recorded prices differ between Karachi and Islamabad for the same item and date?**  
   Kept: city, item, date and price are all present, so matched comparisons work.

3. **Did higher prices make households buy less?**  
   Rejected: the file has no household purchases, quantities bought or income.

4. **Which shop sold at the lowest price?**  
   Rejected: the file has no shop or outlet identifier.

5. **Did inflation cause the price changes?**  
   Rejected: the file has no inflation series and no causal design. A pattern over time cannot establish a cause.

## Reflection (approximately 100 words)

This exercise showed me that data can turn a broad statement into a narrower, testable question. Using the date, item, city and price variables, I can describe how recorded prices in this practice dataset change over time and how the two cities compare. I cannot use these numbers to describe real market conditions, since the file is synthetic. I also cannot say why a price moved, measure affordability, or work out what households bought, because those variables are missing. The key lesson is that any conclusion has to stay inside the limits of the variables and the origin of the data.

## Verification note

The notebook calculations should be run in Jupyter before submission. The synthetic file is clearly labelled and should be used only if the instructor allows substitute teaching data. If the official CSV becomes available, rerun the notebook on it and update every result and the reflection.
