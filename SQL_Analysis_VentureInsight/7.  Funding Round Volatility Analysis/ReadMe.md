🧩 Task 7: Funding Round Volatility Analysis

🎯 Objective

The risk analysis team wants to examine volatility in funding rounds.
Specifically, they are interested in dates where there is significant variation between the smallest and largest funding rounds, which could indicate unusual market activity.
Days where some companies received no funding or where all companies received the same amount are excluded to ensure meaningful insights.

🧠 SQL Query

<img width="300" height="99" alt="image" src="https://github.com/user-attachments/assets/2b76d33a-46df-4160-9883-933e1c16f012" />

📊 Result

<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/da631094-52ca-4175-af23-1bfc171bdb32" />

💬 Interpretation

- This query calculates the minimum and maximum funding amounts for each date using MIN() and MAX().
- The HAVING clause excludes irrelevant records where:
    - The smallest amount is 0 (indicating no funding), or
    - The smallest and largest amounts are equal (indicating no volatility).
- The resulting table highlights dates with significant variation in funding, helping the team spot unusual market activity.
