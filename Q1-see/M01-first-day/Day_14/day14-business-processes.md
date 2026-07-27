# Day 14 Reflection

Today's lesson fundamentally changed how I view databases.

Previously, I looked at tables as collections of rows and columns waiting to be queried with SQL. Today I realised that tables only contain evidence that business processes occurred.

Every row exists because people, systems or departments performed activities that generated business events worth recording. This means that before analysing data, I should first understand the business process that created it.

One of the biggest shifts in my thinking is that business problems usually originate from failing business processes, while the data simply provides evidence of those failures. My job as an analyst is therefore not just to query tables, but to trace business symptoms back to the underlying process causing them.

From now on, whenever I encounter a new table, my first question will no longer be "What columns does it have?" Instead, I will ask, "What business process created this data?"x