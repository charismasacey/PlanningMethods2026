# Week 6 Lab: Testing for Statistical Significance

CP201A Planning Methods Gateway, Fall 2026
Lab 5: Wednesday, September 30 (Section 101) and Friday, October 2 (Section 102)

## Files in this folder

- `Lab5_Notebook_Student.ipynb`: the lab. Starts from the CSV files Lab 4 saved.
- `Lab5_Crosswalk_Companion.ipynb`: advanced path only. Reallocates 2015 to 2019 tract data onto 2020 tracts when a tract was merged, renumbered, or had its boundary moved.
- `tab20_tract20_tract10_st06.txt`: the Census Bureau's 2020-to-2010 tract relationship file for California, used by the companion notebook. Source: https://www.census.gov/geographies/reference-files/time-series/geo/relationship-files.2020.html
- `z_critical_values.png`: the critical-values figure in Section 3.2 (drawn for this course).
- `excel_example_a.png`, `excel_example_b.png`, `excel_example_c.png`: the `.loc` illustrations in Section 0.2.

## What the lab needs from Lab 4

Two CSVs in `Week05_Lab_AggregatingMOEs/`, written by Lab 4 Section 7 and Section 10:

- `lab4_<neighborhood>_comparison_wide.csv` (race and ethnicity)
- `lab4_<neighborhood>_tenure_comparison_wide.csv` or `lab4_<neighborhood>_poverty_comparison_wide.csv`

Section 1.3 of the lab rebuilds the West Oakland defaults from the API if the files are missing.

**If your Lab 4 CSVs came from the West Oakland defaults, they are not your data.** Open your Lab 4 notebook, put your own tract list in Section 1.1, run the whole notebook again (Section 10 too), and use the CSVs it saves. From here on, everything you hand in (P/NP #5 and both parts of Assignment 1) is built from your own neighborhood's tracts: your 2020 tract list for 2020 to 2024 ACS, and the 2010 tract list that covers the same land for 2015 to 2019 ACS data. Lab 5 (this lab) Section 6.0 tells you what that 2010 list is.


**Advanced path:** a companion notebook, `Lab5_Crosswalk_Companion.ipynb`, opens with the same link (look in the folder). Use it only if one of your tracts was merged, renumbered, or had its boundary moved in 2020; the notebook starts with a checklist that tells you whether you need it.

**Reading:** U.S. Census Bureau (2020), *Understanding and Using American Community Survey Data: What All Data Users Need to Know*, Section 7 (pp. 53 to 58). https://www.census.gov/programs-surveys/acs/library/handbooks/general.html

**What you submit this week:** nothing from the notebook itself. P/NP #5 is the filled-in template, saved as a PDF.

**Due this week:** P/NP #5 (estimates, MOEs, and significance tests for two questions) by **Sunday, October 4, at 11:59 p.m.** Section 5.3 of the notebook prints the Part III numbers in the order the template asks for them.

**Assignment 1 is due Sunday, October 11.** Every claim of a difference or a change in the memo needs the test from this lab, with the result in the note under the exhibit.

