# Care-Quality-Commission-Care-Quality-Risk-Analytics

This project uses publicly available Care Quality Commission (CQC) inspection and ratings data to explore care quality, identify areas that may need attention, and compare performance across regions, local authorities, service types and inspection domains.

The aim was to show how inspection data can be used to understand quality in care services, identify potential risks early, and support better decisions for people who use care services.

Live Power BI Dashboard

Explore the interactive Power BI dashboard

Tools Used

Python

Power BI

Power Query

CSV

Data cleaning and validation

Data visualisation

Exploratory data analysis

Data Source and Scope

I used publicly available CQC datasets covering the England care provider directory and inspection ratings. I focused on fields such as:

Overall ratings

Service type

Inspection domains

Region

Local authority

Publication dates

These fields were selected to support comparisons of care quality and risk across different parts of the system.

Data Preparation

I used Python to prepare the source datasets before analysis. This included:

Removing inactive services

Removing unrated services

Removing duplicates

Checking and removing inconsistent records

Keeping consistent definitions across datasets

Exporting the cleaned datasets as CSV files

I then used Power Query in Power BI for further cleaning and transformation before merging the datasets into the reporting model.

Dashboard Overview

1. Quality Overview



This report provides a high-level view of the inspection ratings and where services needing attention are concentrated.

Key findings:

8,369 services were included in the analysed view.

82.73% of services were rated Outstanding or Good.

17.27% were rated Requires Improvement or Inadequate.

The largest number of services needing attention was in the South East, with 241 rated Requires Improvement and 17 rated Inadequate.

The regional percentage table also shows how risk differs across England rather than being spread evenly.

2. Domain-Level Quality and Risk



This report looks at ratings across the different inspection domains and highlights where risk is concentrated.

Key findings:

The Safe domain had the largest number of Good ratings, with 5,209 services rated Good.

The dashboard shows variation across Caring, Effective, Responsive, Safe, Well-led and Overall ratings.

The risk concentration table highlights the local authorities where Requires Improvement and Inadequate ratings are concentrated by domain.

Among the displayed domain percentages, Well-led had the highest share of services needing attention at 41.72%.

Caring had the highest displayed Outstanding/Good percentage at 87.44%, followed closely by Safe at 87.09%.

3. Authority Performance and Benchmarking



This report compares local authorities by performance and risk.

Key findings:

The table shows the top local authorities by counts of Outstanding, Good, Requires Improvement and Inadequate ratings.

Kent had 15 Outstanding, 218 Good, 37 Requires Improvement and 8 Inadequate ratings in the displayed view.

The benchmarking charts compare the share of services performing well with the share needing attention.

In the displayed risk profile, Leicester had 70.21% Outstanding/Good, while Isles of Scilly showed 100% Services Needing Attention in the selected view.

These comparisons help show that overall performance can look strong while risk remains concentrated in particular authorities.

Main Takeaways

Most services in the analysed data met expected standards.

Risk was concentrated in a smaller group of services rather than spread evenly across the system.

Quality and risk patterns varied by region, local authority, service type and inspection domain.

Inspection data can help identify where closer attention may be needed and support more targeted use of regulatory resources.

Clear and consistent data preparation is important before drawing conclusions from inspection data.

Why This Matters

Inspection data can support better decisions by helping organisations:

Identify potential risk earlier

Target inspections and support more effectively

Compare performance across locations and service types

Improve transparency

Direct attention and resources to areas where they may have the greatest impact

The wider goal of the project is to show how data can support better outcomes for people who experience care.

Repository Structure

cqc-care-quality-risk-analytics/
│
├── README.md
├── images/
│   ├── quality-overview.png
│   ├── domain-quality.png
│   └── authority-quality.png
│
├── data/                # Add raw/cleaned datasets if suitable for sharing
├── notebooks/           # Add Python cleaning/analysis notebook
└── powerbi/             # Add .pbix file if you want to share it

Notes

This is an independent portfolio project using publicly available CQC data. It is intended to demonstrate data cleaning, analysis, visualisation and interpretation skills and is not an official CQC publication.
