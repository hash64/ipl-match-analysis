# IPL Match Analysis (Beginner Project)

## Overview
This project is a beginner-friendly analysis of IPL match data using Google Sheets.  
The goal is to practice core data analytics steps: understanding the data, summarizing it, and turning the results into clear insights.

## Questions Answered
1. Which team has the most match wins?
2. Which season had the most matches?
3. Which player won the most Player of the Match awards?

## Key Insights
- Mumbai Indians have the highest number of match wins across all seasons in this dataset, followed by Chennai Super Kings and Kolkata Knight Riders.
- In this dataset, the 2013 IPL season has the highest number of matches, with a total of 76 games played.
- In this dataset, AB de Villiers has won the most 'Player of the Match' awards, with a total of 25 awards.

## Data and Tools
- Data: IPL match-level data (CSV)
- Tool: Google Sheets (pivot tables and charts)

## Limitations
- Some venue names are inconsistent (slightly different spellings), which can affect venue-level analysis.

## Project Versions

This analysis is implemented in two ways:

1. **Google Sheets version**  
   - File: `ipl_matches_analysis.xlsx` (pivot tables, charts, and Insights tab)  
   - Best for understanding the logic without code.

2. **Python (pandas) version**  
   - Folder: `python-analysis/ipl_analysis_python.ipynb`  
   - Uses pandas to reproduce the same insights:
     - Top teams by match wins
     - Matches per season
     - Top players by Player of the Match awards
