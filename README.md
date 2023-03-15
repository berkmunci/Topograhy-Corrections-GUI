# Web Scrapping of Earthquake Data
## Project Target:
Creation of Earthquake catalog with web scrapting.
## Required Data for satisfy project target: 
For each point: date, time, longitude, latitude, depth (m), MD, ML, Mw, Place values.
## Desired Outputs: 
Creation of an earthquake database with update itself when it is run.
## Project Phases:
  ##  1) DATA COLLECTION PHASE
  - Data is collected from http://www.koeri.boun.edu.tr/scripts/lst8.asp.
  ##  2) DATA PREPERATION PHASE
  - Data is defined as Dataframe and desired columns are created with splitting initial data. For instance place column of web scrapped data is splitted into two columns which are city and area.
  ##  3) DATA PROCESSING AND VISUALIZATION PHASE
   First cell is for creation for database
   Second cell is for updating database with new inputs.
   - program neglects duplicated values while updating database.
