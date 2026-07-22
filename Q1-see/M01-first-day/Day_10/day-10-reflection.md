# DAOS Day 10 Reflection

## Biggest Lesson

Today I understood that SQL's `GROUP BY` does not group columns or measures—it groups rows based on the values of one or more dimensions. Once the rows are grouped, SQL performs aggregate calculations on the measure for each group.

This completely changed how I think about `GROUP BY`.

## Key Insights

- Measures answer "How much?" or "How many?"
- Dimensions answer "Who?", "What?", "Where?", and "When?"
- Business questions usually follow the pattern: Measure + Dimension.
- The dimension determines how rows are grouped.
- The measure determines what is calculated for each group.
- SQL first groups rows, then performs aggregate calculations.

## Mental Model

Rows
→ Group by Dimension
→ Calculate Measure
→ Return one result per group

## Reflection

The biggest breakthrough today was realizing that `GROUP BY` groups rows rather than columns. Once I understood that, measures, dimensions, and business questions all connected together. I also now understand why BI tools like Power BI and Excel Pivot Tables work the same way—they group records by dimensions before calculating measures.