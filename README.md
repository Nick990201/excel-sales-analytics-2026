# excel-sales-analytics-2026
![dashboard_sales](https://github.com/user-attachments/assets/7041078c-aba6-432d-a4cc-4b9b553dd08a)

The Story Behind the Project
This project wasn't just about making pretty charts; it was a deep dive into data archaeology. I spent more time under the hood cleaning and structuring the data than I did designing the final look—and honestly? That was the best part.

The "Dirty" Work (Process)
Date Cleanup: My biggest challenge was wrestling with dates that Excel refused to recognize. I had to use a mix of SQL-style logic and functions to force them into a usable format.

Logic & Mapping: I used XLOOKUP and IFS to build a bridge between raw sales and commission structures. It’s the kind of "detective work" that makes the difference between a broken table and a working system.

Building the Engine: I structured the data into clean, pivot-ready tables so the dashboard wouldn't just look good, but actually work fast.

What the Data Told Us
Beyond the numbers, the dashboard revealed some real "Aha!" moments:

Efficiency over Volume: I discovered that Anna Koleva is our "Closing Queen." While others might have more total sales, her 43% Win Rate is the highest in the team.

Targets vs. Reality: The interactive Combo Charts show exactly where we hit the mark and where we fell short in 2026.

Everything is Connected: Thanks to Report Connections, one click on a "Quarter" or "Month" slicer updates every single KPI on the screen instantly.

Lessons Learned
Excel is a Beast: It’s easy to use for a sum, but building a UI on a "white sheet" is surprisingly hard. I spent a lot of time on UI/UX, using "Snap to Grid" and custom Navy & Teal palettes to make it feel like a modern app.

The Pivot Trap: I fought a long battle with "Manual Sorting" bugs where Excel decided to ignore my ranking. I won that battle by forcing a cache reset and value-based sorting.

Clean Data > Cool Charts: No amount of design can save bad data. The satisfaction of a perfectly working XLOOKUP was better than finally picking the right colors.

Tech Stack
Excel Power User: Pivot Tables, Slicers, Data Validation, Advanced Formulas.

Data Modeling: Turning 3,000 messy rows into a relational-style database.

Design: Minimalist corporate aesthetic.
