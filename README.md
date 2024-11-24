# PHASE-1-PROJECT-AIRCRAFT-RISKS-ANALYSIS.
This is my Phase 1 Data Science project where I carried out data cleaning and analysis for Aviation data set.
# AIRCRAFT RISK ANALYSIS.
# OVERVIEW.
Our company is expanding its portfolio to include aircraft, marking a significant move into the aviation sector. To ensure this venture aligns with our strategic objectives, we will leverage data-driven insights to guide our decision-making. A comprehensive risk analysis will be conducted using a database of aviation accidents from 1993 to 2023. This data will help identify trends, potential risks, and safety considerations for different aircraft types, enabling us to select the most suitable options to support our company's goals.
# BUSINESS UNDERSTANDING.
The primary business objective is to expand into the aviation industry by acquiring aircraft that balance operational efficiency, safety, and cost-effectiveness. To achieve this, we will analyze historical aviation accident data spanning three decades (1993–2023). This analysis will focus on identifying patterns and risk factors associated with different aircraft models, manufacturers, and operational contexts. By understanding the safety records and risk profiles of various aircraft, we aim to make informed decisions that minimize risks, align with our strategic goals, and ensure long-term value for the company.
# DATA UNDERSTANDING.
The dataset we are using was drawn from Kaggle.
It contains information from the National Transportation Safety Board (NTSB) aviation accident database, which includes data from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories, and possessions, as well as in international waters. This dataset provides comprehensive insights into various factors involved in aviation incidents, including weather conditions, flight phases, aircraft types, and more.
# DATA PREPARATION:
The data was cleaned using the VSCODE code editor.
The python pandas library and numpy library was imported for analysis.
In the data cleaning the data underwent several steps which include:
* Importing the relevant python libraries.
* Loading and reading the CSV file.
* Inspecting and understanding the data.
* Data Cleaning.
* In data cleaning we checked all the missing values and dropped all the columns with the missing values above the 20% mark.
* We also dropped all the unnecessary columns that we did not need and dropped the duplicates.
* We also filled in all the numerical columns with missing values with 0 and all the categorical columns with missing values with unknown.
* We then merged the two data frames of the Aviation data and US State codes.
* Then we stripped all the white spaces.
# DATA ANALYSIS.
The data was analysed using the VSCode code editor.
The necessary libraries were imported: matplotlib and seaborn.
We analysed different column variables.
We began with the Univariate analysis and we can see that the Accidents make up 95.6% of the investigation type  which is the majority and incidents make up 4.4% which is the minority.
Bivariate analysis and Multivariate analysis was also done.
## Conclusion
Based on the analysis we conclude as follows:
- **Aircraft Makes and Models:**
We can see that the aircraft make with the most accidents are Cessna with 27149 accidents and Piper with 14870 accidents.
We can see that the aircraft model with the most accidents are  152 with 2367 accidents and 172 with 1756 accidents.
The aircraft makes boeing and bell have fewer accidentd but they still have notable numbers.
- **Weather Condition:**
We can see that the weather conditions with the most accidents is VMC followed by IMC.
VMC abbreviation stands for: Visual Meteorological Conditions
IMC: Instrument Meteorological Conditions.
- **Location:**
We can note that most of the accidents occur in Anchorage, Miami and Houston as compared to other regions.
- **Injury types:**
We can see that the number of fatal injuries decreases over the years while the number of uninjured increases over the years.
- **Number of Engines:**
We can see the number of engines with the most accidents are the aircrafts with 4 or less engines.
## Recommendations:
- **Aircraft Makes and Models:**
Avoid Aircraft makes and models with high accident rates such as the Cessna and Piper.

- **Weather Conditions:**
Its notable that the the weather conditions more prone to accidents are VMC. Ensure the aircraft is equipped to handle all conditions for added safety.

- **Location:**
Avoid hifgh risk routes such as Anchorage, Miami and Houston and consider low risk routes.

- **Number of Engines:**
Consider the aircrafts with more than 4 engines if possible.

### Tableau Link for visualisation of the analysis:
https://public.tableau.com/views/Aviationdataanalysis/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
