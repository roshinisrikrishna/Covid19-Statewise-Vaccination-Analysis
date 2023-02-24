 Covid19 India Statewise Vaccination Analysis:
 
 Datasets:

We have a dataset downloaded from kaggle website. It is named as Latest Covid-19 India Status.This data constitues number of covid deaths and positive cases in respective States/UTs till 8th July 2021. The data file is a Comma separated value file format with 36 rows and 9 columns. It contains 9 columns which contains:

State/UTs - Names of Indian States and Union Territories.
Total Cases - Total number of confirmed cases
Active - Total number of active cases
Discharged - Total number of discharged cases
Deaths - Total number of deaths
Active Ratio (%) - Ratio of number of active cases to total cases
Discharge Ratio (%) - Ratio of number of discharged cases to total cases
Death Ratio (%) - Ratio of number of deaths to total cases
Dose 1 - Number of first dose of vaccine given
Dose 2 - Number of second dose of vaccine given
Total Vaccination Doses- Total number of vaccine doses given

The datasets are taken from the website: https://www.kaggle.com/datasets/anandhuh/covid19-india-statewise-vaccine-data

Another vaccination dataset is used in this project from kaggle website. It is named as Covid-19 India Statewise Vaccine.It contains Covid-19 Vaccine data from all the states and union territories of India as on August 09, 2022. It contains 5 columns and 36 rows. It contains columns which contains:
State/UTs - Names of states and union territories of India
Total Vaccination Doses- Total number of vaccine doses given
Dose 1 - Number of first dose of vaccine given
Dose 2 - Number of second dose of vaccine given
Population - Population of the state/UT

PreProcessing:

We preprocess all the data by using basic techniques like dropping all the rows with missing values. The main preprocessing to be done for this analysis is to remove all the other unnecessary columns from the dataset. 

Exploratory Data Analysis:

At first, we create a pivot table statewise with columns Active, Discharged, Deaths with index as State/UTs. We create a column Recovery from columns Discharged by Active and sort in ascending order. The data values are arranged and values are identified by coloring using matplotlib. We create a column Current Cases from columns Discharged, Active and Deaths. Find the top 10 active cases from current cases and sort them.

Plot the figure of the data retrieved. Plot barplot and lineplot to show about Top 10 active cases in India Statewise. We will find the statistics of number of people who have put dose 1 and dose 2. We will plot to find the top 5 vaccinated states of India. 
