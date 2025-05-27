<h1>SQL Project</h1>

 ### 
<h2>Description</h2>
This project allowed me to get hands-on experience with working with a big dataset. This dataset is a public dataset on homelessness from U.S. Department of Housing and Urban Developments (HUD) Point-in-Time (PIT) count data that can be found in Google BigQuery. I became familiarized with the dataset, performed data exploration, transformed it using SQL, as well as analyzed it. I also practiced writing SQL statements in order to explore, filter, and analyze the dataset.
<br />


<h2>Where the Dataset Came From</h2>

This bigquery dataset is a public dataset on homelessness from HUD's Point-in-Time (PIT) count data that can be found in Google BigQuery. 

(bigquery-public-data.sdoh_hud_pit_homelessness.hud_pit_by_coc)

<h2>Tools Used</h2>

- <b>Google BigQuery</b> 
- <b>SQL</b>
- <b>Google Sheets</b> <i>When comparing SQL functions like LEFT()</i>

<h2>Steps Taken</h2>

1. Dataset Exploration
   - Understood the different column names and data types inclueded within the dataset
   - Identified non-integer columns
2. New Table Creation
   - Used SQL to extract the 2-letter state abbreviation from the column CoC_Number. I used the LEFT() function to do this.
4. Data Analysis
   - Realized the correlation between homelessness and population
  
<h2>Key Findings</h2>

1. The 3 CoC Areas with the most Unaccompanied Youth were:
 - San Jose/Santa Clara City & County CoC
 - Oregon Balance of State CoC
 - Vegas/Clark County CoC
2. Delware had <b>decreasing </b> unsheltered homelessness
3. 50 locations had at least 1 Sheltered_SH in 2018, with the top 3 being Philadelphia CoC, Reno/Sparks CoC, Indianapolis CoC
4. The top 7 states with the highest Overall Homeless Populations in 2018 were:
   - CA
   - NY
   - FL
   - TX
   - WA
   - MA
   - OR
 5. OR, MA, and WA were the states that were overrepresented since they had higher ranks in homelessness than in population.
6. The areas with less than 2% Unsheltered Homeless were Springfield/Hampden County CoC and Nassau, Suffolk Counties CoC. Effective shelter strategies are taking place to reduce unsheltered homelessness.  


<h2>Questions</h2>

- What strategies are the areas with less than 2% unsheltered homeless implementing?
- Are there correlations between funding, housing costs, and homelessness across states?

<h2>Links to My SQL Project</h2>

[Part 1](https://docs.google.com/document/d/1QuMILB9_toO9BITnaXDN7rmHoQnaiigT3BIlsNbpJyY/edit?usp=sharing)

[Part 2](https://docs.google.com/document/d/1qVceIwXY5AJro7pzPfVQ74bikXcVUrPxDVuIJNSwBbs/edit?usp=sharing)
