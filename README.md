# Delhi SaniPath Data
Analysis of SaniPath style data collected November 2022 by Jemma Phillips

## Updates

### 22nd Feb 2023

Noted that left censoring was set to 600 cfu_ml. So to exclude their effect need to filter out all those at 600. No right censoring was included


### 30th Jan 2023
Created new file structure:

- code
- data
- documentation
- outputs 
	- images

#### Modifications
- renamed Environmental sampling excel file  to "Environmental_Samples_Data_Jemma.xlsx” _and put into **data** folder
- Added NA to proximaldistal_ _column
- created .Rproj umbrella file in main folder
- created delhi_analysis.Rmd file _in **code** folder

## How to run

Open Rproj file in RStudio. This will automatically open the “delhi_analysis.Rmd” _file from the **code** folder but if it doesn’t open it on manually using file \> open 
