# Week 5 Lab: Aggregating Estimates and Margins of Error (Lab 4)

**CP201A Planning Methods Gateway, Fall 2026**
**Wednesday, September 23 (Section 101) and Friday, September 25 (Section 102)**

Lab 4 takes the tract-level ACS tables from Lab 3 and the Monday, September 14 live demo and turns them into neighborhood-level estimates with margins of error: counts summed across tracts with root-sum-of-squares MOEs, shares with the proportion formula, the same table for the city and county, medians reported as a range with a labeled approximation, and CSVs in the shape P/NP #5 asks for. Optional sections cover `groupby` for several neighborhoods and a 2015 to 2019 pull of the same tracts.

The default neighborhood is West Oakland (the 13 tracts in *Owning Our Air: The West Oakland Community Action Plan*, BAAQMD and WOEIP, 2019). Students replace the parameters in Section 1.1 with their own tracts, city, and county.

## Files

- `Lab4_Notebook_Student.ipynb`: the lab notebook
- `concatenate.png`: figure used in Section 2.2
- `Tract_Codebook_2010_2020.ipynb`: teaching-team and advanced-path notebook that checks any tract list across the 2010 and 2020 boundaries and confirms it with the API
- `tab20_tract20_tract10_st06.txt`: Census Bureau 2020 Tract to 2010 Tract Relationship File, California (used by the codebook notebook)
- `CP201A_Case_Study_Neighborhoods_Starter_Tracts_2010_2020_Fall2026.xlsx`: starter tract lists for the five field-trip neighborhoods, with sources and the 2010 to 2020 check (also posted on bCourses)

The lab notebook has no data files; it pulls everything from the Census API and expects your API key in `~/census_key.txt` (saved in Lab 3).

## Open in Datahub

https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcharismasacey%2FPlanningMethods2026&branch=main&urlpath=tree%2FPlanningMethods2026%2FWeek05_Lab_AggregatingMOEs%2FLab4_Notebook_Student.ipynb

## What is due

Nothing from this notebook is submitted. P/NP #5 (estimates, MOEs, and significance tests for two Assignment 1 questions) is due Sunday, October 4, after Lab 5.

