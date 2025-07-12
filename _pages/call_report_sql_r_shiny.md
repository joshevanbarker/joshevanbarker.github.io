---
title: "Call Report SQL Database and R Shiny Application"
permalink: /portfolio/call_report_rshiny
---

Every quarter, each bank in the United States must file a "Call Report" (FFIEC 031/041/051)--financial statements including an Income Statement and Balance Sheet as well as numerous other schedules covering topics ranging from regulatory capital to derivatives and off-balance sheet items, securities, and much more. Some of this data is publicly available through the Federal Financial Institutions Examination Council (FFIEC)'s Central Data Repository. I took 4 years (2019 to 2023) of this publicly available data of Income Statements (Schedule RI), Balance Sheets (Schedule RC), and amount of past due loans (Schedule RC-N), prepared the raw data, and input it into a SQL database. In the SQL scripts, I turn the raw data into several different useful tables.

Then, using the data in the SQL databases, I built an RShiny App that allows users to query this data with three tools. One allows users to graph and chart individual line items (either multiple line items within the same institution or multiple institutions with the same line item) and see the values, dollar change, and percentage change quarter-to-quarter. The second tool allows one to view an individual schedule for an specific quarter for any institution. The final tool allows for analysis of each schedule by comparing the schedule to the balances of the 4 prior quarters and allowing users to include a merged institution's data in this analysis (if applicable).

This project seeks to highlight both my R and SQL skills. See a brief video demonstration of the application with some of its features here:

<video width="640" height="360" controls>
  <source src="/assets/audiovisual/Call%20Report%20Shiny%20App%20Demo.mp4" type="video/mp4">
</video>

To view all of the relevant code, visit the project's Github Respository here: <a href = "https://github.com/joshevanbarker/Call_Report_Data_Project">Call_Report_Data_Project</a>.
