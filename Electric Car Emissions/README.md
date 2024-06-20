# Electric Car Emissions Analysis

## Description

This purpose of this code is to determine how the electricity mix of different states affects the carbon emissions of electric vehicles.  Production emissions and driving emissions are considered and compared between electric vehicles and gasoline vehicles.

## Skills Demonstrate
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization

## Dataset

The datasets used in this project include data on the electricity generation and resulting carbon emissions in each state. 

## Methodology
**Data Cleaning**: Extracted year 2022 and grouped by state and electricity source.  Made two datasets compatable for merging.  <br />
**EDA**: Determined the Average Emissions from Generated Electricity in lbs CO2 per kWh.  Found annual emissions of All-electric, Plug-in Hybrid, Hybrid and Gasoline Vehicles in each state.  Further went on to determine the numbers of years an electric car would have to drive to offset the higher production emissions.  Also found the reduction in carbon emissions if each type of electric car were to be driven for 5 years.  <br />
**Visualization**: Utilized Tableau to create dashboards demonstrating the annual emissions of different types of cars, the total amount in reduction of carbon emissions based on the adoption of electric cars, the states with the lowest amount of years needed to drive electric cars to offset their production emissions, and the number of years that needs to be driven per state. 

## Results

- The top states with the best electricity mix and thus the lowest annual carbon emissions for electric vehicles are Vermont, Washington, Oregon, New Hampshire and Idaho.
- The state with the highest number of years needed to drive an all-electric car to offset production emissions was West Virginia, with 2.8 years needed.
- If electric cars were to be adopted with a mix of 50% All-electric vehicles, 20% Plug-in Hybrid Vehicles, 15% Hybrid Vehicles and 15% Gasoline Vehicles, there would be a reduction of 8-9 trillion lbs. CO2 which is over half of the carbon emissions reported in 2022.

## Usage 

To run this analysis, open the 'Electric Car Emissions by State.ipynb' notebook and execute the cells.
