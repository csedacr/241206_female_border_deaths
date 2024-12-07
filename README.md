# 241206_female_border_deaths

# **Description**

This repository contains a dataset, code, and findings that support the preliminary analysis found in the draft "Female Deaths Decreasing in Arizona Borderlands, but Increasing in El Paso, Texas sector” for the Advanced Data Journalism course at CUNY Grad School of Journalism.

The raw dataset for Arizona is the "Arizona OpenGIS Initiative for Deceased Migrants" and can be obtained from https://www.humaneborders.org/migrant-death-mapping. It is the result of data compiled by the nonprofit Humane Borders and the Pima County Office of the Medical Examiner from 1981 to October 2024.

The raw dataset from El Paso sector, Texas is El Paso Sector Migrant Death Database and can be obtained from https://www.elpasomigrantdeathdatabase.org/. It is the result of activist group No More Deaths but has less data points than the Arizona dataset since it only shows dates from 2009 onwards
# **Data**

The analysis uses two raw spreadsheets:

- az_deaths.csv: Raw data from "Arizona OpenGIS Initiative for Deceased Migrants" compiled by Humane Borders and - Pima County Office of the Medical Examiner. Data ranges from 1981 to October 2024.
- el_paso_deaths.csv: Raw data from El Paso Sector Migrant Death Database obtained from https://www.elpasomigrantdeathdatabase.org/ compiled by activist group No More Deaths.

# **Methodology**

Arizona Border Deaths
- The notebook arizona_border_deaths.ipynb contains a filtered version of the "Arizona OpenGIS Initiative for Deceased Migrants" to only show the "ML Number" , "Reporting Date" and "Sex”.
- Notebook also contains “az_female_deaths.jpg" in the output with the number of female remains found by year by sector 
- To do this you first have to upload the dataset, filter it and create columns for "ML Number" , "Reporting Date" and "Sex"
- Set to date time so the code is read as a date in the graph, then group by 'Reporting Date' column.
- Filter by query to narrow by female
- Save it to a new csv file
- Sort values by ascending and then graph that date on a line graph from 1981 to 2024
- Export it as jpg


El Paso Sector Border Deaths
- The notebook el_paso_deaths.csv.ipynb contains a filtered version of the "Arizona OpenGIS Initiative for Deceased Migrants" to only show the "Case Number" , "Pronouncement Date" and "Gender."
- Notebook also contains “el_paso_female_deaths.jpg" in the output with the number of female remains found by year by sector 
- To do this you first have to upload the dataset, filter it and create columns for "Case Number" , "Pronouncement Date" and "Gender."
- Set to date time so the code is read as a date in the graph, then group by the 'Pronouncement Date' column.
- Filter by query to narrow by female
- Save it to a new csv file
- Sort values by ascending and then graph that date on a line graph from 2009 to 2024
- Export it as jpg


# **Output**
- az_female_deaths.csv: Modified data to only show the "ML Number" , "Reporting Date" and "Sex."
- Line graphs showing the number of remains found by year in sector



# **Running the analysis yourself**
You can run the analysis yourself with the following installed on your computer:
- Python 3
- Pandas library
- Matplotlib library

# **Contact**

sedachab.cr@gmail.com
