# COVID19-Vaccinations
R, Julia


#Data Sourced from
https://www.cia.gov/the-world-factbook/
https://www.ncei.noaa.gov/products/land-based-station/global-historical-climatology-network-daily
https://covid19.who.int/WHO-COVID-19-global-table-data.csv 
https://covid19.who.int/who-data/vaccination-data.csv 
https://covidtrackerapi.bsg.ox.ac.uk/api/v2/stringency/date-range/{YYYY-MM-DD}/{YYYY-MM-DD}
https://www.oecd.org/about/members-and-partners/


#Population variables and GDP
"country" This is the country's name.
"urbanisation_rate" This is the urbanisation rate, which is the percentage of the population that lives in urban areas.
"urbanisation_yearly_change" This is the average rate that the urbanisation rate has been changing every year averaged over the last 20 years.
"gdp_per_cap" This is the real GDP per capita rate, the real means this variable is based on purchasing power.
"size" This is the size of the country in squared kilometres. 
"population" This is the population size for 2021
"density" This is the number of people that live in an average square kilometre.
"country code" This is the three-letter code representing the country.

#Climate_2021_2020
fips: 2 letter FIPS country code
tavg: Average temperature 2021 & 2020 (degrees Celsius).
prcp: Average daily precipitation 2021 & 2020 (milimeters).
iso3166: 2 character ISO-3166 country code.
Name: Country name.


#COVID-19 Vaccination rates for the latest date(22/10/2021) and OECD countries
#Variables in COVID-19 Vaccination rates 
country_code - ISO-3 Character 
country_name - Country name
region - Country in a specific region, as WHO Member States are grouped into six regions
total_cases - Total number of COVID-19 cases 
total_deaths  - Total number of deaths due to COVID-19 
total_vaccinations - Total number of vaccinations administered for COVID-19 
vaccinated_1dose - Total number of people vaccinated by single dose 
fully_vacccinated - Total number of people fully vaccinated
total_vaccinations_per100 - Total number of vaccinations per 100 people in total population
percent_full_vac - Percentage of people fully vaccinated
first_vaccine_date - Vaccination start date by country
last_updated_date - Last updated date
stringency - Stringency index is the measure from 0 to 100 based on ordinal calculations of people’s behaviour in terms of lockdowns during the pandemic. Like social distancing, facemasks, hand hygiene, banning or limited public place gatherings, closures of schools, parks and work places, economic aids, prioritising the vaccinations are some of the measures taken to minimise the spread of infection and mortalities in the community. 

#variables in OECD members
country_code - ISO-3 Character 
country_name - Country name

#Variables added in Final dataset
Infection rate per 1000: total cases by population per 1000
Deaths per 1000: total daeths by population per 1000
Total vaccinations per 1000: total vaccinations by population per 1000
OECD: Organisation for Economic Cooperation and Development
OECD country: If the country in OECD category then Yes otherwise No 
