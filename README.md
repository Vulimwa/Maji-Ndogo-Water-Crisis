# Maji Ndogo Water Crisis Analysis

## Project Overview

This project is designed to apply urban planning concepts-especially in utilities, services, and infrastructure to a practical scenario. The analysis focuses on water accessibility, utilities, services, and infrastructure in the fictional country of Maji Ndogo, demonstrating how planning knowledge can be used to address real-world challenges.

## Objectives
- **Assess the current state of water access** across urban and rural communities in Maji Ndogo.
- **Analyze the efficiency and equity of water utilities and services** using SQL and data science tools.
- **Identify infrastructure gaps** and propose actionable solutions to improve water delivery and reduce service disparities.

## Data & Methodology
- **Data Sources:**
  - Survey data on water sources, locations, employees, and service visits (see `Data/` folder).
  - MySQL database for structured querying and analysis.
- **Tools Used:**
  - Jupyter Notebook (see `Majindogo.ipynb`)
  - Python, Pandas, SQL (via `ipython-sql` and `pymysql`)
- **Key Steps:**
  1. Data cleaning: Standardized employee emails, phone numbers, and removed inconsistencies.
  2. Service analysis: Quantified employee activity, water source types, and service coverage by town and province.
  3. Infrastructure assessment: Evaluated the number and type of water sources, their functionality, and the number of people served.
  4. Queue and accessibility analysis: Measured average queue times, peak hours, and disparities between urban and rural areas.
  5. Solution design: Prioritized interventions based on impact, focusing on shared taps, wells, and broken infrastructure.

## Key Insights
- **Utilities & Services:**
  - 43% of the population relies on shared taps, with up to 2,000 people sharing a single tap in some communities.
  - 31% have in-home water infrastructure, but nearly half of these systems are non-functional due to broader infrastructure failures (pipes, pumps, reservoirs).
  - 18% use wells, but only 28% of these are clean and safe.
- **Infrastructure Gaps:**
  - Most water sources are in rural areas, presenting logistical challenges for repairs and upgrades.
  - Queue times for water can exceed 2 hours, especially on weekends and during peak hours.
- **Service Disparities:**
  - Urban areas have better infrastructure but still face issues with broken systems.
  - Rural communities are disproportionately affected by long queues and limited access.

## Solutions & Recommendations
- **Short-term:**
  - Deploy water trucks to river-dependent communities.
  - Install filters (UV, reverse osmosis) in contaminated wells.
  - Send additional tankers to high-queue shared taps during peak times.
- **Medium-term:**
  - Repair broken infrastructure (pipes, reservoirs) to restore service to the largest number of people.
  - Install extra shared taps in high-demand areas.
- **Long-term:**
  - Expand in-home tap installations as resources allow.
  - Address root causes of well contamination.

## Skills Demonstrated
- Data cleaning and transformation
- SQL database management and advanced querying
- Urban infrastructure analysis
- Service delivery assessment
- Solution design for utilities and public services
- Reporting and visualization of key findings

## How to Use
1. Open `Majindogo.ipynb` in Jupyter Notebook.
2. Ensure you have MySQL running and the required Python packages installed (`ipython-sql`, `pymysql`).
3. Follow the notebook cells for step-by-step analysis, from data cleaning to solution recommendations.

## About the Author
This project was done by Bravin Vulimwa to showcase practical skills in analyzing and improving essential public services, with a focus on equitable and sustainable urban development. It is intended to demonstrate initiative and applied learning beyond formal academic requirements.

---

*For more details, see the notebook and data files in this repository.*
