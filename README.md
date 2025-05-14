# Global-Covid-19-vaccination-analysis
Global Covid 19 vaccination analysis



    Top 5 Countries by Vaccination Coverage:
    | COUNTRY              | PERSONS_VACCINATED_1PLUS_DOSE_PER100   |
    |:---------------------|:---------------------------------------|
    | Puerto Rico          | 100                                    |
    | United Arab Emirates | 100                                    |
    | Brunei Darussalam    | 100                                    |
    | Niue                 | 100                                    |
    | Nauru                | 100                                    |
    
    Global Vaccination Progress:
    Total Vaccinations: 13,658,220,081
    People with At Least One Dose: 5,610,057,847
    People Fully Vaccinated: 5,167,774,734
    People with Booster Dose: 2,507,135,738
    
    Average Vaccination Coverage by WHO Region:
    | WHO_REGION   | PERSONS_VACCINATED_1PLUS_DOSE_PER100   |
    |:-------------|:---------------------------------------|
    | SEARO        | 80.8                                   |
    | WPRO         | 75.9355                                |
    | AMRO         | 68.4667                                |
    | EURO         | 63.1273                                |
    | EMRO         | 56.1818                                |
    | AFRO         | 42.8261                                |
    
    Correlation Matrix of Vaccination Metrics:
    |                                      | TOTAL_VACCINATIONS   | PERSONS_VACCINATED_1PLUS_DOSE   | TOTAL_VACCINATIONS_PER100   | PERSONS_VACCINATED_1PLUS_DOSE_PER100   | PERSONS_BOOSTER_ADD_DOSE_PER100   |
    |:-------------------------------------|:---------------------|:--------------------------------|:----------------------------|:---------------------------------------|:----------------------------------|
    | TOTAL_VACCINATIONS                   | 1                    | 0.993088                        | 0.141577                    | 0.159708                               | 0.10746                           |
    | PERSONS_VACCINATED_1PLUS_DOSE        | 0.993088             | 1                               | 0.114972                    | 0.146676                               | 0.0776772                         |
    | TOTAL_VACCINATIONS_PER100            | 0.141577             | 0.114972                        | 1                           | 0.913382                               | 0.91486                           |
    | PERSONS_VACCINATED_1PLUS_DOSE_PER100 | 0.159708             | 0.146676                        | 0.913382                    | 1                                      | 0.788053                          |
    | PERSONS_BOOSTER_ADD_DOSE_PER100      | 0.10746              | 0.0776772                       | 0.91486                     | 0.788053                               | 1                                 |
    
    Missing Values:
    |                            | 0       |
    |:---------------------------|:--------|
    | WHO_REGION                 | 2.7907  |
    | DATE_UPDATED               | 3.25581 |
    | VACCINES_USED              | 100     |
    | FIRST_VACCINE_DATE         | 8.83721 |
    | NUMBER_VACCINES_TYPES_USED | 100     |

