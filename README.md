1. Overview

The file contains the various data sources used to conduct our study. It is also linked to codes (do.file) and our various Stata (for tables) and Excel (for figures) databases. To replicate the study using Stata software, the replicator must follow the codes mentioned in the do.file to obtain the results.  
Regarding the figures, the Excel file indicates the data for their reproduction in the various sheets.

2. Data Availability

Data Sources

Filename 1: CPIA transparency, accountability, and corruption in the public sector rating (1=low to 6=high)
Source: World Bank’s World Development Indicators
Access year: 2023
URL: https://data.worldbank.org/indicator/IQ.CPA.TRAN.XQ
	License:  All data are publicly available.

Filename 2: Total natural resources rents (% of GDP)
Source: World Bank’s World Development Indicators
Access year: 2023
URL: https://data.worldbank.org/indicator/NY.GDP.TOTL.RT.ZS
	License: All data are publicly available.

Filename 3: Life expectancy at birth, total (years)
Source:  World Bank’s World Development Indicators
Access year: 2023
URL: https://data.worldbank.org/indicator/SP.DYN.LE00.IN
	License: All data are publicly available.

Filename 4: GDP per capita (constant 2015 US$)
Source:  World Bank’s World Development Indicators
Access year: 2023
URL: https://data.worldbank.org/indicator/NY.GDP.PCAP.KD
	License: All data are publicly available.

Filename 5: International Migrant Stock 2020: Destination and origin		
Source: UNDESA
Access year: 2023
URL: https://www.un.org/development/desa/pd/content/international-migrant-stock
	License: All data are publicly available.

Filename 6: Political Rights and civil liberties, especially Country and Territory Ratings and Statuses, 1973-2025 (Excel Download)
Source: Freedom House
Access year: 2023
 URL: https://freedomhouse.org/report/freedom-world#Data
	License: All data are publicly available.
           
Filename 7: diaspora savings (International Migrant Stock 2020: Destination and origin; Labor force, total; Population ages 0-14, total; Population ages 65 and above, total)
Source: UNDESA; World Bank’s World Development Indicators.
Access year: 2023
URL: https://data.worldbank.org/indicator/SP.POP.65UP.TO 
    https://donnees.banquemondiale.org/indicateur/SP.POP.0014.TO
    https://data.worldbank.org/indicator/SL.TLF.TOTL.IN
    https://www.un.org/development/desa/pd/content/international-migrant-stock
 	License: All data are publicly available.

  Filename 8 : Sum of imports and exports - Total trade in goods (Percentage of Gross Domestic Product)
Source: UNCTAD
Access year : 2023
URL: https://unctadstat.unctad.org/datacentre/dataviewer/US.GoodsAndServTradeOpennessBpm6
License: All data are publicly available.

Filename 9 : Foreign direct investment: Inward and outward flows and stock, annual, especially Inward flow US$ at current prices in millions
            Gross domestic product: Total and per capita, current and constant (2015) prices: especially US$ at current prices in millions
 Source: UNCTAD
Access year : 2023 
URL: https://unctadstat.unctad.org/datacentre/dataviewer/US.FdiFlowsStock
     https://unctadstat.unctad.org/datacentre/dataviewer/US.GDPTotal
License: All data are publicly available.     

Filename 10: Political Stability and Absence of Violence/Terrorism: Percentile Rank
Source: World Bank’s Worldwide Governance Indicators
Access year : 2023 
URL: https://databank.worldbank.org/source/worldwide-governance-indicators
License: All data are publicly available.

 
    Statement about Rights
    
 I certify that the author(s) of the manuscript have legitimate access to and permission to use the data used in this manuscript.
 

 3. Instructions for Replicators

execute the codes with the different databases. For replication, everything is explained in the do.file.


4. List of Exhibits

The provided codes reproduces all tables and figures in the paper.


5. Software Requirements

Stata 17

-xtset id year;
- outreg2;
- estout.


  











