# Ontario-Energy-Demand

## About Dataset
IESO stands for Independent Electricity System Operator, which is the organization responsible for managing the electricity system and ensuring the reliable operation of the electrical grid in Ontario, Canada.

One of the primary roles of IESO is to balance the supply and demand of electricity in Ontario. They do this by predicting the amount of electricity that will be needed at any given time and coordinating the generation and distribution of that electricity to ensure that the supply matches the demand.

To accomplish this, IESO uses a variety of tools and processes to monitor and manage the electrical grid. These include real-time monitoring of electricity usage, dispatching power plants to generate electricity as needed, and managing the flow of electricity across the grid to ensure that it reaches the areas where it is needed most.

IESO also works closely with electricity generators, transmission and distribution companies, and other stakeholders to plan for the future of Ontario's electricity system. This includes forecasting future energy demand, developing new sources of electricity generation, and implementing policies to encourage energy conservation and efficiency.

This dataset contains hourly information on both the demand and price spanning from 2003 to 2023.

hour: Hour 1 is from 12 am. to 1 am., Hour 2 is from 1 am. to 2 am. Hours 1-24 are the hours from midnight one day through midnight the next day. Eastern Standard Time is used year-round.

hourly_demand: total hourly Ontario demand in kWh

average_hourly_price: The average weighted hourly price in Canadian cents/kWh. Also known as the Hourly Ontario Energy Price (HOEP), it is the average of the twelve market clearing prices (MCP) set in each hour. A new MCP is set every five minutes. Averages are weighted by the amount of electricity used throughout the province within each hour
