# covid-19 Using Python and Tableau

## Problem Statement:
The COVID-19 dataset serves as a critical resource for understanding the spread, impact, and dynamics of the coronavirus pandemic. However, amidst the wealth of data available, several challenges persist in effectively leveraging this information to inform public health strategies and mitigate the effects of the pandemic. One pressing problem to address is the accurate identification and analysis of trends in infection rates, mortality rates, and vaccination rates across different regions and demographics. This requires robust data cleaning, normalization, and integration techniques to reconcile inconsistencies and discrepancies within the dataset, ensuring the reliability and validity of the insights derived. Additionally, there is a need to develop predictive models to forecast the future trajectory of the pandemic, anticipate potential surges in cases, and assess the effectiveness of intervention measures such as lockdowns and vaccination campaigns. Furthermore, improving data sharing and collaboration among global health organizations, governments, and research institutions is essential to facilitate cross-border analysis and coordination in combating the pandemic on a global scale. By addressing these challenges, we can enhance our understanding of the COVID-19 pandemic and inform evidence-based decision-making to mitigate its impact on public health and society.

![Alt text](https://github.com/msinghsandhu/covid-19/blob/main/Dashboard.png?raw=true)


## Solution Approach:

To address the problem statement, the following approach was used:

### * Data Cleaning and Transformation: 
Used Pandas to drop irrelevant data from the CSV files and performing other relavent data transformation operations to have a clean data for the visulization purpose.

### * Vizulization Creation - Performance Insights: 
Creating the plots using the following libraries: Matplotlib and seaborn 
* Top 10 States with most active cases
* Top 10 states with most number of deaths recorded
* Trends of number of cases for each state that got impacted
* Gender ratio of vaccination
* Top 5 states with highest number of vaccinations
* Top 5 least vaccinated states.

### * Tableau Dashboard Creation:  
Each dashboard was designed to be interactive, allowing users to filter and drill down into specific dimensions or time periods of interest.
The dashboard highlights the following points:
* Top 10 countries with confirmed cases
* Tile representation of Death cases in each country
* Maximum recoveries
* Comparision between confirmed and deaths in each country.

  
## Expected Outcome:

   * Enhanced Data Analysis: The analysis based on all the countries and specific to one country gave a detailed overview.

   * Improved Decision Making: By understanding the trends of the rise in cases and the fall in cases in each state of every single country we can determine the chances of next peak duration and impact and take important steps to handle those

   * Increased Efficiency: By focusing on the vaccination rate and the number of recoveries we can target the states which are highly impacted and needs to be vaccinated at a higher rate.

 
