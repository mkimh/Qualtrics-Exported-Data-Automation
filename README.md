# Qualtrics-Exported-Data-Automation
 
## Basic Information 
- Python: Pandas, Numpy, Regex
- Data preprocessing automation

## Intended Use
- Primary intended uses: This automation code processes raw data from Qualtrics responses to internal reporting dataset for Tableau.
- Primary intended users: Internal reporting data preparation purposes. General Qualtrics users may reference lines of codes for personal uses.

## Purpose
- The purpose of these python codes is automating data preparation to feed faculty/course Tableau dashboard using Qualtrics survey data. This will help automate a data processing segment in order for the team to complete this task faster with less human errors and allocate more time to other priority areas.

## Data
Input data is downloaded directly from Qualtrics and output data is prepared to be aligned with columns in the internal data source file for Tableau. Each output data will include course/faculty information, survey questions, and related statistics in the current format used in our Tableau dashboard.

## Takeaways
- The code will take seconds to prepare a set of data.
-	The code needs minimal intervention including:
*	Set data range for questions (when desired to set custom range to accommodate with different input data fields in every survey)
* Input correct metadata
* Review output
