# CU Fintech Bootcamp Project1

## What Drives Bitcoin's Price?  

### Team
- Manpreet Padam
- Victor Ramirez 
- Jennifer Mulroy 

#### Scope

The scope of the project is to identify patterns in Bitcoin trading data to determine what drives the price of Bitcoin. We will perform statistical analysis that will include daily volatility, trading volume, and cumulative returns to find relationships between the data and supply and demand factors. 
 
### Questions to Answer and Research: 
 - Is it a good long term investment or short investment? 
 - Can we apply traditional market statistic analysis on crytpo trading data? 
 - How will we determine which datasets will provide the most value to the analysis objective? 
 
### Methods

define financial calculations used in the project

### Structure

1. Call api data from:
    get_yahoo_data
    glassnode
    IEX? 
    CSV

All data calls will be wrapped in a class to retrieve from api source, clean and return a dictonary of dataframes for further analysis. 

2. Run financial simulations:
    