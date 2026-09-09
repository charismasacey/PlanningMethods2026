# Week 3: Lab 3, ACS Data in Python

**CP201A Planning Methods Gateway, Fall 2026**

Section 101: Wednesday, September 9, 5:00 to 6:30 p.m., BW 479
Section 102: Friday, September 11, 11:00 a.m. to 12:30 p.m., BW 479

This week your Census API key goes to work. You will save the key once, learn how a Census API request is put together, and pull the same ACS table at three geographic scales: census tract, city, and county.

## What is in this folder

| File | What it is |
| --- | --- |
| `Lab3_Notebook_Student.ipynb` | The lab notebook. This is the only file you open. |
| `backup_data/` | Saved copies of the three tables, for anyone whose API key has not arrived yet. |
| `README.md` | This file. |

## Getting started

Click the Datahub link on the Lab 3 page in bCourses. The notebook and the
`backup_data` folder come with it. There is nothing to install.

## Before lab

Sign up for a free Census API key at https://api.census.gov/data/key_signup.html and click the activation link in the confirmation email. It takes about two minutes. Without it you can still follow along using the backup data, but you will need your own key going forward.

## What is due

**Sunday, September 13, 11:59 p.m.**
* Python Basics Task Set from Lab 2 (P/NP #3)
* Lab 3 Check-In on bCourses (participation credit). Two questions: did your API key
  work, and what neighborhood are you thinking about? If something broke tonight, this
  is where you tell us, and there is no penalty for saying so!
  
**Tuesday, September 22, 11:59 p.m.**
* Measuring Urban Change field trip observation exercise, your census tracts, and your ACS table list for Assignment 1 (P/NP #4)

There is no separate notebook submission for Lab 3 itself.

## If you are working in your own Python environment

Datahub is the course default and nobody needs to do this. If you would rather work on your own machine, here is what the notebook expects.

**Packages**

```
pandas
numpy
census
```

Install with `pip install pandas numpy census` or `conda install -c conda-forge pandas numpy` followed by `pip install census`.

The `census` package is a thin wrapper around the Census Bureau API. The notebook uses

`Census(key=api_key)` and `c.acs5.get(...)`.

**Your API key**

The notebook writes your key to `~/census_key.txt` (your home directory, not this folder) so that the key stays off GitHub and out of anything you submit.
Every notebook from here on reads it from that file. This works the same way on Datahub and on your own machine.

**Working directory**

Run the notebook from inside this folder, so that the relative path resolves: 

`backup_data/lab3_backup_tracts.csv`  
If you get a `FileNotFoundError` on the backup cells, that is why.

**Data vintage**

All pulls use `year=2024`, which is the 2020 to 2024 ACS 5-year estimates. Five-year
estimates are labeled by their final year. If you change the year, your numbers will not
match what we show in lecture.

## Questions

Bring them to lab, to GSI office hours, or to Charisma's office hours (Wednesdays 10 to 12, or by appointment).
