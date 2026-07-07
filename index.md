# Frequently unconvinced

I write about statistics, data science, and the places where methods are easier to use than to understand.

## Articles

### General statistics and data science methodology
**[Shrinking Universes in Conditional Probability](https://medium.com/@embeer/shrinking-universes-in-conditional-probability-2856d6a92173)**

This article explains conditional probability as "shrinking universes." It shows how conditioning on an event changes the reference population, altering the denominator while the overlap (numerator) may stay the same.

Using a simple example of computer users who like ice cream, the piece highlights practical implications for interpreting ambiguous real-world metrics (like World Bank data) and using probability rules for sanity checks and recovering missing values.

In short, it emphasizes asking what the true reference population is when analyzing data.

### Statistics and data science using Findex
**[The Denominator Problem in Findex](https://medium.com/@embeer/the-denominator-problem-in-findex-accd68dc3bbe)**

This article examines denominator inconsistencies in the World Bank's Global Findex database, recommending caution when deriving population-level estimates from specific variables. It analyzes the UNIT_MEASURE column, where most conditional indicators (beyond the full respondent population PT_RESP) allow consistent recovery of reference population sizes via conditional probability. However, three measures introduced in the 2024 wave—percentage with a mobile money account, without any account, and using the internet—show notable inconsistencies across indicators, with spreads sometimes exceeding 10–35 percentage points depending on the country and indicator choice.

Overall, it highlights the importance of checking denominator consistency in conditional data in any analysis.

Detailed breakdowns, maps, and calculations are in the accompanying [notebook](https://github.com/reebme/curated-data-sqlite/blob/main/notebooks/04_findex_unit_measure.ipynb).

**[I Asked AI What Percentage of Women Pay Bills Worldwide](https://medium.com/@embeer/i-asked-ai-what-percentage-of-women-pay-bills-worldwide-1348144642bf)**

**[World Bank data suggests 0% of Australians have a credit card. Obviously false.](https://medium.com/@embeer/world-bank-data-suggests-0-of-australians-have-a-credit-card-obviously-false-a4d34dafacdf)**

### Time Series
**[Rooted in Stationarity: Constructing AR(p) Processes from the Ground Up](https://medium.com/@embeer/rooted-in-stationarity-constructing-ar-p-processes-from-the-ground-up-bc429fb7c7a5)**

## Code

- [GitHub profile](https://github.com/reebme)

## Contact

- [LinkedIn](https://www.linkedin.com/in/magdalena-ruducha-3929aa318)
