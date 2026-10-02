Power BI Assignments 📊
A repository containing my Power BI assignments from the AI Driven Data Analytics course. This repo documents my progression from Excel into Power BI, showing data cleaning, modeling, DAX, and interactive reporting work — a record of learning and deliverables.

Overview
Purpose  
This repository stores end‑to‑end Power BI work: raw data, Power Query transformations, aggregated queries, DAX measures, PBIX files, and screenshots that demonstrate the steps and results for each assignment.

Audience  
Instructors, graders, collaborators, and future-you who want reproducible steps, explanations, and deliverables.

Contents
Power BI Desktop files (PBIX) with finished dashboards and reports

Raw data CSVs used for each assignment

Power Query M snippets and step descriptions

DAX measures catalog with explanations and usage examples

Screenshots of Power Query steps, Model view, and key visuals

Documentation including README, measures.md, and step‑by‑step notes

Learning Goals
Master Power Query for data cleaning and transformation

Build robust data models with correct relationships and cardinality

Write DAX measures for dynamic, filter‑aware calculations

Design interactive dashboards with clear visuals and KPIs

Validate and document results for reproducibility and grading

What you will find per assignment
Problem statement and expected deliverables

Raw dataset used for the task (in data/)

Power Query steps (in powerquery/) with M code snippets

Aggregated tables created by Group By or DAX (if required)

DAX measures used in visuals (in measures.md)

Final PBIX file (in pbix/) and screenshots (in screenshots/)

Validation notes showing sample checks and totals

Quick Start
Clone the repo to your machine.

Open the PBIX file in pbix/ or recreate steps using M snippets in powerquery/.

Place CSVs from data/ into a local folder and update data source paths if needed.

Refresh data: Home → Transform data → Data source settings to update file paths.

Use measures.md to review or add DAX measures to the model.

Recommended Folder Structure
Path	Purpose
data/	Raw CSV files used for assignments
powerquery/	M code snippets and exported query steps
pbix/	Final Power BI Desktop files
screenshots/	Power Query, Model view, and visual screenshots
docs/	Assignment writeups, instructions, and this README
measures.md	Catalog of DAX measures with descriptions


Best Practices and Notes
Keep raw data unchanged in data/; add derived queries and aggregated tables in powerquery/.

Use a Date table for time intelligence and consistent time filtering.

Store ratios as decimals (e.g., Profit Margin = 0.12) and format as Percentage in the model.

Use DIVIDE() in DAX to avoid divide‑by‑zero errors.

Validate aggregates by spot‑checking sums against raw CSV totals.

Document assumptions (null handling, rounding, aggregation rules) in each assignment folder.

Next Steps
As I continue the course I will add:

More Power BI dashboards with advanced visuals and bookmarks

Scenario analyses and what‑if parameters using DAX

Cross‑tool work: MySQL queries and Python notebooks for data prep and advanced analytics

Contact and Contribution
Contributions welcome via issues or pull requests. Please include sample data and a clear description of changes.
License: add a LICENSE file (recommended MIT) if you want public reuse.
Maintainer: add your name and contact details in docs/ for graders or collaborators.
