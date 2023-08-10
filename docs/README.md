# Effects of a Clogged Judiciary in India, a Country with 50 Million Court Matters Pending

This is my master's project towards completion of Master of Science (Data Journalism) from Columbia Journalism School. Find the front-end [here](https://github.io/masters_project).

## What I Aimed to Accomplish
The aim of this project was to bring to light the vast number of court matters, including trial-stage matters, that have remained unresolved for decades. 

The story begins with an example of a murder case from Sadhupur village in Uttar Pradesh state of India which was closed 42 years after the mass killings of Dalit community members by armed men.

It then provides more examples of such cases.

A part of the process was to highlight that these cases are not in public conscience because journalists are not even aware that they exists. The aimed result of this project is to provide a tool, in the form a database, that can provide district-level insights into criminal matters that have fallen off the judiciary's radar.

A part of the solution is to find out how the problem begins; how do these cases fall off the judiciary's radar?

## Findings
Data findings:
* There are more than half a million cases that have been lying unattended for more than two decades. Of these half million cases, 80,000 have been around for more than three decades - some going back nearly 55 years. 

* Of the 50 million matters in the country, over 32 million are criminal matters while others are civil.

* There is at least 9 percent and at most 60 percent judicial vacancy in the district courts all over the country.

* To provide a slight insight on how a more granular dataset can provide (a sample database created as part of this project):
-In 61 out of 75 districts of Uttar Pradesh, there are 38,418 murder-related matters.
-Of these, over 20,000 are in trial stage. 
-Among those in trial stage, hundreds of cases have been stuck for more than 20 years, 3 have been around for more than 30 years, and 1 has been awaiting conclusion for over 40 years, as in 2023.
-The geographical locations and the courthouses in which these cases are ongoing can be pointed out with this database.
-The judicial vacancy, which is not part of the universe of data of this project, of these courts and their individual caseload can help identify the most overworked and vulnerable courts.
-This can in-turn help the law ministry concentrate its resources on these courts.

Qualitative findings:
* In 3 cases, 2 of which made it into the story, the public prosecutors agreed that older cases, that were instituted before their time in office, will not land on their radar unless a special effort is made by principal judges.

* The 42-year-old case from Sadhupur village of UP was brought to conclusion because the principal judge Harvir Singh of Firozabad district decided to make a list of old cases in his jurisdiction and try to bring them to a conclusion. 

* As case pendency increases, the percent share of prison population of those languishing in jail awaiting a fair trial, increases. While I do not have proof of causation, there is a correlation that is worth exploring further with data.
 
## Data Collection Process
The data for this project was collected from various sources. Some of the main ones include:
* National Data and Analysis Platform (NDAP) API
* e-court services
* Department of Justice dashboard for judicial appointments
* Justice Clock from the e-courts initiative
* 2011 India census government website

The NDAP platform had a documented API while the others were scraped using either Playwright or BeautifulSoup or *hold your breath* both *release* .

Confession: I had to physically write the 75 names of the districts in UP to join them to the datasets because the pages I scraped only have abbreviations. Carpal tunnel in the making.

## Overview of the Data Analysis Process
The data analysis required two constants: population, judicial vacancy, names of districts (for sample database).

The analysis first gives an overall view of how many cases exist in the country and tries to boil down to the most granular available datapoint.

The database I created provides a step further than the data available in public domain currently.

## New Skills and Lessons Learned
There are a few things that I learned in this project:
* How to not panic and follow a schedule
* Parallel processing
* Creating graphics purely in Illustrator
* Different ways of scraping aside from the traditional methods
* AI can help debug code 

## Future of This Project
In the coming months I wish to scale the project in multiple directions.
