# Vaccination rates

## Introduction
Evaluation of successful vaccination programs is important to combat potential pandemics in the future. Here, the countries were determined where herd immunity against COVID-19 was achieved, hence making these vaccination programs efficient. For this the end-date was predicted when each country can finish making vaccinations by modeling vaccination dinamics with logistic regression.


## Data
Dataframe from Kaggle was used that described COVID-19 World Vaccination Progress. Data was collected across every country and in the continents in general. The population ratio for herd immunity against common viruses including SARS-Cov-2  was found online. 

## Methods
After cleaning the data and visualising the rates of vaccinations in different countries and continents, the vaccinations data was extrapolated and date was predicted when each country can achive herd immunity from COVID-19.

The result of this project is a dataframe containing id the names of the countries and the predicted date when the population is fully vaccinated.

## Results
- The countries that reached the threshold of herd immunity were found.   
- For those countries that can reach this threshold, the date of the threshold attainment was calculated.    

- The vaccination rates were examined, cleaned and plotted for each country and continent.
- The vaccination rates were extrapolated. 
    - This regression fitted the data from 199 countries with $R^2 > 0.9$. 
    - Other counties were not analyzed due to lack of data.
- Out of these 199 countries only 38 showed accomplishment of reaching the status of 75% immunized population, which is the lowest threshold for herd immunity for alpha variant of COVID-19.
- Other countries cannot surpass the threshold of herd immunity.


## Files
- **Vaccination_rates.ipynb** - Main notebook with description of the project, code, graphs, and commentaries.
