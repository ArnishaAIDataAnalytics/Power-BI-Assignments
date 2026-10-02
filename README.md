# Power BI Assignments 📊

A repository of my Power BI assignments from the AI-Driven Data Analytics course. This project documents my journey from Excel into Power BI, covering data cleaning, modeling, DAX, and interactive reporting work.

## Overview

This repository contains end-to-end Power BI work, including raw data, Power Query transformations, aggregated queries, DAX measures, PBIX files, and screenshots that demonstrate the process and results for each assignment.

### Purpose
The main goal of this repo is to capture practical learning and deliverables in Power BI, with a focus on:

- Data preparation and transformation
- Data modeling and relationship design
- DAX calculations and business metrics
- Dashboard design and reporting
- Reproducibility and documentation

### Audience
This repository is intended for:

- Instructors and graders
- Collaborators
- Future self-reference
- Anyone reviewing the progression of analytics work

## Contents

Each assignment may include:

- Power BI Desktop files (`.pbix`)
- Raw CSV datasets
- Power Query M scripts and transformation steps
- DAX measures and formula explanations
- Screenshots of key visuals and model design
- Documentation notes and assignment summaries

## Learning Goals

This portfolio aims to build skills in:

- Power Query for data cleaning and transformation
- Data modeling with proper relationships and cardinality
- Writing DAX measures for filter-aware calculations
- Designing dashboards with clear KPIs and visuals
- Validating results and documenting analysis steps

## What You Will Find in Each Assignment

- Problem statement and expected deliverables
- Raw datasets used for the task
- Power Query steps with M code snippets
- Aggregated tables created via Group By or DAX
- DAX measures used in visuals
- Final PBIX files and screenshots
- Validation notes with sample checks and totals

## Quick Start

1. Clone this repository to your machine.
2. Open the relevant PBIX file in the assignment folder.
3. If needed, recreate the steps using the provided Power Query M snippets.
4. Update data source paths if files were moved.
5. Review the DAX formulas and model structure for analysis logic.

## Recommended Folder Structure

| Path | Purpose |
| --- | --- |
| `data/` | Raw CSV files used for assignments |
| `powerquery/` | M code snippets and exported query steps |
| `pbix/` | Final Power BI Desktop files |
| `screenshots/` | Screenshots of Power Query, model view, and visuals |
| `docs/` | Assignment writeups and supporting documentation |
| `measures.md` | Catalog of DAX measures with descriptions |

## Best Practices and Notes

- Keep raw data unchanged in `data/`; create derived queries and aggregated tables separately.
- Use a Date table for time intelligence and consistent time filtering.
- Store ratios as decimals (for example, `Profit Margin = 0.12`) and format them as percentages in the model.
- Prefer `DIVIDE()` in DAX to avoid divide-by-zero errors.
- Validate aggregates by checking totals against raw data.
- Document assumptions such as null handling, rounding, and aggregation rules.

## Next Steps

As the learning journey continues, the plan is to add:

- More dashboards with advanced visuals and bookmarks
- Scenario analysis and what-if parameters using DAX
- Cross-tool work involving MySQL and Python for data prep and advanced analytics

