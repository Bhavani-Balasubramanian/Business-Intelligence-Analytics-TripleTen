🧩 Task 9: Investment Strategy by Fund Activity

🎯 Objective

Building on the fund activity classification, the research team wants to understand how fund strategies vary by activity level.
Specifically, the goal is to determine whether high-activity funds (investing in many companies) participate in more funding rounds per company compared to middle- or low-activity funds.
This analysis helps investors understand the breadth and depth of fund engagement across their portfolios.

🧠 SQL Query

<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/e820237f-4dd0-490e-99b0-a31998ea808a" />

📊 Result (Sample)

<img width="500" height="150" alt="image" src="https://github.com/user-attachments/assets/7367bc0d-a280-4f8e-8540-aeab7b587ba2" />


💬 Interpretation

- - The query categorizes funds by activity level using a CASE statement, then calculates the average number of funding rounds per category using AVG().
  - ROUND() ensures the average is a whole number for easier interpretation.
  - Sorting in ascending order shows low-activity funds first and high-activity funds last, highlighting the increase in rounds as activity level rise
