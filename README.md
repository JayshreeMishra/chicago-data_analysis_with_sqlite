# Chicago Census Data Analysis with SQLite

## Introduction
This project involves the analysis of three datasets from the city of Chicago using SQLite. The datasets include:

1. **Socioeconomic Indicators in Chicago**
   - This dataset contains six socioeconomic indicators of public health significance and a hardship index, by Chicago community area, for the years 2008–2012.
   - [Original Dataset](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)

2. **Chicago Public Schools**
   - The dataset provides school-level performance data used to create CPS School Report Cards for the 2011-2012 school year.
   - [Original Dataset](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)

3. **Chicago Crime Data**
   - This dataset reflects reported incidents of crime (excluding murders where data exists for each victim) in the City of Chicago from 2001 to the present (excluding the most recent seven days).
   - [Original Dataset](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

## Getting Started
To run the analysis, follow these steps:

1. Install the required dependencies.
  
2. Load the necessary extensions and import the datasets.
   
3. Execute SQL queries to explore the datasets.

## Project Structure
- **Notebook Files:**
  - `Chicago_Data_Analysis.ipynb`: Jupyter notebook containing the analysis code.
  
- **Datasets:**
  - `ChicagoCensusData.csv`: Socioeconomic Indicators in Chicago.
  - `ChicagoPublicSchools.csv`: Chicago Public Schools data.
  - `ChicagoCrimeData.csv`: Chicago Crime Data.

## Analysis Highlights
1. **Total Crimes Recorded**
   - Find the total number of crimes recorded in the CRIME table.

2. **Community Areas with Low Per Capita Income**
   - List community areas with per capita income less than 11000.

3. **Crimes Involving Minors**
   - List all case numbers for crimes involving minors.

4. **Kidnapping Crimes Involving a Child**
   - List all kidnapping crimes involving a child.

5. **Crimes Recorded at Schools**
   - What kinds of crimes were recorded at schools?

6. **Average Safety Score by School Type**
   - List the average safety score for each type of school.

7. **Community Areas with High Poverty**
   - List 5 community areas with the highest % of households below the poverty line.

8. **Most Crime-Prone Community Area**
   - Identify which community area is most crime-prone.

9. **Community Area with Highest Hardship Index**
   - Determine the community area with the highest hardship index.

10. **Community Area with Most Crimes**
    - Find the Community Area Name with the most number of crimes.
