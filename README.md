# NBA-Basketball-Dashboard

📌 NBA Basketball Dashboard (Power BI)

🏀 Project Overview
The NBA Basketball Dashboard is a data visualization tool built using Power BI to analyze player statistics, team performance, and draft history. It helps users explore key metrics like points, assists, rebounds, efficiency, and player rankings across different seasons.

📂 Dataset Description
The dataset includes various player and team attributes, such as:

Player Information: player_name, age, player_height, player_weight, college, country
Team Details: team_abbreviation, season
Draft Information: draft_year, draft_round, draft_number
Performance Metrics: gp (games played), pts (points), reb (rebounds), ast (assists), net_rating, usg_pct, ts_pct, ast_pct

🚀 Features & Visuals

📊 Key Metrics (KPI Cards)
Total Points Scored
Average Assists per Game
Top Player by Net Rating
Player with Highest Usage Percentage

📈 Visualizations
Player Performance Overview
Bar Chart: Top 10 players by pts, reb, ast
Slicer: Filter by season and team_abbreviation
Team-wise Performance
Stacked Column Chart: Total pts by team
Pie Chart: Assist percentage distribution across teams
Draft Insights
Line Chart: Points trend over different draft years
Advanced Metrics
Scatter Plot: Relationship between usg_pct and ts_pct
🎛 Filters & Slicers
Season Selection
Team Filter
Country Filter
Draft Year Selection

⚡ DAX Measures Used
DAX
Copy
Edit
Create a Table or Matrix Visual:
Add team_abbreviation as the row field.
Add the measures: [Average Age], [Average Height], [Average Weight], and the respective ranks.
Apply Filters:
Use a filter on Rank by Age, Rank by Height, or Rank by Weight to show Top 10 Teams only (filter where rank ≤ 10).

📌 Setup Instructions
1️⃣ Load Data
Import the dataset into Power BI (CSV, Excel, or SQL Database).
2️⃣ Data Cleaning & Transformation
Ensure correct data types for numeric fields.
Remove missing or inconsistent values.
3️⃣ Build Visuals
Use Power BI Report View to create charts, tables, and slicers.
Apply filters and interactivity for better insights.
4️⃣ Publish & Share
Publish the report to Power BI Service for online access.
Share with team members or export as PDF.

🎨 Design & Best Practices
Theme: NBA-inspired colors and styling
Responsiveness: Optimized for desktop and mobile
Interactivity: Tooltips and drill-through analysis

📬 Contact & Support
For any questions or feature suggestions, feel free to reach out! 🚀
