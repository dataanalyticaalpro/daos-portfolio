A database is organised around business entities, not tables. Tables are separated because each entity changes independently and the business needs to manage them separately.

The Relationship Lens

Whenever I see a table, I should ask:

What real-world entity or business process does this represent?
Why is this information stored separately?
How is it related to other business entities?
What business questions can this table answer?
Key Insight

Relationships exist in the business first. SQL JOINs simply recreate those existing business relationships inside the database.

Mental Model
Business
    ↓
Business Entity / Process
    ↓
Database Table
    ↓
Rows
    ↓
Dimensions & Measures
    ↓
SQL Queries