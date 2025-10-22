🧩 Task 8: Fund Activity Classification

🎯 Objective

Investor clients want to understand the activity level of different venture funds to identify potential co-investment partners.

- High-activity funds invest in many companies, indicating broad networks.
- Middle-activity funds maintain a balance, showing moderate portfolio size.
- Low-activity funds focus on fewer investments, often reflecting deeper industry expertise.

Categorizing funds helps clients match their investment strategy with the right partners.

🧠 SQL Query

<img width="500" height="99" alt="image" src="https://github.com/user-attachments/assets/1125c994-abd3-474a-8917-1182a9590615" />


📊 Result (Sample)

<img width="600" height="100" alt="image" src="https://github.com/user-attachments/assets/dc20f54d-b3cc-42a1-b75b-df670e5d60d3" />


💬 Interpretation

The CASE statement creates a new field category to classify funds based on the number of companies they invest in.

Funds with:

- ≥ 100 investments → high_activity
- 20–99 investments → middle_activity
- < 20 investments → low_activity

This classification allows clients to quickly assess fund portfolios and target partners aligned with their strategy.
