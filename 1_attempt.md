# 1_attempt.md — Working draft

**Student:** Muhammad Saad Noor  
**ERP ID:** 37179

> Process note: This is an AI-assisted working draft, written after the student had already talked through the assignment with an AI assistant. It must not be passed off as an attempt made before using AI, and it must not be used to create a fake `attempt-before-AI` commit. The student should rewrite the claims and predictions in their own words and ask the instructor how the required snapshot should be documented.

## Two everyday price claims

### Claim 1
“Staple food items are becoming pricier.”

- **Answerable question:** How did the recorded price per stated unit of rice, eggs, sugar and black tea change across the 12 weekly observations in Karachi and Islamabad?
- **Variables needed:** date, city, item, price per unit and unit.
- **What would count as evidence:** a steady rise or fall in observed prices, worked out separately for each item and city.

### Claim 2
“Daily-use items cost roughly the same in every city.”

- **Answerable question:** For each item, how far apart were the recorded prices in Karachi and Islamabad on the same observation dates?
- **Variables needed:** date, city, item, price per unit and unit.
- **What would count as evidence:** same-date price gaps, plus the average gap for each item.

## Predictions before running the notebook

These are expectations, not results. The original course CSV was not available, so the predictions concern the file structure I expect, inferred from the assignment context and the example repository; none of them is a verified fact.

1. **Shape:** I expect a long (tidy) table with one row per item, city and date observation.
2. **Number of items:** I expect four distinct items, going by the example submission.
3. **Number of dates:** I expect twelve distinct dates, going by the example submission.

## Dataset limitation

The practice file provided is openly synthetic, with 96 rows, 6 columns, 4 items, 2 cities and 12 dates. These facts apply to the synthetic file alone and must not be reported as facts about the official course dataset.
