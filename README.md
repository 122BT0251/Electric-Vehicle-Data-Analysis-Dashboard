This project focuses on analyzing the Electric Vehicle (EV) market in the United States using Tableau.
The dashboard provides a comprehensive, interactive visualization of over 150,000 EV records, enabling insights into adoption trends, vehicle types, manufacturers, and state-level penetration.

The main goal of this analysis was to identify trends and patterns in the electric vehicle industry — helping policymakers, manufacturers, and consumers better understand the EV landscape.

🧾 Dataset

Source: Kaggle - Electric Vehicle Population Data

Size: ~150,000 rows, 17 columns

Format: CSV

Key Fields Used
Field	Description
Model Year	Year of vehicle model
Make	Manufacturer (e.g., Tesla, Nissan, BMW)
Model	Specific model name
Electric Vehicle Type	BEV (Battery Electric Vehicle) / PHEV (Plug-in Hybrid Electric Vehicle)
Electric Range	Average distance in miles on a full charge
CAFV Eligibility	Clean Alternative Fuel Vehicle eligibility status
State	U.S. state of registration
🎯 Project Objectives

Analyze growth trends in electric vehicle adoption from 2011–2024.

Compare BEV vs. PHEV vehicle share and performance.

Identify top manufacturers and their best-selling models.

Visualize state-wise distribution and CFV eligibility ratios.

Create an interactive Tableau dashboard for dynamic analysis using filters and actions.

🧩 Tools & Technologies

Tableau Desktop / Tableau Public – Data visualization and dashboard creation

Microsoft Excel – Data cleaning and preprocessing

Kaggle – Dataset source

📈 Dashboard Features

The final Tableau dashboard includes:

✅ Dynamic KPIs: Total Vehicles, Average Electric Range, Total BEVs, Total PHEVs

🌎 Interactive Filters: State, Manufacturer, Vehicle Type, Model

📊 Charts and Visuals:

Total Vehicles by Model Year (Trend Analysis)

Total Vehicles by State (Map View)

Top 10 Vehicle Makes (Bar Chart)

Total Vehicles by CAFV Eligibility (Donut Chart)

Total Vehicles by Model (Grid View)

⚙️ Action Filters: Click on a make, model, or state to dynamically update all visuals

🎨 Design Theme: Green and white palette symbolizing clean energy

🧮 Analytical Insights

Some key findings derived from the dashboard:

78% of electric vehicles are Battery Electric Vehicles (BEV), while 22% are Plug-in Hybrids (PHEV).

The state of Washington leads in EV adoption, followed by California.

Tesla dominates the market, contributing over 50% of total EVs sold.

The average electric range across all vehicles is approximately 90 miles per charge.

46% of vehicles have unknown CFV eligibility, indicating ongoing research and certification.

🛠️ Steps Followed

Data Cleaning – Removed duplicates, standardized model names, filtered model years ≥ 2011.

Data Preparation – Created calculated fields for KPIs and category splits.

Dashboard Design – Structured layout using containers (KPIs, filters, charts).

Interactivity Setup – Added filters, parameters, and action-based controls.

Validation – Tested dashboard responsiveness and accuracy of all calculations.

📸 Dashboard Preview

<img width="1610" height="788" alt="image" src="https://github.com/user-attachments/assets/d86ca87b-c3e8-4a07-a318-9aa317998d7b" />



🧠 Learnings & Takeaways

Developed strong understanding of Tableau interactivity (filters, parameters, dual axes).

Enhanced ability to translate business questions into visual analytics.

Improved storytelling through data visualization and design consistency.

Practiced end-to-end data analytics workflow — from raw data to actionable insights.
