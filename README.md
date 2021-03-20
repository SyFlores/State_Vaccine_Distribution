# State_Vaccine_Distribution
This repository is intended to show the ETL (extract, transform and load) process for datasets related to statewide COVID-19 impacts and vaccine distribution.

*Collaborators: Sy Flores*

---
## **Table of Contents**
- [Abstract](#abstract)
- [Repository](#repository)
- [Body](#body)
  - [Data](#data)
  - [Methodology](#methodology)
- [Conclusion](#conclusion)
- [Sources](#sources)
---
## Abstract
Placeholder

## Repository
This section serves as a means to navigate the project/repository.
- **Main_Script.ipynb**
  - This Jupyter Notebook serves as the data cleaning and transformation file
  - This file is dependent on the data files located in the Data/Input folder location
- **Data**
  - Input
    - Truth source .csv files (These contain no changes to data)
    - 'raw_covid_impacts.csv','raw_janssen.csv', 'raw_moderna.csv', and 'raw_pfizer.csv' files
  - Output
    - Placeholder
- .gitattributes
  - This file specifies which large file types we are able to upload and download
  - We currently have .csv files
- README.md
  - This .md file details most documentation needed in order to interpret the project
  - For code specific documentation, .md code segments have been inserted into the 'Data Cleaning.ipynb' notebook detailing how the code functions

## Body

### Data 
1. [Distribution of COVID-19 deaths and populations, by jurisdiction, age, and race and Hispanic origin](https://data.cdc.gov/NCHS/Distribution-of-COVID-19-deaths-and-populations-by/jwta-jxbg) as provided by National Center for Health Statistics

**Disclaimer:** We will largely be using descriptions as noted by the Centers for Disease Control and Prevention as to avoid straying from the intended interpretation of the dataset. Where apparent, we may provide minimal and reasonable interpretation.
  - Description
    - Placeholder
  - Notable Variables
    - Placeholder
  - Limitations
    - Placeholder

2. [COVID-19 Vaccine Distribution Allocations by Jurisdiction - Janssen](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh) as provided by HHS ASPA (U.S. Department of Health & Human Services, Office of the Assistant Secretary for Public Affairs)

**Disclaimer:** We will largely be using descriptions as noted by the Centers for Disease Control and Prevention as to avoid straying from the intended interpretation of the dataset. Where apparent, we may provide minimal and reasonable interpretation.
  - Description
    - Placeholder
  - Notable Variables
    - Placeholder
  - Limitations
    - Placeholder

3. [COVID-19 Vaccine Distribution Allocations by Jurisdiction - Moderna](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/b7pe-5nws) as provided by HHS ASPA (U.S. Department of Health & Human Services, Office of the Assistant Secretary for Public Affairs)

**Disclaimer:** We will largely be using descriptions as noted by the Centers for Disease Control and Prevention as to avoid straying from the intended interpretation of the dataset. Where apparent, we may provide minimal and reasonable interpretation.
  - Description
    - Placeholder
  - Notable Variables
    - Placeholder
  - Limitations
    - Placeholder

4. [COVID-19 Vaccine Distribution Allocations by Jurisdiction - Pfizer](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/saz5-9hgg) as provided by HHS ASPA (U.S. Department of Health & Human Services, Office of the Assistant Secretary for Public Affairs)

**Disclaimer:** We will largely be using descriptions as noted by the Centers for Disease Control and Prevention as to avoid straying from the intended interpretation of the dataset. Where apparent, we may provide minimal and reasonable interpretation.
  - Description
    - Placeholder
  - Notable Variables
    - Placeholder
  - Limitations
    - Placeholder

Chosen datasets are from the Centers for Disease Control and Prevention website (data.cdc.gov) and should be considered incredibly reliable. COVID-19 impact data last updated 03/19/2021 and provided by National Center for Health Statistics. All vaccine distribution data last updated 03/16/2021 and provided by HHS ASPA.

### Methodology
1. Importing data from the primary data sources
2. Cleaning data and consolidating vaccination data into one table using Python/Pandas
3. Load data into a database using SQLAlchemy/Flask

## Conclusion
*Remains to be completed.*

---

## Sources
1. [Distribution of COVID-19 deaths and populations, by jurisdiction, age, and race and Hispanic origin](https://data.cdc.gov/NCHS/Distribution-of-COVID-19-deaths-and-populations-by/jwta-jxbg)
2. [COVID-19 Vaccine Distribution Allocations by Jurisdiction - Janssen](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh)
3. [COVID-19 Vaccine Distribution Allocations by Jurisdiction - Moderna](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/b7pe-5nws)
4. [COVID-19 Vaccine Distribution Allocations by Jurisdiction - Pfizer](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/saz5-9hgg)
